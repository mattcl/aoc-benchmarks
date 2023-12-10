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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.8 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.04 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.9 | 1.9 | 1.05 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 1.8 | 1.06 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.9 | 1.8 | 1.06 ± 0.31 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.9 | 2.1 | 1.08 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.14 ± 0.34 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.9 | 1.18 ± 0.36 |
| mattcl-ts | input-mattcl | 14.6 ± 0.3 | 13.8 | 15.7 | 12.72 ± 2.77 |
| mattcl-ts | input-kcen | 14.8 ± 0.3 | 14.2 | 15.7 | 12.89 ± 2.80 |
| mattcl-ts | input-lanjian | 14.9 ± 0.5 | 13.8 | 18.7 | 12.92 ± 2.82 |
| mattcl-ts | input-pting | 14.9 ± 0.3 | 14.0 | 15.8 | 12.94 ± 2.81 |
| mattcl-py | input-mattcl | 22.2 ± 0.7 | 21.2 | 25.3 | 19.29 ± 4.21 |
| pting | input-mattcl | 22.3 ± 0.9 | 21.2 | 26.7 | 19.43 ± 4.27 |
| mattcl-py | input-lanjian | 22.5 ± 0.7 | 21.5 | 26.0 | 19.60 ± 4.28 |
| pting | input-kcen | 22.6 ± 0.7 | 21.5 | 25.7 | 19.67 ± 4.30 |
| mattcl-py | input-kcen | 22.6 ± 0.7 | 21.8 | 25.4 | 19.68 ± 4.29 |
| pting | input-lanjian | 22.7 ± 0.7 | 21.8 | 25.3 | 19.76 ± 4.31 |
| mattcl-py | input-pting | 23.0 ± 0.8 | 22.1 | 25.8 | 19.97 ± 4.37 |
| pting | input-pting | 23.1 ± 0.8 | 22.0 | 26.9 | 20.07 ± 4.40 |
| kcen | input-mattcl | 28.2 ± 0.9 | 27.1 | 31.1 | 24.53 ± 5.36 |
| kcen | input-lanjian | 29.0 ± 0.7 | 27.8 | 32.1 | 25.18 ± 5.48 |
| kcen | input-kcen | 29.1 ± 0.5 | 28.2 | 31.3 | 25.32 ± 5.49 |
| kcen | input-pting | 29.3 ± 0.6 | 28.2 | 31.1 | 25.52 ± 5.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|