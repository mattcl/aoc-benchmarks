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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.01 ± 0.29 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.05 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.9 | 1.05 ± 0.32 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.9 | 1.9 | 1.08 ± 0.31 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 1.9 | 1.11 ± 0.32 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.12 ± 0.33 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.12 ± 0.33 |
| mattcl-ts | input-mattcl | 15.2 ± 0.3 | 14.3 | 16.1 | 13.11 ± 2.79 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.5 | 16.5 | 13.22 ± 2.81 |
| mattcl-ts | input-pting | 15.4 ± 0.4 | 14.5 | 16.3 | 13.29 ± 2.83 |
| mattcl-ts | input-kcen | 15.5 ± 3.7 | 14.5 | 66.3 | 13.42 ± 4.29 |
| mattcl-py | input-mattcl | 22.4 ± 0.8 | 21.4 | 26.5 | 19.36 ± 4.15 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.3 | 25.7 | 19.39 ± 4.15 |
| mattcl-py | input-lanjian | 22.7 ± 0.6 | 21.6 | 26.0 | 19.66 ± 4.19 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.9 | 26.1 | 19.83 ± 4.24 |
| mattcl-py | input-kcen | 23.0 ± 0.7 | 21.7 | 25.6 | 19.86 ± 4.24 |
| mattcl-py | input-pting | 23.1 ± 0.8 | 22.1 | 26.2 | 20.00 ± 4.28 |
| pting | input-pting | 23.2 ± 0.8 | 22.0 | 26.3 | 20.06 ± 4.30 |
| pting | input-kcen | 23.4 ± 4.2 | 21.7 | 63.4 | 20.28 ± 5.64 |
| kcen | input-mattcl | 28.6 ± 1.1 | 27.1 | 31.6 | 24.70 ± 5.31 |
| kcen | input-lanjian | 29.3 ± 1.0 | 28.2 | 36.3 | 25.36 ± 5.43 |
| kcen | input-kcen | 29.4 ± 0.9 | 28.0 | 32.6 | 25.46 ± 5.44 |
| kcen | input-pting | 29.9 ± 1.0 | 28.6 | 32.6 | 25.84 ± 5.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|