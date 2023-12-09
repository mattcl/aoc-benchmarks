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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.9 | 2.0 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.03 ± 0.29 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.9 | 2.0 | 1.03 ± 0.28 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.06 ± 0.30 |
| mattcl | input-kcen | 1.3 ± 0.3 | 1.0 | 1.9 | 1.07 ± 0.30 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.0 | 2.2 | 1.11 ± 0.31 |
| lanjian | input-lanjian | 1.4 ± 0.3 | 1.0 | 2.1 | 1.11 ± 0.31 |
| lanjian | input-kcen | 1.4 ± 0.2 | 1.0 | 2.0 | 1.11 ± 0.29 |
| mattcl-ts | input-mattcl | 14.6 ± 0.4 | 13.7 | 15.7 | 11.85 ± 2.41 |
| mattcl-ts | input-kcen | 14.8 ± 0.4 | 14.0 | 15.8 | 12.00 ± 2.45 |
| mattcl-ts | input-lanjian | 14.9 ± 0.4 | 13.7 | 15.7 | 12.02 ± 2.45 |
| mattcl-ts | input-pting | 15.2 ± 3.0 | 13.7 | 56.2 | 12.30 ± 3.47 |
| mattcl-py | input-mattcl | 22.2 ± 0.7 | 21.1 | 25.3 | 17.96 ± 3.68 |
| pting | input-mattcl | 22.2 ± 0.6 | 21.3 | 25.5 | 17.99 ± 3.67 |
| mattcl-py | input-lanjian | 22.5 ± 0.6 | 21.8 | 25.5 | 18.24 ± 3.73 |
| pting | input-lanjian | 22.6 ± 0.7 | 21.8 | 25.4 | 18.31 ± 3.74 |
| pting | input-kcen | 22.6 ± 0.7 | 21.8 | 25.9 | 18.31 ± 3.75 |
| mattcl-py | input-kcen | 22.6 ± 0.8 | 21.6 | 25.7 | 18.32 ± 3.76 |
| pting | input-pting | 23.0 ± 0.7 | 22.1 | 26.3 | 18.60 ± 3.81 |
| mattcl-py | input-pting | 23.0 ± 0.9 | 21.8 | 26.1 | 18.64 ± 3.84 |
| kcen | input-mattcl | 28.1 ± 0.9 | 27.0 | 31.5 | 22.72 ± 4.65 |
| kcen | input-kcen | 28.8 ± 0.7 | 27.9 | 31.6 | 23.32 ± 4.75 |
| kcen | input-lanjian | 28.9 ± 0.9 | 27.7 | 31.4 | 23.40 ± 4.78 |
| kcen | input-pting | 29.6 ± 0.7 | 28.5 | 31.8 | 23.92 ± 4.87 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|