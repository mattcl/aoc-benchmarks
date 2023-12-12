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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.02 ± 0.30 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.9 | 1.06 ± 0.33 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 2.0 | 1.07 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.13 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.17 ± 0.35 |
| lanjian | input-lanjian | 1.4 ± 3.0 | 0.8 | 43.9 | 1.22 ± 2.69 |
| mattcl-ts | input-mattcl | 15.1 ± 0.3 | 14.3 | 16.2 | 13.35 ± 2.92 |
| mattcl-ts | input-kcen | 15.2 ± 0.3 | 14.3 | 16.5 | 13.44 ± 2.94 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.5 | 16.3 | 13.51 ± 2.96 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.6 | 16.5 | 13.53 ± 2.96 |
| pting | input-mattcl | 22.3 ± 0.7 | 21.2 | 25.2 | 19.73 ± 4.34 |
| mattcl-py | input-mattcl | 22.3 ± 0.8 | 21.4 | 25.9 | 19.76 ± 4.36 |
| mattcl-py | input-lanjian | 22.6 ± 0.7 | 21.3 | 25.4 | 20.00 ± 4.40 |
| mattcl-py | input-kcen | 22.8 ± 0.7 | 21.9 | 25.7 | 20.19 ± 4.44 |
| pting | input-lanjian | 22.9 ± 0.7 | 21.7 | 25.5 | 20.21 ± 4.44 |
| pting | input-kcen | 22.9 ± 0.7 | 21.9 | 25.3 | 20.22 ± 4.44 |
| mattcl-py | input-pting | 23.0 ± 0.9 | 21.8 | 26.2 | 20.36 ± 4.50 |
| pting | input-pting | 23.0 ± 0.8 | 21.6 | 25.9 | 20.38 ± 4.50 |
| kcen | input-mattcl | 28.3 ± 0.8 | 27.2 | 30.6 | 25.03 ± 5.49 |
| kcen | input-kcen | 29.3 ± 0.9 | 28.2 | 32.2 | 25.93 ± 5.69 |
| kcen | input-pting | 29.4 ± 0.8 | 28.5 | 32.9 | 26.02 ± 5.70 |
| kcen | input-lanjian | 30.2 ± 5.7 | 28.3 | 74.4 | 26.71 ± 7.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|