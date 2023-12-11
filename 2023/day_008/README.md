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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.9 | 1.9 | 1.05 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.9 | 2.0 | 1.06 ± 0.33 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 2.1 | 1.07 ± 0.32 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.08 ± 0.34 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.10 ± 0.34 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.13 ± 0.34 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.2 | 1.18 ± 0.35 |
| mattcl-ts | input-mattcl | 15.2 ± 0.4 | 14.2 | 16.8 | 13.02 ± 2.89 |
| mattcl-ts | input-lanjian | 15.2 ± 0.3 | 14.3 | 16.1 | 13.08 ± 2.90 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 13.9 | 17.0 | 13.09 ± 2.91 |
| mattcl-ts | input-pting | 15.4 ± 0.4 | 14.7 | 17.0 | 13.17 ± 2.92 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.4 | 25.6 | 19.24 ± 4.29 |
| mattcl-py | input-mattcl | 22.4 ± 0.9 | 21.1 | 28.1 | 19.25 ± 4.31 |
| pting | input-lanjian | 22.9 ± 0.7 | 21.6 | 25.8 | 19.63 ± 4.37 |
| mattcl-py | input-kcen | 22.9 ± 0.7 | 21.6 | 25.3 | 19.64 ± 4.37 |
| pting | input-kcen | 22.9 ± 0.8 | 21.7 | 26.2 | 19.66 ± 4.39 |
| mattcl-py | input-lanjian | 22.9 ± 0.9 | 21.5 | 27.2 | 19.67 ± 4.41 |
| mattcl-py | input-pting | 22.9 ± 0.6 | 21.8 | 26.4 | 19.69 ± 4.37 |
| pting | input-pting | 23.2 ± 0.7 | 22.2 | 26.3 | 19.94 ± 4.44 |
| kcen | input-mattcl | 28.5 ± 1.0 | 27.2 | 31.3 | 24.47 ± 5.46 |
| kcen | input-lanjian | 29.1 ± 0.8 | 27.8 | 32.4 | 24.98 ± 5.55 |
| kcen | input-kcen | 29.5 ± 0.9 | 27.7 | 32.6 | 25.33 ± 5.64 |
| kcen | input-pting | 29.7 ± 0.8 | 28.5 | 32.4 | 25.50 ± 5.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|