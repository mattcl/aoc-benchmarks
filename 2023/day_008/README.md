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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.8 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.3 | 0.8 | 1.7 | 1.00 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.03 ± 0.29 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.8 | 1.8 | 1.06 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.9 | 1.06 ± 0.32 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.8 | 2.0 | 1.09 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 2.1 | 1.12 ± 0.31 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.19 ± 0.35 |
| mattcl-ts | input-mattcl | 13.9 ± 0.4 | 12.8 | 15.2 | 12.42 ± 2.56 |
| mattcl-ts | input-lanjian | 14.1 ± 0.4 | 12.9 | 15.3 | 12.57 ± 2.60 |
| mattcl-ts | input-kcen | 14.2 ± 0.4 | 13.2 | 15.5 | 12.66 ± 2.61 |
| mattcl-ts | input-pting | 14.4 ± 0.6 | 13.5 | 19.8 | 12.86 ± 2.68 |
| mattcl-py | input-mattcl | 22.3 ± 0.7 | 21.4 | 26.0 | 19.87 ± 4.11 |
| pting | input-lanjian | 22.6 ± 0.8 | 21.7 | 28.2 | 20.15 ± 4.18 |
| mattcl-py | input-lanjian | 22.6 ± 0.7 | 21.7 | 25.9 | 20.16 ± 4.17 |
| mattcl-py | input-kcen | 22.6 ± 0.6 | 21.6 | 25.5 | 20.17 ± 4.15 |
| pting | input-kcen | 22.6 ± 0.6 | 21.6 | 25.7 | 20.18 ± 4.16 |
| pting | input-mattcl | 22.8 ± 3.2 | 21.2 | 49.1 | 20.30 ± 5.05 |
| pting | input-pting | 23.0 ± 0.7 | 21.9 | 25.8 | 20.49 ± 4.24 |
| mattcl-py | input-pting | 23.0 ± 0.8 | 21.9 | 26.2 | 20.51 ± 4.26 |
| kcen | input-mattcl | 28.2 ± 0.9 | 27.0 | 31.1 | 25.14 ± 5.20 |
| kcen | input-lanjian | 29.1 ± 1.0 | 27.7 | 32.7 | 25.93 ± 5.38 |
| kcen | input-kcen | 29.1 ± 0.8 | 27.8 | 31.9 | 26.00 ± 5.36 |
| kcen | input-pting | 29.6 ± 0.8 | 28.5 | 32.2 | 26.40 ± 5.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|