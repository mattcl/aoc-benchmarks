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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.9 | 2.0 | 1.07 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.07 ± 0.32 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.9 | 1.9 | 1.08 ± 0.30 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 1.9 | 1.11 ± 0.34 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.11 ± 0.33 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.9 | 2.0 | 1.12 ± 0.31 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.22 ± 0.36 |
| mattcl-ts | input-mattcl | 14.3 ± 0.3 | 13.6 | 15.3 | 12.92 ± 2.73 |
| mattcl-ts | input-lanjian | 14.5 ± 0.4 | 13.5 | 15.9 | 13.07 ± 2.77 |
| mattcl-ts | input-kcen | 14.5 ± 0.4 | 13.5 | 16.4 | 13.10 ± 2.78 |
| mattcl-ts | input-pting | 14.6 ± 0.4 | 13.7 | 15.5 | 13.21 ± 2.79 |
| mattcl-py | input-mattcl | 22.2 ± 0.9 | 21.3 | 25.7 | 20.06 ± 4.29 |
| pting | input-mattcl | 22.3 ± 0.7 | 21.4 | 25.3 | 20.10 ± 4.27 |
| mattcl-py | input-lanjian | 22.5 ± 0.7 | 21.8 | 25.8 | 20.32 ± 4.32 |
| pting | input-kcen | 22.6 ± 0.7 | 21.8 | 25.5 | 20.38 ± 4.32 |
| pting | input-lanjian | 22.7 ± 0.7 | 21.8 | 26.4 | 20.46 ± 4.35 |
| mattcl-py | input-kcen | 22.7 ± 0.8 | 21.5 | 25.7 | 20.52 ± 4.37 |
| mattcl-py | input-pting | 22.9 ± 0.7 | 22.0 | 25.6 | 20.65 ± 4.38 |
| pting | input-pting | 22.9 ± 0.7 | 21.7 | 25.6 | 20.66 ± 4.39 |
| kcen | input-mattcl | 28.3 ± 1.1 | 26.9 | 33.3 | 25.57 ± 5.46 |
| kcen | input-lanjian | 29.0 ± 0.8 | 28.0 | 31.6 | 26.17 ± 5.54 |
| kcen | input-kcen | 29.3 ± 1.1 | 28.0 | 33.1 | 26.41 ± 5.63 |
| kcen | input-pting | 29.5 ± 0.8 | 28.3 | 32.8 | 26.63 ± 5.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|