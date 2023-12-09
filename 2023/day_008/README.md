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
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.8 | 1.05 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.8 | 1.05 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.07 ± 0.33 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.9 | 1.08 ± 0.32 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.9 | 2.1 | 1.09 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 2.0 | 1.12 ± 0.32 |
| lanjian | input-kcen | 1.5 ± 2.7 | 0.9 | 39.9 | 1.31 ± 2.48 |
| mattcl-ts | input-mattcl | 14.5 ± 0.3 | 13.5 | 15.3 | 13.04 ± 2.77 |
| mattcl-ts | input-lanjian | 14.7 ± 0.3 | 13.8 | 15.5 | 13.20 ± 2.81 |
| mattcl-ts | input-kcen | 14.8 ± 0.3 | 13.6 | 15.5 | 13.27 ± 2.82 |
| mattcl-ts | input-pting | 14.8 ± 0.3 | 13.9 | 15.7 | 13.33 ± 2.83 |
| mattcl-py | input-mattcl | 21.9 ± 0.7 | 21.2 | 25.7 | 19.71 ± 4.21 |
| pting | input-mattcl | 22.0 ± 0.7 | 21.0 | 24.6 | 19.74 ± 4.22 |
| pting | input-kcen | 22.4 ± 0.8 | 21.5 | 25.8 | 20.10 ± 4.30 |
| mattcl-py | input-kcen | 22.4 ± 0.7 | 21.5 | 25.6 | 20.11 ± 4.30 |
| mattcl-py | input-lanjian | 22.4 ± 0.8 | 21.4 | 25.5 | 20.14 ± 4.32 |
| pting | input-lanjian | 22.5 ± 0.8 | 21.6 | 26.6 | 20.23 ± 4.34 |
| pting | input-pting | 22.6 ± 0.7 | 21.8 | 25.3 | 20.34 ± 4.35 |
| mattcl-py | input-pting | 22.6 ± 0.7 | 21.8 | 25.6 | 20.34 ± 4.35 |
| kcen | input-mattcl | 27.9 ± 0.8 | 27.0 | 30.8 | 25.09 ± 5.35 |
| kcen | input-kcen | 28.8 ± 0.9 | 27.6 | 34.0 | 25.86 ± 5.53 |
| kcen | input-lanjian | 28.9 ± 2.7 | 27.5 | 54.7 | 25.98 ± 5.99 |
| kcen | input-pting | 29.2 ± 0.7 | 28.1 | 31.8 | 26.21 ± 5.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|