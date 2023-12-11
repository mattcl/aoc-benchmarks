# Day 8 benchmarks

[link to problem](https://adventofcode.com/2023/day/8)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 8)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.1 ± 0.3 | 0.8 | 1.8 | 1.00 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.8 | 1.00 ± 0.30 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.8 | 2.0 | 1.03 ± 0.31 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.8 | 1.8 | 1.04 ± 0.32 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.8 | 2.0 | 1.09 ± 0.35 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.13 ± 0.35 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.2 | 1.20 ± 0.37 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.0 | 16.7 | 13.25 ± 3.00 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.3 | 16.3 | 13.37 ± 3.03 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 14.4 | 16.4 | 13.38 ± 3.03 |
| mattcl-ts | input-pting | 15.2 ± 0.4 | 14.4 | 16.3 | 13.43 ± 3.04 |
| mattcl-py | input-mattcl | 22.3 ± 0.8 | 21.3 | 25.2 | 19.71 ± 4.50 |
| pting | input-mattcl | 22.5 ± 0.8 | 21.4 | 27.1 | 19.84 ± 4.53 |
| pting | input-kcen | 22.8 ± 0.8 | 21.6 | 26.0 | 20.13 ± 4.59 |
| mattcl-py | input-lanjian | 22.8 ± 0.9 | 21.6 | 26.0 | 20.15 ± 4.61 |
| mattcl-py | input-kcen | 22.8 ± 0.9 | 21.7 | 25.6 | 20.17 ± 4.62 |
| pting | input-lanjian | 22.9 ± 0.9 | 21.9 | 27.3 | 20.24 ± 4.62 |
| mattcl-py | input-pting | 23.0 ± 0.7 | 21.9 | 25.9 | 20.30 ± 4.62 |
| pting | input-pting | 23.1 ± 0.7 | 22.0 | 25.9 | 20.38 ± 4.63 |
| kcen | input-mattcl | 28.3 ± 1.0 | 26.8 | 31.3 | 24.98 ± 5.69 |
| kcen | input-kcen | 29.2 ± 0.8 | 27.6 | 31.8 | 25.75 ± 5.85 |
| kcen | input-lanjian | 29.2 ± 0.8 | 27.8 | 32.5 | 25.77 ± 5.85 |
| kcen | input-pting | 29.8 ± 1.0 | 28.2 | 33.8 | 26.36 ± 6.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|