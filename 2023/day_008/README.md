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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.8 | 1.02 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.04 ± 0.31 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.05 ± 0.33 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 2.9 | 1.07 ± 0.34 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.9 | 1.07 ± 0.33 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.9 | 1.9 | 1.09 ± 0.32 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.0 | 1.16 ± 0.34 |
| mattcl-ts | input-mattcl | 14.7 ± 0.4 | 13.8 | 16.0 | 12.87 ± 2.83 |
| mattcl-ts | input-pting | 14.8 ± 0.3 | 13.8 | 16.0 | 13.01 ± 2.85 |
| mattcl-ts | input-lanjian | 14.9 ± 0.4 | 13.6 | 16.1 | 13.02 ± 2.86 |
| mattcl-ts | input-kcen | 15.5 ± 4.3 | 13.8 | 55.4 | 13.59 ± 4.77 |
| mattcl-py | input-mattcl | 22.3 ± 1.0 | 21.2 | 25.6 | 19.55 ± 4.35 |
| pting | input-mattcl | 22.3 ± 0.7 | 21.4 | 25.4 | 19.59 ± 4.32 |
| mattcl-py | input-kcen | 22.6 ± 0.7 | 21.7 | 26.0 | 19.84 ± 4.38 |
| mattcl-py | input-lanjian | 22.6 ± 0.7 | 21.7 | 25.7 | 19.84 ± 4.38 |
| pting | input-lanjian | 22.7 ± 0.9 | 21.7 | 25.9 | 19.93 ± 4.41 |
| pting | input-kcen | 22.8 ± 0.9 | 21.7 | 26.0 | 19.99 ± 4.43 |
| mattcl-py | input-pting | 22.9 ± 0.7 | 21.8 | 26.1 | 20.10 ± 4.43 |
| pting | input-pting | 23.0 ± 0.8 | 22.1 | 25.9 | 20.17 ± 4.45 |
| kcen | input-mattcl | 28.3 ± 1.0 | 26.9 | 31.3 | 24.83 ± 5.49 |
| kcen | input-kcen | 28.9 ± 0.7 | 27.8 | 31.4 | 25.35 ± 5.57 |
| kcen | input-lanjian | 29.0 ± 0.8 | 28.0 | 32.1 | 25.46 ± 5.60 |
| kcen | input-pting | 29.6 ± 0.9 | 28.5 | 33.1 | 25.96 ± 5.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|