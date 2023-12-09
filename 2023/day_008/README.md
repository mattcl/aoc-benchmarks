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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.32 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.9 | 1.05 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.8 | 1.8 | 1.06 ± 0.33 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.9 | 1.07 ± 0.35 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.8 | 2.0 | 1.10 ± 0.34 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 1.9 | 1.15 ± 0.35 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.15 ± 0.36 |
| mattcl-ts | input-mattcl | 14.7 ± 0.4 | 13.7 | 15.8 | 13.45 ± 3.11 |
| mattcl-ts | input-lanjian | 14.7 ± 0.4 | 13.7 | 16.1 | 13.50 ± 3.12 |
| mattcl-ts | input-kcen | 14.8 ± 0.3 | 14.0 | 15.5 | 13.55 ± 3.13 |
| mattcl-ts | input-pting | 15.1 ± 3.9 | 13.8 | 69.5 | 13.86 ± 4.81 |
| mattcl-py | input-mattcl | 22.2 ± 0.8 | 20.9 | 25.1 | 20.38 ± 4.74 |
| pting | input-mattcl | 22.3 ± 0.9 | 21.1 | 26.8 | 20.43 ± 4.76 |
| pting | input-kcen | 22.5 ± 0.8 | 21.6 | 26.1 | 20.64 ± 4.80 |
| mattcl-py | input-kcen | 22.6 ± 0.6 | 21.5 | 25.0 | 20.68 ± 4.78 |
| mattcl-py | input-lanjian | 22.6 ± 0.8 | 21.3 | 26.2 | 20.71 ± 4.81 |
| pting | input-lanjian | 22.8 ± 0.9 | 21.3 | 26.0 | 20.92 ± 4.88 |
| pting | input-pting | 22.9 ± 0.7 | 22.0 | 26.0 | 20.94 ± 4.86 |
| mattcl-py | input-pting | 22.9 ± 0.7 | 21.7 | 25.7 | 21.02 ± 4.87 |
| kcen | input-mattcl | 28.2 ± 0.9 | 26.9 | 30.7 | 25.87 ± 6.00 |
| kcen | input-lanjian | 28.9 ± 0.8 | 27.6 | 31.4 | 26.44 ± 6.12 |
| kcen | input-kcen | 29.1 ± 1.0 | 27.5 | 32.4 | 26.66 ± 6.19 |
| kcen | input-pting | 29.5 ± 0.9 | 28.0 | 32.2 | 27.06 ± 6.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|