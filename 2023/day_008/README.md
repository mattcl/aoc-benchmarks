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
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.9 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.9 | 1.03 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.9 | 2.0 | 1.04 ± 0.32 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 1.9 | 1.05 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.06 ± 0.32 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.08 ± 0.33 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.1 | 1.15 ± 0.34 |
| mattcl | input-mattcl | 1.4 ± 3.6 | 0.8 | 51.3 | 1.17 ± 2.98 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 13.9 | 16.5 | 12.48 ± 2.81 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.1 | 16.0 | 12.56 ± 2.82 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.1 | 16.0 | 12.57 ± 2.83 |
| mattcl-ts | input-kcen | 15.4 ± 3.6 | 14.2 | 61.0 | 12.81 ± 4.13 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.4 | 25.7 | 18.69 ± 4.23 |
| mattcl-py | input-mattcl | 22.5 ± 0.7 | 21.6 | 25.7 | 18.81 ± 4.25 |
| mattcl-py | input-lanjian | 22.9 ± 0.9 | 21.7 | 26.5 | 19.09 ± 4.33 |
| pting | input-kcen | 22.9 ± 0.8 | 22.0 | 26.0 | 19.09 ± 4.32 |
| pting | input-lanjian | 23.0 ± 0.9 | 21.9 | 26.3 | 19.15 ± 4.35 |
| mattcl-py | input-kcen | 23.1 ± 2.0 | 22.0 | 43.3 | 19.24 ± 4.61 |
| mattcl-py | input-pting | 23.2 ± 0.8 | 22.0 | 27.0 | 19.33 ± 4.38 |
| pting | input-pting | 23.3 ± 0.9 | 22.1 | 26.2 | 19.40 ± 4.41 |
| kcen | input-mattcl | 28.2 ± 0.8 | 27.1 | 31.4 | 23.56 ± 5.32 |
| kcen | input-lanjian | 29.2 ± 0.8 | 28.0 | 32.0 | 24.39 ± 5.50 |
| kcen | input-kcen | 29.4 ± 0.9 | 28.1 | 32.7 | 24.48 ± 5.53 |
| kcen | input-pting | 29.8 ± 1.0 | 28.6 | 32.9 | 24.86 ± 5.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|