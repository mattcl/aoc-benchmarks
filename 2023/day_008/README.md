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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.9 | 1.8 | 1.03 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 2.0 | 1.07 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.9 | 1.9 | 1.07 ± 0.33 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 3.1 | 1.10 ± 0.35 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 1.9 | 1.11 ± 0.34 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 2.1 | 1.13 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.14 ± 0.34 |
| mattcl-ts | input-lanjian | 14.9 ± 0.4 | 13.9 | 16.4 | 12.83 ± 2.95 |
| mattcl-ts | input-kcen | 14.9 ± 0.3 | 13.9 | 15.9 | 12.85 ± 2.95 |
| mattcl-ts | input-mattcl | 14.9 ± 2.1 | 14.0 | 43.5 | 12.86 ± 3.43 |
| mattcl-ts | input-pting | 15.0 ± 0.3 | 13.8 | 16.1 | 12.90 ± 2.96 |
| mattcl-py | input-mattcl | 22.4 ± 0.9 | 20.9 | 25.1 | 19.25 ± 4.46 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.3 | 26.0 | 19.25 ± 4.44 |
| mattcl-py | input-kcen | 22.8 ± 0.8 | 21.5 | 26.0 | 19.57 ± 4.52 |
| mattcl-py | input-lanjian | 22.8 ± 0.8 | 21.3 | 25.7 | 19.59 ± 4.53 |
| pting | input-kcen | 22.8 ± 0.9 | 21.5 | 26.6 | 19.60 ± 4.54 |
| pting | input-lanjian | 22.8 ± 0.8 | 21.8 | 25.8 | 19.64 ± 4.54 |
| pting | input-pting | 23.1 ± 0.7 | 21.9 | 25.9 | 19.88 ± 4.59 |
| mattcl-py | input-pting | 23.2 ± 0.7 | 22.1 | 26.1 | 19.95 ± 4.60 |
| kcen | input-mattcl | 28.4 ± 0.9 | 27.2 | 30.8 | 24.41 ± 5.63 |
| kcen | input-kcen | 29.3 ± 0.8 | 28.0 | 32.2 | 25.17 ± 5.79 |
| kcen | input-lanjian | 29.4 ± 1.0 | 27.3 | 34.7 | 25.28 ± 5.83 |
| kcen | input-pting | 29.8 ± 0.8 | 28.6 | 32.5 | 25.66 ± 5.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|