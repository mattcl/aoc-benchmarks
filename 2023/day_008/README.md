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
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 2.0 | 1.03 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 1.8 | 1.04 ± 0.32 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.8 | 1.04 ± 0.31 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.32 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.9 | 2.1 | 1.13 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.14 ± 0.34 |
| mattcl | input-pting | 1.6 ± 5.0 | 0.8 | 71.4 | 1.36 ± 4.34 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.2 | 16.1 | 13.03 ± 2.86 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.1 | 16.1 | 13.08 ± 2.87 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.3 | 16.5 | 13.14 ± 2.88 |
| mattcl-ts | input-pting | 15.2 ± 0.3 | 14.5 | 16.1 | 13.21 ± 2.90 |
| pting | input-mattcl | 22.2 ± 0.5 | 21.5 | 24.6 | 19.36 ± 4.25 |
| mattcl-py | input-mattcl | 22.4 ± 0.8 | 21.1 | 25.7 | 19.51 ± 4.32 |
| mattcl-py | input-lanjian | 22.6 ± 0.7 | 21.8 | 25.2 | 19.69 ± 4.34 |
| pting | input-kcen | 22.7 ± 0.7 | 21.8 | 25.6 | 19.79 ± 4.37 |
| mattcl-py | input-kcen | 22.8 ± 0.7 | 22.0 | 25.6 | 19.88 ± 4.38 |
| pting | input-lanjian | 22.8 ± 0.8 | 21.7 | 26.0 | 19.88 ± 4.39 |
| pting | input-pting | 23.1 ± 0.9 | 22.1 | 26.0 | 20.11 ± 4.46 |
| mattcl-py | input-pting | 23.1 ± 0.7 | 22.1 | 26.0 | 20.13 ± 4.44 |
| kcen | input-mattcl | 28.3 ± 1.1 | 26.8 | 35.5 | 24.65 ± 5.47 |
| kcen | input-lanjian | 29.1 ± 0.7 | 27.9 | 31.7 | 25.33 ± 5.57 |
| kcen | input-kcen | 29.2 ± 0.9 | 28.1 | 32.1 | 25.45 ± 5.61 |
| kcen | input-pting | 29.6 ± 0.7 | 28.5 | 32.4 | 25.75 ± 5.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|