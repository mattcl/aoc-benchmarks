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
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 2.1 | 1.04 ± 0.30 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.05 ± 0.31 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.32 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.08 ± 0.32 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 2.1 | 1.09 ± 0.31 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.12 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.0 | 1.16 ± 0.33 |
| mattcl-ts | input-mattcl | 15.2 ± 0.3 | 14.2 | 16.2 | 12.75 ± 2.70 |
| mattcl-ts | input-pting | 15.4 ± 0.4 | 14.5 | 16.7 | 12.90 ± 2.74 |
| mattcl-ts | input-lanjian | 15.5 ± 3.2 | 14.3 | 59.1 | 13.03 ± 3.84 |
| mattcl-ts | input-kcen | 15.6 ± 2.4 | 14.5 | 39.5 | 13.07 ± 3.40 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.2 | 25.5 | 18.83 ± 4.01 |
| mattcl-py | input-mattcl | 22.4 ± 0.7 | 21.5 | 25.6 | 18.83 ± 4.01 |
| mattcl-py | input-lanjian | 23.0 ± 1.0 | 21.9 | 26.5 | 19.31 ± 4.15 |
| mattcl-py | input-kcen | 23.0 ± 1.1 | 21.7 | 30.5 | 19.35 ± 4.19 |
| pting | input-kcen | 23.1 ± 2.1 | 21.9 | 45.3 | 19.40 ± 4.46 |
| pting | input-lanjian | 23.1 ± 1.2 | 21.9 | 32.6 | 19.41 ± 4.21 |
| pting | input-pting | 23.4 ± 1.0 | 22.1 | 27.7 | 19.65 ± 4.23 |
| mattcl-py | input-pting | 23.4 ± 0.9 | 22.3 | 26.6 | 19.66 ± 4.21 |
| kcen | input-mattcl | 28.5 ± 1.0 | 27.3 | 31.7 | 23.92 ± 5.10 |
| kcen | input-kcen | 29.4 ± 1.0 | 28.3 | 37.5 | 24.67 ± 5.27 |
| kcen | input-lanjian | 29.4 ± 0.8 | 28.2 | 31.7 | 24.69 ± 5.25 |
| kcen | input-pting | 29.8 ± 1.0 | 28.6 | 33.0 | 24.99 ± 5.33 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|