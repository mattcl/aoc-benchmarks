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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 2.1 | 1.07 ± 0.33 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.9 | 1.07 ± 0.33 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.8 | 1.07 ± 0.33 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.08 ± 0.34 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.8 | 2.0 | 1.09 ± 0.31 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.14 ± 0.35 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.15 ± 0.35 |
| mattcl-ts | input-mattcl | 14.9 ± 0.4 | 13.9 | 16.5 | 13.39 ± 2.92 |
| mattcl-ts | input-kcen | 14.9 ± 0.3 | 13.9 | 15.7 | 13.45 ± 2.93 |
| mattcl-ts | input-pting | 15.0 ± 0.3 | 14.2 | 16.1 | 13.49 ± 2.94 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.2 | 16.2 | 13.49 ± 2.93 |
| mattcl-py | input-mattcl | 22.3 ± 0.6 | 21.2 | 26.1 | 20.04 ± 4.38 |
| pting | input-mattcl | 22.5 ± 0.8 | 21.4 | 26.0 | 20.24 ± 4.45 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.4 | 25.7 | 20.63 ± 4.53 |
| pting | input-kcen | 23.0 ± 1.1 | 21.5 | 31.6 | 20.67 ± 4.60 |
| mattcl-py | input-kcen | 23.1 ± 0.8 | 22.1 | 25.9 | 20.76 ± 4.56 |
| mattcl-py | input-lanjian | 23.1 ± 1.0 | 21.4 | 26.4 | 20.77 ± 4.59 |
| pting | input-pting | 23.1 ± 0.7 | 21.7 | 25.9 | 20.82 ± 4.56 |
| mattcl-py | input-pting | 23.2 ± 0.8 | 22.2 | 26.3 | 20.86 ± 4.57 |
| kcen | input-mattcl | 28.5 ± 2.6 | 26.6 | 54.0 | 25.60 ± 6.04 |
| kcen | input-kcen | 29.5 ± 1.0 | 28.0 | 33.3 | 26.51 ± 5.81 |
| kcen | input-pting | 29.9 ± 1.1 | 28.4 | 32.7 | 26.93 ± 5.92 |
| kcen | input-lanjian | 30.2 ± 5.5 | 27.7 | 68.5 | 27.17 ± 7.68 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|