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
| mattcl | input-mattcl | 1.1 ± 0.3 | 0.8 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.33 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 1.9 | 1.07 ± 0.33 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.07 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.9 | 1.9 | 1.08 ± 0.33 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.4 | 1.13 ± 0.35 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.13 ± 0.34 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 2.1 | 1.14 ± 0.32 |
| mattcl-ts | input-mattcl | 15.1 ± 0.3 | 14.3 | 16.1 | 13.29 ± 2.99 |
| mattcl-ts | input-lanjian | 15.2 ± 0.3 | 14.5 | 16.3 | 13.41 ± 3.02 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 14.3 | 17.0 | 13.43 ± 3.02 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.6 | 16.4 | 13.51 ± 3.04 |
| mattcl-py | input-mattcl | 22.4 ± 0.8 | 21.5 | 25.6 | 19.72 ± 4.47 |
| pting | input-mattcl | 22.4 ± 0.8 | 21.4 | 25.3 | 19.72 ± 4.47 |
| pting | input-kcen | 22.8 ± 0.7 | 21.7 | 25.8 | 20.08 ± 4.54 |
| mattcl-py | input-lanjian | 22.8 ± 0.8 | 21.8 | 25.8 | 20.10 ± 4.55 |
| pting | input-lanjian | 23.1 ± 0.9 | 21.7 | 26.9 | 20.30 ± 4.61 |
| mattcl-py | input-kcen | 23.1 ± 0.9 | 21.9 | 27.2 | 20.31 ± 4.61 |
| pting | input-pting | 23.2 ± 0.8 | 22.2 | 27.0 | 20.40 ± 4.62 |
| mattcl-py | input-pting | 23.3 ± 0.8 | 22.2 | 26.0 | 20.53 ± 4.65 |
| kcen | input-mattcl | 28.3 ± 0.8 | 27.4 | 31.5 | 24.94 ± 5.63 |
| kcen | input-lanjian | 29.3 ± 0.7 | 28.0 | 31.4 | 25.76 ± 5.80 |
| kcen | input-kcen | 29.5 ± 0.9 | 28.1 | 32.8 | 25.91 ± 5.86 |
| kcen | input-pting | 29.8 ± 0.9 | 28.6 | 32.6 | 26.18 ± 5.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|