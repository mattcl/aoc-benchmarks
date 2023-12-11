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
| mattcl | input-mattcl | 1.1 ± 0.3 | 0.8 | 1.9 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 2.0 | 1.02 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.8 | 1.8 | 1.03 ± 0.32 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.8 | 1.05 ± 0.33 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 2.0 | 1.06 ± 0.34 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.9 | 2.0 | 1.09 ± 0.34 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.12 ± 0.34 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.17 ± 0.36 |
| mattcl-ts | input-mattcl | 15.1 ± 0.3 | 14.2 | 16.1 | 13.30 ± 3.04 |
| mattcl-ts | input-pting | 15.2 ± 0.4 | 14.5 | 16.6 | 13.39 ± 3.07 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 14.4 | 16.8 | 13.41 ± 3.07 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.1 | 17.1 | 13.41 ± 3.07 |
| pting | input-mattcl | 22.4 ± 0.8 | 21.4 | 26.1 | 19.70 ± 4.54 |
| mattcl-py | input-mattcl | 22.6 ± 2.9 | 20.9 | 53.9 | 19.85 ± 5.18 |
| mattcl-py | input-lanjian | 22.7 ± 0.7 | 21.3 | 25.5 | 19.98 ± 4.59 |
| mattcl-py | input-kcen | 22.7 ± 0.6 | 21.9 | 26.4 | 19.99 ± 4.58 |
| pting | input-kcen | 22.8 ± 0.6 | 21.9 | 25.0 | 20.03 ± 4.58 |
| pting | input-lanjian | 23.1 ± 1.1 | 21.5 | 26.6 | 20.28 ± 4.71 |
| mattcl-py | input-pting | 23.1 ± 0.7 | 21.9 | 26.1 | 20.28 ± 4.65 |
| pting | input-pting | 23.2 ± 0.8 | 22.2 | 26.0 | 20.44 ± 4.70 |
| kcen | input-mattcl | 28.4 ± 1.4 | 26.8 | 39.4 | 24.92 ± 5.80 |
| kcen | input-kcen | 29.5 ± 0.9 | 28.0 | 32.9 | 25.89 ± 5.94 |
| kcen | input-pting | 29.6 ± 0.6 | 28.5 | 32.1 | 25.99 ± 5.94 |
| kcen | input-lanjian | 29.6 ± 2.5 | 27.8 | 53.3 | 26.02 ± 6.31 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|