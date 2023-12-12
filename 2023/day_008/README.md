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
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 1.9 | 1.04 ± 0.33 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.9 | 1.06 ± 0.34 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.34 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 2.0 | 1.07 ± 0.34 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.9 | 2.1 | 1.09 ± 0.35 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 1.9 | 1.10 ± 0.34 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.16 ± 0.36 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.3 | 16.6 | 13.19 ± 3.15 |
| mattcl-ts | input-kcen | 15.2 ± 0.3 | 14.5 | 16.2 | 13.30 ± 3.17 |
| mattcl-ts | input-lanjian | 15.3 ± 0.3 | 14.5 | 16.8 | 13.31 ± 3.18 |
| mattcl-ts | input-pting | 15.6 ± 4.3 | 14.5 | 73.9 | 13.63 ± 4.98 |
| pting | input-mattcl | 22.4 ± 0.8 | 21.4 | 25.7 | 19.54 ± 4.70 |
| mattcl-py | input-mattcl | 22.5 ± 0.8 | 21.4 | 26.1 | 19.60 ± 4.71 |
| mattcl-py | input-kcen | 22.8 ± 1.0 | 21.6 | 30.7 | 19.93 ± 4.81 |
| pting | input-lanjian | 22.9 ± 0.9 | 21.5 | 26.1 | 19.96 ± 4.81 |
| pting | input-kcen | 23.0 ± 0.9 | 21.8 | 26.1 | 20.02 ± 4.82 |
| mattcl-py | input-lanjian | 23.0 ± 1.0 | 21.4 | 26.4 | 20.04 ± 4.85 |
| mattcl-py | input-pting | 23.1 ± 1.0 | 22.1 | 31.7 | 20.12 ± 4.87 |
| pting | input-pting | 23.4 ± 3.8 | 22.1 | 65.4 | 20.40 ± 5.86 |
| kcen | input-mattcl | 28.4 ± 0.9 | 27.1 | 31.3 | 24.80 ± 5.95 |
| kcen | input-kcen | 29.1 ± 0.8 | 27.9 | 31.9 | 25.41 ± 6.09 |
| kcen | input-lanjian | 29.7 ± 4.0 | 28.0 | 68.4 | 25.88 ± 7.05 |
| kcen | input-pting | 29.7 ± 0.9 | 28.4 | 32.6 | 25.91 ± 6.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|