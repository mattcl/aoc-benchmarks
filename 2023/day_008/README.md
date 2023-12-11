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
| mattcl | input-mattcl | 1.1 ± 0.3 | 0.7 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.8 | 1.9 | 1.01 ± 0.32 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.8 | 2.0 | 1.06 ± 0.34 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.8 | 1.07 ± 0.35 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.9 | 1.08 ± 0.34 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.0 | 1.08 ± 0.34 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.16 ± 0.37 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.8 | 2.0 | 1.16 ± 0.38 |
| mattcl-ts | input-mattcl | 14.7 ± 0.3 | 13.8 | 15.5 | 13.49 ± 3.13 |
| mattcl-ts | input-lanjian | 14.8 ± 0.3 | 13.8 | 15.7 | 13.58 ± 3.15 |
| mattcl-ts | input-kcen | 14.9 ± 0.3 | 13.8 | 16.0 | 13.62 ± 3.16 |
| mattcl-ts | input-pting | 14.9 ± 0.3 | 14.0 | 15.8 | 13.66 ± 3.17 |
| pting | input-mattcl | 22.1 ± 0.6 | 21.1 | 24.7 | 20.31 ± 4.72 |
| mattcl-py | input-mattcl | 22.2 ± 0.8 | 21.1 | 25.0 | 20.33 ± 4.75 |
| mattcl-py | input-lanjian | 22.6 ± 0.8 | 21.8 | 25.9 | 20.71 ± 4.84 |
| pting | input-lanjian | 22.6 ± 0.6 | 21.7 | 25.6 | 20.71 ± 4.82 |
| pting | input-kcen | 22.6 ± 0.7 | 21.6 | 25.7 | 20.74 ± 4.83 |
| mattcl-py | input-kcen | 22.7 ± 0.9 | 21.7 | 25.7 | 20.84 ± 4.88 |
| mattcl-py | input-pting | 22.9 ± 0.9 | 21.7 | 28.3 | 20.99 ± 4.91 |
| pting | input-pting | 23.4 ± 3.2 | 21.8 | 53.7 | 21.50 ± 5.74 |
| kcen | input-mattcl | 28.1 ± 1.0 | 26.9 | 35.0 | 25.80 ± 6.03 |
| kcen | input-kcen | 29.0 ± 0.7 | 27.9 | 31.9 | 26.61 ± 6.18 |
| kcen | input-lanjian | 29.1 ± 0.8 | 27.9 | 31.6 | 26.65 ± 6.20 |
| kcen | input-pting | 29.5 ± 1.0 | 28.4 | 32.6 | 27.08 ± 6.31 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|