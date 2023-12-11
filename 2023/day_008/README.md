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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.9 | 1.9 | 1.03 ± 0.29 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.9 | 2.0 | 1.03 ± 0.30 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.0 | 1.05 ± 0.30 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 1.9 | 1.05 ± 0.28 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.06 ± 0.31 |
| lanjian | input-pting | 1.4 ± 0.3 | 0.9 | 2.2 | 1.13 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.2 | 1.0 | 2.2 | 1.14 ± 0.31 |
| mattcl-ts | input-mattcl | 15.1 ± 0.3 | 14.3 | 16.2 | 12.39 ± 2.60 |
| mattcl-ts | input-pting | 15.2 ± 0.3 | 14.2 | 16.1 | 12.48 ± 2.62 |
| mattcl-ts | input-lanjian | 15.6 ± 4.9 | 14.4 | 69.2 | 12.84 ± 4.82 |
| mattcl-ts | input-kcen | 15.7 ± 7.7 | 14.3 | 120.0 | 12.90 ± 6.84 |
| mattcl-py | input-mattcl | 22.3 ± 0.6 | 21.5 | 24.9 | 18.35 ± 3.85 |
| pting | input-mattcl | 22.5 ± 0.7 | 21.4 | 25.4 | 18.52 ± 3.91 |
| mattcl-py | input-kcen | 22.6 ± 0.6 | 21.8 | 25.3 | 18.57 ± 3.90 |
| pting | input-kcen | 22.7 ± 0.7 | 21.9 | 25.8 | 18.67 ± 3.93 |
| pting | input-lanjian | 22.7 ± 0.6 | 21.8 | 25.5 | 18.67 ± 3.92 |
| mattcl-py | input-lanjian | 22.8 ± 0.9 | 21.7 | 25.9 | 18.71 ± 3.96 |
| mattcl-py | input-pting | 23.0 ± 0.6 | 22.2 | 26.1 | 18.88 ± 3.97 |
| pting | input-pting | 23.1 ± 0.8 | 22.2 | 25.8 | 19.02 ± 4.02 |
| kcen | input-mattcl | 28.2 ± 1.3 | 27.1 | 38.4 | 23.22 ± 4.95 |
| kcen | input-lanjian | 28.8 ± 0.7 | 27.7 | 31.8 | 23.71 ± 4.98 |
| kcen | input-kcen | 29.1 ± 0.7 | 28.1 | 31.7 | 23.90 ± 5.02 |
| kcen | input-pting | 29.6 ± 0.9 | 28.6 | 32.8 | 24.37 ± 5.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|