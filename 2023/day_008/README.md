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
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 1.8 | 1.04 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 2.0 | 1.04 ± 0.31 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.0 | 1.05 ± 0.32 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 2.0 | 1.05 ± 0.30 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.12 ± 0.33 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.1 | 1.15 ± 0.33 |
| mattcl | input-pting | 1.6 ± 4.7 | 0.9 | 67.5 | 1.31 ± 3.96 |
| mattcl-ts | input-lanjian | 15.2 ± 0.4 | 14.3 | 16.2 | 12.82 ± 2.79 |
| mattcl-ts | input-kcen | 15.2 ± 0.4 | 14.4 | 16.8 | 12.83 ± 2.79 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.5 | 17.1 | 12.89 ± 2.81 |
| mattcl-ts | input-mattcl | 15.4 ± 3.1 | 14.1 | 58.8 | 12.94 ± 3.85 |
| pting | input-mattcl | 22.5 ± 0.7 | 21.1 | 25.7 | 18.90 ± 4.14 |
| mattcl-py | input-mattcl | 22.6 ± 2.8 | 21.0 | 53.8 | 19.02 ± 4.76 |
| mattcl-py | input-lanjian | 22.8 ± 0.7 | 21.8 | 25.7 | 19.19 ± 4.20 |
| mattcl-py | input-kcen | 22.9 ± 0.7 | 21.7 | 25.9 | 19.24 ± 4.21 |
| pting | input-kcen | 22.9 ± 0.8 | 21.6 | 27.4 | 19.24 ± 4.22 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.8 | 26.7 | 19.27 ± 4.23 |
| pting | input-pting | 23.2 ± 1.0 | 22.0 | 31.3 | 19.53 ± 4.31 |
| mattcl-py | input-pting | 23.3 ± 0.8 | 22.2 | 26.3 | 19.62 ± 4.30 |
| kcen | input-mattcl | 28.4 ± 0.8 | 27.1 | 31.4 | 23.88 ± 5.21 |
| kcen | input-lanjian | 29.1 ± 1.0 | 27.5 | 32.6 | 24.51 ± 5.36 |
| kcen | input-kcen | 29.3 ± 0.9 | 28.1 | 32.6 | 24.67 ± 5.39 |
| kcen | input-pting | 29.6 ± 0.7 | 28.1 | 31.9 | 24.93 ± 5.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|