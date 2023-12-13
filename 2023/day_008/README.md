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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 2.0 | 1.02 ± 0.28 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 2.1 | 1.04 ± 0.30 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.05 ± 0.30 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 1.9 | 1.09 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 2.1 | 1.10 ± 0.30 |
| lanjian | input-pting | 1.3 ± 0.2 | 1.0 | 2.0 | 1.11 ± 0.30 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.2 | 1.14 ± 0.31 |
| mattcl-ts | input-mattcl | 15.2 ± 0.4 | 14.4 | 18.0 | 12.64 ± 2.58 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 14.4 | 16.8 | 12.67 ± 2.58 |
| mattcl-ts | input-lanjian | 15.3 ± 0.3 | 14.6 | 16.4 | 12.68 ± 2.58 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.5 | 16.5 | 12.73 ± 2.59 |
| mattcl-py | input-mattcl | 22.4 ± 0.8 | 21.1 | 25.7 | 18.65 ± 3.82 |
| pting | input-mattcl | 22.6 ± 0.8 | 21.7 | 25.9 | 18.74 ± 3.84 |
| mattcl-py | input-lanjian | 22.8 ± 0.7 | 21.9 | 26.4 | 18.94 ± 3.87 |
| pting | input-lanjian | 22.8 ± 0.7 | 21.6 | 25.6 | 18.95 ± 3.87 |
| pting | input-kcen | 23.0 ± 0.8 | 21.8 | 25.9 | 19.07 ± 3.91 |
| mattcl-py | input-kcen | 23.0 ± 0.8 | 22.0 | 25.8 | 19.11 ± 3.91 |
| mattcl-py | input-pting | 23.2 ± 0.6 | 22.1 | 26.2 | 19.28 ± 3.93 |
| pting | input-pting | 23.3 ± 0.8 | 22.1 | 26.5 | 19.34 ± 3.96 |
| kcen | input-mattcl | 28.2 ± 0.7 | 27.1 | 31.5 | 23.46 ± 4.78 |
| kcen | input-lanjian | 29.1 ± 0.8 | 27.8 | 31.5 | 24.19 ± 4.94 |
| kcen | input-kcen | 29.5 ± 1.0 | 28.3 | 36.8 | 24.49 ± 5.02 |
| kcen | input-pting | 29.7 ± 0.9 | 28.2 | 32.5 | 24.67 ± 5.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|