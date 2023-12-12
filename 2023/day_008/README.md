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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.9 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 2.0 | 1.04 ± 0.30 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.0 | 1.07 ± 0.31 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.08 ± 0.31 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.08 ± 0.32 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.08 ± 0.31 |
| lanjian | input-pting | 1.3 ± 0.3 | 1.0 | 2.1 | 1.14 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.2 | 1.0 | 2.2 | 1.19 ± 0.32 |
| mattcl-ts | input-mattcl | 15.2 ± 0.4 | 14.3 | 16.6 | 12.79 ± 2.60 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.6 | 16.5 | 12.90 ± 2.62 |
| mattcl-ts | input-kcen | 15.3 ± 0.3 | 14.5 | 16.4 | 12.90 ± 2.62 |
| mattcl-ts | input-pting | 15.4 ± 0.4 | 14.7 | 17.0 | 12.96 ± 2.64 |
| mattcl-py | input-mattcl | 22.4 ± 0.8 | 21.3 | 25.4 | 18.85 ± 3.86 |
| pting | input-mattcl | 22.5 ± 0.7 | 21.7 | 25.6 | 18.93 ± 3.87 |
| pting | input-lanjian | 22.8 ± 0.7 | 21.8 | 25.6 | 19.19 ± 3.92 |
| mattcl-py | input-lanjian | 22.8 ± 1.0 | 21.4 | 30.9 | 19.25 ± 3.97 |
| pting | input-kcen | 22.9 ± 0.8 | 21.9 | 26.5 | 19.30 ± 3.96 |
| mattcl-py | input-kcen | 23.0 ± 0.7 | 21.9 | 26.0 | 19.35 ± 3.96 |
| pting | input-pting | 23.1 ± 0.9 | 21.8 | 28.2 | 19.50 ± 4.00 |
| mattcl-py | input-pting | 23.2 ± 0.9 | 21.9 | 27.0 | 19.57 ± 4.02 |
| kcen | input-mattcl | 28.5 ± 0.9 | 26.8 | 31.3 | 24.03 ± 4.91 |
| kcen | input-lanjian | 29.2 ± 0.8 | 27.8 | 31.9 | 24.58 ± 5.01 |
| kcen | input-kcen | 29.5 ± 0.9 | 28.1 | 32.8 | 24.85 ± 5.07 |
| kcen | input-pting | 29.9 ± 0.9 | 28.7 | 33.2 | 25.16 ± 5.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|