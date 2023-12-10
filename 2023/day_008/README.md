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
| mattcl | input-mattcl | 1.1 ± 0.3 | 0.8 | 1.9 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.4 | 1.03 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.9 | 1.04 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.9 | 1.8 | 1.05 ± 0.30 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.9 | 2.0 | 1.07 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 1.9 | 1.08 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 1.9 | 1.12 ± 0.33 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.1 | 1.19 ± 0.36 |
| mattcl-ts | input-mattcl | 14.6 ± 0.3 | 13.9 | 15.7 | 12.77 ± 2.81 |
| mattcl-ts | input-lanjian | 14.8 ± 0.4 | 13.8 | 15.7 | 12.93 ± 2.85 |
| mattcl-ts | input-kcen | 14.9 ± 0.4 | 13.8 | 16.1 | 12.98 ± 2.86 |
| mattcl-ts | input-pting | 14.9 ± 0.3 | 14.1 | 15.8 | 13.06 ± 2.88 |
| pting | input-mattcl | 22.3 ± 0.7 | 21.2 | 25.5 | 19.48 ± 4.31 |
| mattcl-py | input-mattcl | 22.4 ± 1.5 | 21.2 | 39.1 | 19.54 ± 4.49 |
| mattcl-py | input-lanjian | 22.4 ± 0.6 | 21.6 | 25.2 | 19.59 ± 4.33 |
| pting | input-kcen | 22.5 ± 0.7 | 21.4 | 25.9 | 19.70 ± 4.36 |
| pting | input-lanjian | 22.7 ± 0.8 | 21.7 | 25.8 | 19.84 ± 4.40 |
| mattcl-py | input-kcen | 22.7 ± 0.8 | 22.0 | 26.3 | 19.86 ± 4.40 |
| mattcl-py | input-pting | 23.0 ± 0.8 | 22.0 | 26.4 | 20.08 ± 4.45 |
| pting | input-pting | 23.1 ± 0.9 | 22.0 | 25.9 | 20.23 ± 4.50 |
| kcen | input-mattcl | 28.2 ± 0.9 | 27.1 | 31.1 | 24.66 ± 5.46 |
| kcen | input-kcen | 29.1 ± 0.8 | 28.0 | 31.8 | 25.45 ± 5.62 |
| kcen | input-lanjian | 29.3 ± 1.1 | 27.9 | 33.1 | 25.62 ± 5.70 |
| kcen | input-pting | 29.7 ± 1.0 | 28.3 | 32.4 | 25.91 ± 5.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|