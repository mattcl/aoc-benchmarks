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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.8 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 4.3 | 1.12 ± 0.39 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 2.0 | 1.14 ± 0.35 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.9 | 1.9 | 1.16 ± 0.34 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.9 | 1.9 | 1.18 ± 0.34 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 2.7 | 1.18 ± 0.35 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 2.0 | 1.21 ± 0.34 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.2 | 1.31 ± 0.38 |
| mattcl-ts | input-lanjian | 14.6 ± 0.5 | 13.5 | 17.5 | 13.81 ± 2.95 |
| mattcl-ts | input-pting | 14.9 ± 0.4 | 13.9 | 16.1 | 14.09 ± 3.00 |
| mattcl-ts | input-kcen | 15.0 ± 1.1 | 13.6 | 24.6 | 14.16 ± 3.16 |
| mattcl-ts | input-mattcl | 15.0 ± 3.9 | 13.7 | 69.6 | 14.17 ± 4.76 |
| pting | input-mattcl | 22.2 ± 0.7 | 21.3 | 25.2 | 21.03 ± 4.49 |
| mattcl-py | input-mattcl | 22.4 ± 0.8 | 21.1 | 25.7 | 21.16 ± 4.53 |
| mattcl-py | input-lanjian | 22.7 ± 0.7 | 21.5 | 26.2 | 21.46 ± 4.57 |
| pting | input-lanjian | 22.7 ± 0.7 | 21.7 | 26.1 | 21.48 ± 4.57 |
| mattcl-py | input-kcen | 23.6 ± 0.5 | 22.8 | 26.1 | 22.37 ± 4.74 |
| pting | input-pting | 23.8 ± 0.5 | 22.7 | 26.6 | 22.55 ± 4.78 |
| mattcl-py | input-pting | 23.9 ± 0.5 | 22.9 | 26.2 | 22.64 ± 4.80 |
| pting | input-kcen | 24.1 ± 1.6 | 22.0 | 32.4 | 22.83 ± 5.04 |
| kcen | input-mattcl | 28.2 ± 0.9 | 26.9 | 31.2 | 26.66 ± 5.68 |
| kcen | input-lanjian | 29.3 ± 0.7 | 27.8 | 32.1 | 27.69 ± 5.88 |
| kcen | input-pting | 29.5 ± 1.1 | 28.2 | 38.7 | 27.93 ± 5.98 |
| kcen | input-kcen | 29.8 ± 0.8 | 28.3 | 32.3 | 28.16 ± 5.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|