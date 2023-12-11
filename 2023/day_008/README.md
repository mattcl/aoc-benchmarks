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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.8 | 1.8 | 1.03 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.05 ± 0.32 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.9 | 1.06 ± 0.32 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.9 | 1.07 ± 0.33 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.7 | 1.07 ± 0.33 |
| lanjian | input-pting | 1.2 ± 0.3 | 0.8 | 2.0 | 1.13 ± 0.34 |
| lanjian | input-kcen | 1.2 ± 0.3 | 0.9 | 2.1 | 1.13 ± 0.34 |
| mattcl-ts | input-mattcl | 14.7 ± 0.4 | 13.7 | 15.7 | 13.39 ± 3.01 |
| mattcl-ts | input-kcen | 14.8 ± 0.4 | 13.7 | 15.8 | 13.47 ± 3.03 |
| mattcl-ts | input-lanjian | 14.8 ± 0.3 | 13.7 | 15.7 | 13.48 ± 3.03 |
| mattcl-ts | input-pting | 14.9 ± 0.3 | 13.9 | 15.7 | 13.55 ± 3.04 |
| pting | input-mattcl | 22.2 ± 0.6 | 21.4 | 24.9 | 20.23 ± 4.56 |
| mattcl-py | input-mattcl | 22.5 ± 3.9 | 20.9 | 66.5 | 20.46 ± 5.81 |
| mattcl-py | input-lanjian | 22.5 ± 0.8 | 21.4 | 26.0 | 20.51 ± 4.64 |
| mattcl-py | input-kcen | 22.6 ± 0.6 | 21.8 | 25.6 | 20.54 ± 4.62 |
| pting | input-lanjian | 22.7 ± 0.7 | 21.7 | 25.4 | 20.61 ± 4.65 |
| mattcl-py | input-pting | 22.8 ± 0.7 | 21.8 | 25.7 | 20.75 ± 4.68 |
| pting | input-kcen | 22.9 ± 1.1 | 21.7 | 28.7 | 20.80 ± 4.75 |
| pting | input-pting | 23.1 ± 0.9 | 22.1 | 26.2 | 21.01 ± 4.77 |
| kcen | input-mattcl | 28.1 ± 0.7 | 27.0 | 30.6 | 25.54 ± 5.75 |
| kcen | input-kcen | 29.0 ± 0.7 | 28.0 | 31.2 | 26.35 ± 5.92 |
| kcen | input-lanjian | 29.2 ± 0.8 | 27.9 | 32.2 | 26.57 ± 5.99 |
| kcen | input-pting | 29.5 ± 0.9 | 28.5 | 32.8 | 26.86 ± 6.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|