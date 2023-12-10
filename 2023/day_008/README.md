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
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 1.8 | 1.01 ± 0.30 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.02 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.9 | 1.8 | 1.02 ± 0.30 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.9 | 2.0 | 1.05 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 2.1 | 1.11 ± 0.31 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.14 ± 0.34 |
| lanjian | input-pting | 2.9 ± 5.9 | 0.9 | 33.1 | 2.49 ± 5.12 |
| mattcl-ts | input-pting | 14.8 ± 0.4 | 13.8 | 16.2 | 12.75 ± 2.82 |
| mattcl-ts | input-kcen | 14.9 ± 0.3 | 14.1 | 15.8 | 12.81 ± 2.82 |
| mattcl-ts | input-mattcl | 16.8 ± 8.1 | 13.9 | 83.7 | 14.45 ± 7.70 |
| mattcl-ts | input-lanjian | 22.0 ± 15.3 | 14.2 | 71.3 | 18.99 ± 13.82 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.1 | 25.6 | 19.32 ± 4.28 |
| mattcl-py | input-mattcl | 22.7 ± 0.8 | 21.3 | 25.4 | 19.54 ± 4.33 |
| mattcl-py | input-pting | 22.8 ± 0.6 | 21.9 | 25.3 | 19.64 ± 4.34 |
| pting | input-pting | 22.9 ± 0.8 | 21.9 | 28.7 | 19.73 ± 4.38 |
| pting | input-lanjian | 23.2 ± 0.7 | 21.9 | 25.9 | 19.99 ± 4.42 |
| mattcl-py | input-kcen | 23.5 ± 4.6 | 22.2 | 74.8 | 20.20 ± 5.96 |
| mattcl-py | input-lanjian | 23.6 ± 1.2 | 22.6 | 36.0 | 20.29 ± 4.57 |
| pting | input-kcen | 25.8 ± 5.2 | 22.5 | 38.3 | 22.21 ± 6.61 |
| kcen | input-mattcl | 28.8 ± 0.8 | 27.2 | 31.4 | 24.78 ± 5.48 |
| kcen | input-lanjian | 30.2 ± 0.8 | 28.8 | 32.6 | 26.00 ± 5.74 |
| kcen | input-pting | 30.3 ± 3.6 | 28.6 | 52.2 | 26.11 ± 6.51 |
| kcen | input-kcen | 32.2 ± 8.6 | 28.2 | 87.9 | 27.70 ± 9.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|