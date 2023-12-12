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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.9 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 1.8 | 1.03 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 1.9 | 1.04 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.9 | 1.9 | 1.05 ± 0.32 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.9 | 1.07 ± 0.33 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 2.0 | 1.08 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 2.0 | 1.10 ± 0.32 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.12 ± 0.33 |
| mattcl-ts | input-mattcl | 15.1 ± 0.3 | 14.3 | 16.0 | 12.64 ± 2.91 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.5 | 16.7 | 12.80 ± 2.95 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.3 | 16.5 | 12.81 ± 2.95 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 14.6 | 16.8 | 12.82 ± 2.95 |
| pting | input-mattcl | 22.3 ± 0.7 | 21.3 | 25.5 | 18.75 ± 4.33 |
| mattcl-py | input-mattcl | 22.4 ± 0.8 | 20.9 | 25.7 | 18.79 ± 4.36 |
| mattcl-py | input-lanjian | 22.7 ± 0.8 | 21.7 | 25.9 | 19.07 ± 4.41 |
| mattcl-py | input-kcen | 22.8 ± 0.7 | 21.8 | 26.4 | 19.14 ± 4.43 |
| pting | input-kcen | 22.8 ± 0.8 | 21.7 | 25.5 | 19.17 ± 4.45 |
| pting | input-lanjian | 22.8 ± 0.8 | 21.8 | 25.8 | 19.17 ± 4.44 |
| mattcl-py | input-pting | 23.2 ± 0.8 | 22.1 | 26.2 | 19.44 ± 4.50 |
| pting | input-pting | 23.2 ± 1.4 | 21.8 | 36.2 | 19.45 ± 4.61 |
| kcen | input-mattcl | 28.6 ± 1.4 | 27.0 | 40.5 | 23.96 ± 5.62 |
| kcen | input-lanjian | 29.2 ± 0.8 | 27.9 | 31.4 | 24.50 ± 5.65 |
| kcen | input-kcen | 29.3 ± 0.7 | 28.0 | 31.4 | 24.60 ± 5.67 |
| kcen | input-pting | 29.6 ± 0.8 | 28.4 | 32.6 | 24.81 ± 5.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|