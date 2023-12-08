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
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.1 | 1.03 ± 0.31 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.8 | 1.8 | 1.03 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 2.1 | 1.05 ± 0.33 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.9 | 1.9 | 1.08 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 1.9 | 1.12 ± 0.32 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.14 ± 0.33 |
| mattcl-ts | input-kcen | 14.4 ± 0.4 | 13.3 | 15.5 | 12.64 ± 2.67 |
| mattcl-ts | input-mattcl | 14.5 ± 3.3 | 13.1 | 60.7 | 12.71 ± 3.93 |
| mattcl-ts | input-pting | 14.6 ± 0.4 | 13.7 | 15.5 | 12.79 ± 2.70 |
| mattcl-ts | input-lanjian | 14.7 ± 3.9 | 13.3 | 68.3 | 12.87 ± 4.34 |
| mattcl-py | input-mattcl | 22.0 ± 0.7 | 21.1 | 25.9 | 19.26 ± 4.08 |
| pting | input-mattcl | 22.3 ± 2.1 | 21.3 | 45.7 | 19.55 ± 4.50 |
| mattcl-py | input-lanjian | 22.4 ± 0.6 | 21.4 | 25.3 | 19.62 ± 4.15 |
| pting | input-kcen | 22.5 ± 0.6 | 21.4 | 25.1 | 19.67 ± 4.15 |
| mattcl-py | input-kcen | 22.5 ± 0.8 | 21.4 | 26.3 | 19.69 ± 4.18 |
| pting | input-lanjian | 22.7 ± 1.1 | 21.9 | 30.6 | 19.90 ± 4.27 |
| pting | input-pting | 22.9 ± 0.8 | 21.8 | 25.8 | 20.04 ± 4.25 |
| mattcl-py | input-pting | 23.0 ± 0.7 | 21.8 | 26.0 | 20.09 ± 4.25 |
| kcen | input-mattcl | 28.1 ± 0.9 | 27.0 | 31.0 | 24.56 ± 5.21 |
| kcen | input-kcen | 28.9 ± 1.1 | 27.7 | 35.8 | 25.31 ± 5.38 |
| kcen | input-lanjian | 29.0 ± 1.2 | 27.7 | 35.8 | 25.35 ± 5.41 |
| kcen | input-pting | 29.5 ± 0.8 | 28.2 | 32.7 | 25.79 ± 5.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|