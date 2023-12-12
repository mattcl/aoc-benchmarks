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
| mattcl | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.0 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 1.0 | 2.0 | 1.03 ± 0.28 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 1.0 | 2.1 | 1.04 ± 0.29 |
| mattcl | input-pting | 1.3 ± 0.2 | 1.0 | 2.1 | 1.04 ± 0.29 |
| mattcl | input-kcen | 1.4 ± 0.3 | 1.0 | 2.0 | 1.10 ± 0.31 |
| lanjian | input-kcen | 1.4 ± 0.2 | 1.0 | 2.0 | 1.12 ± 0.30 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.0 | 2.2 | 1.13 ± 0.30 |
| lanjian | input-lanjian | 1.6 ± 3.6 | 1.0 | 51.7 | 1.28 ± 2.84 |
| mattcl-ts | input-mattcl | 15.3 ± 0.4 | 14.4 | 17.0 | 12.15 ± 2.49 |
| mattcl-ts | input-kcen | 15.3 ± 0.3 | 14.4 | 16.7 | 12.16 ± 2.48 |
| mattcl-ts | input-pting | 15.4 ± 0.3 | 14.7 | 16.4 | 12.22 ± 2.49 |
| mattcl-ts | input-lanjian | 15.7 ± 3.8 | 14.7 | 56.4 | 12.47 ± 3.93 |
| mattcl-py | input-mattcl | 22.3 ± 0.5 | 21.2 | 24.8 | 17.70 ± 3.62 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.3 | 25.4 | 17.80 ± 3.65 |
| pting | input-kcen | 22.7 ± 0.5 | 21.7 | 25.3 | 18.01 ± 3.68 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.9 | 26.6 | 18.18 ± 3.74 |
| mattcl-py | input-kcen | 23.0 ± 0.7 | 22.0 | 26.2 | 18.22 ± 3.74 |
| pting | input-pting | 23.1 ± 0.7 | 21.8 | 26.0 | 18.34 ± 3.76 |
| mattcl-py | input-pting | 23.1 ± 0.8 | 22.2 | 26.3 | 18.36 ± 3.78 |
| mattcl-py | input-lanjian | 23.4 ± 3.9 | 21.4 | 65.6 | 18.58 ± 4.87 |
| kcen | input-mattcl | 28.6 ± 1.0 | 26.9 | 31.8 | 22.67 ± 4.67 |
| kcen | input-lanjian | 29.2 ± 0.8 | 27.9 | 32.4 | 23.13 ± 4.74 |
| kcen | input-kcen | 29.6 ± 0.9 | 28.2 | 32.5 | 23.44 ± 4.81 |
| kcen | input-pting | 29.8 ± 0.8 | 28.5 | 32.6 | 23.66 ± 4.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|