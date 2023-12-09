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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 2.0 | 1.03 ± 0.31 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.9 | 1.9 | 1.03 ± 0.29 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 2.1 | 1.03 ± 0.31 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.9 | 1.9 | 1.04 ± 0.31 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 1.9 | 1.07 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.12 ± 0.35 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.1 | 1.15 ± 0.34 |
| mattcl-ts | input-mattcl | 14.8 ± 0.4 | 13.9 | 15.9 | 12.46 ± 2.81 |
| mattcl-ts | input-kcen | 14.9 ± 0.3 | 14.0 | 15.8 | 12.57 ± 2.83 |
| mattcl-ts | input-lanjian | 14.9 ± 0.3 | 14.0 | 16.0 | 12.58 ± 2.83 |
| mattcl-ts | input-pting | 14.9 ± 0.4 | 13.8 | 15.9 | 12.58 ± 2.83 |
| mattcl-py | input-mattcl | 22.3 ± 0.9 | 21.2 | 25.7 | 18.81 ± 4.28 |
| pting | input-mattcl | 22.5 ± 0.8 | 21.0 | 25.5 | 18.92 ± 4.29 |
| pting | input-kcen | 22.7 ± 0.8 | 21.5 | 26.1 | 19.10 ± 4.33 |
| pting | input-lanjian | 22.8 ± 0.6 | 21.7 | 26.0 | 19.21 ± 4.34 |
| mattcl-py | input-kcen | 22.8 ± 0.8 | 21.7 | 26.2 | 19.22 ± 4.36 |
| mattcl-py | input-lanjian | 22.8 ± 0.9 | 21.4 | 26.5 | 19.23 ± 4.38 |
| mattcl-py | input-pting | 23.1 ± 0.7 | 21.8 | 26.1 | 19.48 ± 4.40 |
| pting | input-pting | 23.5 ± 5.1 | 21.8 | 77.9 | 19.80 ± 6.14 |
| kcen | input-mattcl | 28.3 ± 0.9 | 26.9 | 31.2 | 23.78 ± 5.38 |
| kcen | input-kcen | 29.1 ± 0.9 | 27.8 | 32.7 | 24.51 ± 5.54 |
| kcen | input-lanjian | 29.3 ± 0.9 | 27.7 | 32.3 | 24.62 ± 5.57 |
| kcen | input-pting | 29.6 ± 0.8 | 28.3 | 33.3 | 24.89 ± 5.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|