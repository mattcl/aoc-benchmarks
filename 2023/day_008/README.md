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
| mattcl | input-mattcl | 1.0 ± 0.3 | 0.7 | 1.7 | 1.00 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.02 ± 0.34 |
| mattcl | input-pting | 1.1 ± 0.3 | 0.7 | 1.9 | 1.04 ± 0.36 |
| mattcl | input-kcen | 1.1 ± 0.3 | 0.8 | 1.7 | 1.05 ± 0.36 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.05 ± 0.35 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.8 | 2.3 | 1.08 ± 0.36 |
| lanjian | input-pting | 1.2 ± 0.3 | 0.8 | 2.0 | 1.12 ± 0.38 |
| lanjian | input-kcen | 1.2 ± 0.3 | 0.8 | 2.8 | 1.16 ± 0.39 |
| mattcl-ts | input-mattcl | 14.4 ± 0.3 | 13.7 | 15.7 | 13.73 ± 3.47 |
| mattcl-ts | input-lanjian | 14.5 ± 0.3 | 13.8 | 15.9 | 13.85 ± 3.51 |
| mattcl-ts | input-kcen | 14.6 ± 0.3 | 13.6 | 15.6 | 13.89 ± 3.51 |
| mattcl-ts | input-pting | 14.7 ± 0.3 | 13.9 | 15.5 | 13.98 ± 3.54 |
| mattcl-py | input-mattcl | 21.9 ± 0.9 | 20.9 | 29.7 | 20.85 ± 5.33 |
| pting | input-mattcl | 22.0 ± 0.8 | 21.1 | 25.1 | 20.94 ± 5.33 |
| pting | input-kcen | 22.3 ± 0.6 | 21.3 | 25.2 | 21.25 ± 5.39 |
| mattcl-py | input-kcen | 22.3 ± 0.7 | 21.5 | 25.8 | 21.27 ± 5.40 |
| mattcl-py | input-lanjian | 22.4 ± 1.0 | 21.3 | 29.5 | 21.32 ± 5.46 |
| pting | input-lanjian | 22.4 ± 0.8 | 21.5 | 25.7 | 21.33 ± 5.43 |
| mattcl-py | input-pting | 22.5 ± 0.7 | 21.6 | 25.5 | 21.44 ± 5.45 |
| pting | input-pting | 22.6 ± 0.7 | 21.3 | 25.5 | 21.48 ± 5.46 |
| kcen | input-mattcl | 27.6 ± 0.9 | 26.7 | 31.0 | 26.31 ± 6.68 |
| kcen | input-kcen | 28.6 ± 0.8 | 27.4 | 31.5 | 27.22 ± 6.91 |
| kcen | input-lanjian | 28.6 ± 0.8 | 27.7 | 31.8 | 27.23 ± 6.90 |
| kcen | input-pting | 29.0 ± 0.7 | 28.1 | 31.7 | 27.63 ± 6.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|