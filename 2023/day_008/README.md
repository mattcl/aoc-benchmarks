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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.9 | 2.0 | 1.00 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 1.0 | 2.1 | 1.03 ± 0.27 |
| mattcl | input-pting | 1.4 ± 0.3 | 1.0 | 2.2 | 1.05 ± 0.29 |
| mattcl | input-lanjian | 1.4 ± 0.3 | 1.0 | 2.1 | 1.06 ± 0.29 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.2 | 1.06 ± 0.27 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.1 | 1.07 ± 0.28 |
| lanjian | input-pting | 1.4 ± 0.2 | 1.0 | 2.2 | 1.10 ± 0.28 |
| lanjian | input-kcen | 1.5 ± 0.3 | 1.0 | 2.4 | 1.13 ± 0.29 |
| mattcl-ts | input-lanjian | 15.4 ± 0.3 | 14.5 | 16.8 | 11.92 ± 2.28 |
| mattcl-ts | input-kcen | 15.4 ± 0.4 | 14.6 | 16.6 | 11.93 ± 2.28 |
| mattcl-ts | input-pting | 15.4 ± 0.4 | 14.6 | 16.8 | 11.96 ± 2.29 |
| mattcl-ts | input-mattcl | 15.5 ± 3.1 | 14.4 | 57.9 | 12.01 ± 3.31 |
| pting | input-mattcl | 22.5 ± 0.8 | 21.4 | 26.8 | 17.42 ± 3.36 |
| mattcl-py | input-mattcl | 22.5 ± 0.6 | 21.2 | 25.1 | 17.43 ± 3.34 |
| pting | input-kcen | 22.8 ± 0.6 | 21.9 | 25.8 | 17.68 ± 3.39 |
| mattcl-py | input-lanjian | 23.1 ± 0.9 | 21.7 | 26.5 | 17.86 ± 3.46 |
| pting | input-pting | 23.2 ± 0.7 | 21.8 | 26.0 | 18.00 ± 3.46 |
| mattcl-py | input-kcen | 23.3 ± 0.8 | 22.3 | 26.1 | 18.01 ± 3.48 |
| mattcl-py | input-pting | 23.3 ± 0.7 | 22.2 | 25.9 | 18.04 ± 3.46 |
| pting | input-lanjian | 23.5 ± 4.1 | 22.1 | 67.9 | 18.18 ± 4.68 |
| kcen | input-mattcl | 28.4 ± 0.7 | 27.1 | 31.5 | 22.00 ± 4.21 |
| kcen | input-lanjian | 29.5 ± 1.8 | 27.9 | 45.7 | 22.87 ± 4.56 |
| kcen | input-kcen | 29.5 ± 0.8 | 28.4 | 32.7 | 22.88 ± 4.39 |
| kcen | input-pting | 29.8 ± 0.8 | 28.6 | 32.9 | 23.06 ± 4.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|