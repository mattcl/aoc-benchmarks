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
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.8 | 1.04 ± 0.33 |
| mattcl | input-lanjian | 1.1 ± 0.3 | 0.8 | 1.8 | 1.06 ± 0.34 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.07 ± 0.34 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.9 | 1.07 ± 0.34 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.8 | 2.0 | 1.10 ± 0.34 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.8 | 1.11 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.9 | 1.9 | 1.17 ± 0.35 |
| mattcl-ts | input-mattcl | 14.4 ± 0.3 | 13.4 | 15.3 | 13.43 ± 3.11 |
| mattcl-ts | input-kcen | 14.6 ± 0.3 | 13.6 | 15.4 | 13.59 ± 3.15 |
| mattcl-ts | input-lanjian | 14.6 ± 0.4 | 13.6 | 15.7 | 13.62 ± 3.16 |
| mattcl-ts | input-pting | 14.7 ± 0.4 | 13.8 | 15.7 | 13.71 ± 3.18 |
| mattcl-py | input-mattcl | 21.9 ± 0.6 | 20.8 | 24.8 | 20.35 ± 4.73 |
| pting | input-mattcl | 21.9 ± 0.8 | 21.0 | 27.4 | 20.41 ± 4.77 |
| pting | input-kcen | 22.3 ± 0.7 | 21.3 | 25.5 | 20.75 ± 4.83 |
| mattcl-py | input-lanjian | 22.3 ± 0.6 | 21.1 | 25.2 | 20.76 ± 4.82 |
| mattcl-py | input-kcen | 22.4 ± 0.7 | 21.6 | 25.1 | 20.82 ± 4.84 |
| mattcl-py | input-pting | 22.5 ± 0.6 | 21.8 | 25.9 | 20.94 ± 4.86 |
| pting | input-lanjian | 22.5 ± 0.8 | 21.5 | 25.2 | 20.97 ± 4.90 |
| pting | input-pting | 22.7 ± 0.7 | 21.8 | 26.5 | 21.12 ± 4.92 |
| kcen | input-mattcl | 27.8 ± 0.9 | 26.7 | 31.2 | 25.89 ± 6.03 |
| kcen | input-kcen | 28.5 ± 0.6 | 27.6 | 30.6 | 26.52 ± 6.14 |
| kcen | input-lanjian | 28.7 ± 0.8 | 27.7 | 31.5 | 26.74 ± 6.21 |
| kcen | input-pting | 29.1 ± 0.8 | 27.6 | 31.7 | 27.12 ± 6.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|