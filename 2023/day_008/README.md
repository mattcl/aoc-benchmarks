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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.8 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.8 | 1.00 ± 0.29 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 2.1 | 1.04 ± 0.32 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.9 | 1.05 ± 0.33 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 2.3 | 1.05 ± 0.31 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.9 | 1.9 | 1.05 ± 0.31 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.9 | 1.9 | 1.09 ± 0.31 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.14 ± 0.34 |
| mattcl-ts | input-kcen | 14.7 ± 0.4 | 13.5 | 16.3 | 12.94 ± 2.83 |
| mattcl-ts | input-lanjian | 14.7 ± 0.4 | 13.9 | 15.9 | 12.95 ± 2.82 |
| mattcl-ts | input-pting | 14.8 ± 0.4 | 13.7 | 15.9 | 13.02 ± 2.84 |
| mattcl-ts | input-mattcl | 15.3 ± 0.5 | 14.0 | 17.5 | 13.47 ± 2.95 |
| mattcl-py | input-lanjian | 22.5 ± 0.6 | 21.7 | 25.3 | 19.78 ± 4.32 |
| pting | input-mattcl | 22.5 ± 0.8 | 21.2 | 25.7 | 19.79 ± 4.35 |
| mattcl-py | input-kcen | 22.5 ± 0.7 | 21.7 | 25.7 | 19.86 ± 4.35 |
| pting | input-kcen | 22.6 ± 0.8 | 21.9 | 25.9 | 19.93 ± 4.37 |
| mattcl-py | input-pting | 23.0 ± 0.8 | 21.9 | 26.2 | 20.23 ± 4.44 |
| pting | input-lanjian | 23.1 ± 0.8 | 21.9 | 25.3 | 20.37 ± 4.47 |
| mattcl-py | input-mattcl | 23.2 ± 0.6 | 21.8 | 25.5 | 20.41 ± 4.45 |
| pting | input-pting | 23.5 ± 4.5 | 21.8 | 72.6 | 20.70 ± 5.97 |
| kcen | input-kcen | 28.8 ± 0.9 | 27.7 | 31.6 | 25.38 ± 5.55 |
| kcen | input-lanjian | 28.8 ± 0.8 | 27.9 | 31.4 | 25.41 ± 5.56 |
| kcen | input-mattcl | 29.2 ± 0.7 | 27.7 | 31.1 | 25.71 ± 5.60 |
| kcen | input-pting | 29.5 ± 0.7 | 28.5 | 32.3 | 25.95 ± 5.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|