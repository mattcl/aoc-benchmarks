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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.9 | 1.8 | 1.00 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.9 | 1.9 | 1.05 ± 0.30 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.08 ± 0.32 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.9 | 1.9 | 1.09 ± 0.31 |
| mattcl | input-lanjian | 1.3 ± 2.0 | 0.9 | 29.7 | 1.12 ± 1.72 |
| lanjian | input-pting | 1.4 ± 0.2 | 1.0 | 2.1 | 1.15 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.2 | 1.0 | 2.0 | 1.18 ± 0.31 |
| lanjian | input-lanjian | 2.0 ± 5.5 | 0.9 | 46.5 | 1.71 ± 4.59 |
| mattcl-ts | input-mattcl | 14.6 ± 0.4 | 13.7 | 15.5 | 12.24 ± 2.58 |
| mattcl-ts | input-pting | 15.0 ± 0.4 | 14.0 | 16.8 | 12.51 ± 2.64 |
| mattcl-ts | input-lanjian | 15.1 ± 3.7 | 13.7 | 66.1 | 12.66 ± 4.07 |
| mattcl-ts | input-kcen | 15.2 ± 0.4 | 14.2 | 17.4 | 12.73 ± 2.69 |
| mattcl-py | input-mattcl | 22.3 ± 0.8 | 21.2 | 25.2 | 18.65 ± 3.96 |
| pting | input-mattcl | 22.3 ± 0.7 | 21.4 | 25.6 | 18.69 ± 3.96 |
| mattcl-py | input-lanjian | 22.7 ± 0.7 | 21.8 | 25.9 | 18.99 ± 4.03 |
| pting | input-lanjian | 22.9 ± 0.9 | 21.9 | 25.9 | 19.16 ± 4.09 |
| mattcl-py | input-pting | 22.9 ± 0.7 | 21.9 | 25.9 | 19.18 ± 4.06 |
| pting | input-pting | 23.2 ± 0.9 | 21.9 | 26.9 | 19.42 ± 4.14 |
| pting | input-kcen | 23.4 ± 2.8 | 22.1 | 51.7 | 19.55 ± 4.71 |
| mattcl-py | input-kcen | 23.5 ± 0.6 | 22.5 | 25.6 | 19.66 ± 4.15 |
| kcen | input-mattcl | 28.1 ± 0.8 | 27.1 | 30.9 | 23.49 ± 4.97 |
| kcen | input-lanjian | 29.1 ± 0.8 | 27.9 | 32.5 | 24.35 ± 5.15 |
| kcen | input-pting | 29.8 ± 2.6 | 28.6 | 55.1 | 24.95 ± 5.68 |
| kcen | input-kcen | 29.9 ± 1.8 | 28.5 | 44.3 | 25.04 ± 5.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|