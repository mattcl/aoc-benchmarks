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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.9 | 2.0 | 1.07 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.0 | 1.08 ± 0.31 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.9 | 2.6 | 1.08 ± 0.32 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.0 | 1.09 ± 0.32 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.12 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.16 ± 0.33 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.2 | 1.21 ± 0.35 |
| mattcl-ts | input-mattcl | 14.8 ± 0.4 | 13.9 | 15.7 | 12.86 ± 2.65 |
| mattcl-ts | input-lanjian | 14.9 ± 0.4 | 13.8 | 16.2 | 12.94 ± 2.67 |
| mattcl-ts | input-pting | 15.0 ± 0.3 | 14.0 | 16.2 | 13.05 ± 2.69 |
| mattcl-ts | input-kcen | 15.1 ± 2.1 | 14.0 | 43.0 | 13.11 ± 3.23 |
| mattcl-py | input-mattcl | 22.2 ± 0.7 | 21.4 | 25.2 | 19.32 ± 4.00 |
| pting | input-mattcl | 22.3 ± 0.7 | 21.4 | 25.4 | 19.40 ± 4.02 |
| pting | input-kcen | 22.6 ± 0.6 | 21.7 | 25.8 | 19.65 ± 4.06 |
| mattcl-py | input-kcen | 22.7 ± 0.6 | 21.8 | 25.2 | 19.70 ± 4.07 |
| mattcl-py | input-lanjian | 22.8 ± 1.9 | 21.7 | 42.4 | 19.79 ± 4.37 |
| pting | input-lanjian | 22.8 ± 0.9 | 21.6 | 26.3 | 19.85 ± 4.14 |
| pting | input-pting | 23.0 ± 0.8 | 22.1 | 26.1 | 20.00 ± 4.15 |
| mattcl-py | input-pting | 23.1 ± 0.9 | 22.1 | 26.7 | 20.08 ± 4.19 |
| kcen | input-mattcl | 28.1 ± 0.9 | 27.0 | 31.0 | 24.47 ± 5.07 |
| kcen | input-kcen | 29.0 ± 0.6 | 28.1 | 31.3 | 25.23 ± 5.20 |
| kcen | input-lanjian | 29.2 ± 1.2 | 27.9 | 36.0 | 25.42 ± 5.31 |
| kcen | input-pting | 29.5 ± 0.6 | 28.5 | 31.8 | 25.67 ± 5.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|