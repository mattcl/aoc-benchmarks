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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.9 | 2.0 | 1.00 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.0 | 1.02 ± 0.29 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.9 | 2.0 | 1.03 ± 0.29 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.05 ± 0.30 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.06 ± 0.30 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.0 | 2.2 | 1.09 ± 0.30 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.3 | 1.12 ± 0.32 |
| mattcl | input-mattcl | 1.4 ± 3.6 | 0.8 | 52.6 | 1.15 ± 2.94 |
| mattcl-ts | input-mattcl | 15.2 ± 0.3 | 14.4 | 16.1 | 12.21 ± 2.46 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 14.3 | 16.7 | 12.34 ± 2.49 |
| mattcl-ts | input-pting | 15.4 ± 0.4 | 14.6 | 16.7 | 12.38 ± 2.50 |
| mattcl-ts | input-lanjian | 15.4 ± 1.5 | 14.6 | 35.8 | 12.42 ± 2.77 |
| mattcl-py | input-mattcl | 22.4 ± 1.7 | 21.4 | 40.1 | 18.00 ± 3.84 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.5 | 25.2 | 18.06 ± 3.66 |
| pting | input-lanjian | 22.8 ± 0.7 | 21.9 | 25.9 | 18.36 ± 3.71 |
| mattcl-py | input-lanjian | 22.8 ± 0.9 | 21.9 | 28.9 | 18.37 ± 3.74 |
| mattcl-py | input-kcen | 22.9 ± 0.9 | 21.8 | 26.6 | 18.39 ± 3.75 |
| pting | input-kcen | 22.9 ± 1.0 | 21.8 | 27.1 | 18.39 ± 3.76 |
| mattcl-py | input-pting | 23.2 ± 0.7 | 22.2 | 26.0 | 18.63 ± 3.77 |
| pting | input-pting | 23.3 ± 1.3 | 21.9 | 34.2 | 18.75 ± 3.89 |
| kcen | input-mattcl | 29.0 ± 4.0 | 27.2 | 61.4 | 23.32 ± 5.64 |
| kcen | input-lanjian | 29.2 ± 0.9 | 27.7 | 32.7 | 23.52 ± 4.76 |
| kcen | input-kcen | 29.2 ± 0.7 | 28.1 | 31.7 | 23.52 ± 4.74 |
| kcen | input-pting | 29.7 ± 0.9 | 28.4 | 33.1 | 23.90 ± 4.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|