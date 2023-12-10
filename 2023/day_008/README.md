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
| mattcl | input-mattcl | 1.1 ± 0.3 | 0.7 | 1.8 | 1.00 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.33 |
| mattcl | input-lanjian | 1.1 ± 0.3 | 0.8 | 1.8 | 1.02 ± 0.34 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.04 ± 0.34 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.9 | 1.05 ± 0.34 |
| lanjian | input-pting | 1.2 ± 0.3 | 0.8 | 2.1 | 1.10 ± 0.36 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.15 ± 0.37 |
| mattcl | input-kcen | 1.4 ± 3.6 | 0.8 | 51.7 | 1.24 ± 3.21 |
| mattcl-ts | input-mattcl | 14.6 ± 0.4 | 13.4 | 15.8 | 13.00 ± 3.25 |
| mattcl-ts | input-lanjian | 14.7 ± 0.3 | 13.9 | 15.6 | 13.15 ± 3.28 |
| mattcl-ts | input-kcen | 14.8 ± 0.4 | 13.9 | 15.6 | 13.20 ± 3.30 |
| mattcl-ts | input-pting | 14.8 ± 0.3 | 13.7 | 15.7 | 13.25 ± 3.30 |
| mattcl-py | input-mattcl | 22.3 ± 0.7 | 21.5 | 25.5 | 19.89 ± 4.99 |
| pting | input-mattcl | 22.3 ± 0.7 | 21.5 | 25.5 | 19.89 ± 4.98 |
| mattcl-py | input-lanjian | 22.5 ± 0.6 | 21.7 | 25.8 | 20.08 ± 5.02 |
| pting | input-kcen | 22.6 ± 0.7 | 21.9 | 25.9 | 20.19 ± 5.05 |
| pting | input-lanjian | 22.7 ± 0.7 | 21.8 | 26.0 | 20.26 ± 5.07 |
| pting | input-pting | 23.0 ± 0.7 | 21.9 | 26.1 | 20.49 ± 5.13 |
| mattcl-py | input-pting | 23.0 ± 0.7 | 22.1 | 25.5 | 20.51 ± 5.14 |
| mattcl-py | input-kcen | 23.3 ± 4.3 | 21.5 | 61.6 | 20.81 ± 6.42 |
| kcen | input-mattcl | 28.2 ± 0.9 | 26.8 | 32.1 | 25.20 ± 6.31 |
| kcen | input-lanjian | 29.1 ± 0.8 | 28.0 | 32.3 | 25.99 ± 6.50 |
| kcen | input-kcen | 29.4 ± 1.6 | 27.9 | 43.5 | 26.26 ± 6.69 |
| kcen | input-pting | 29.7 ± 1.0 | 28.6 | 33.1 | 26.48 ± 6.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|