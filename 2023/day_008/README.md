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
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.9 | 1.05 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 2.0 | 1.05 ± 0.31 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.32 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.9 | 1.06 ± 0.33 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.10 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.12 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.13 ± 0.33 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.3 | 15.9 | 13.22 ± 2.88 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.1 | 16.5 | 13.25 ± 2.89 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.2 | 16.5 | 13.27 ± 2.90 |
| mattcl-ts | input-mattcl | 15.3 ± 4.3 | 14.3 | 74.0 | 13.46 ± 4.77 |
| pting | input-mattcl | 22.3 ± 0.7 | 21.5 | 25.7 | 19.61 ± 4.30 |
| mattcl-py | input-mattcl | 22.4 ± 0.9 | 21.3 | 25.7 | 19.65 ± 4.33 |
| mattcl-py | input-lanjian | 22.6 ± 0.7 | 21.5 | 25.5 | 19.86 ± 4.36 |
| pting | input-kcen | 22.8 ± 0.7 | 21.8 | 25.6 | 19.99 ± 4.39 |
| pting | input-lanjian | 22.8 ± 0.9 | 21.8 | 26.5 | 20.03 ± 4.41 |
| mattcl-py | input-kcen | 22.9 ± 0.8 | 21.8 | 26.1 | 20.12 ± 4.43 |
| mattcl-py | input-pting | 23.0 ± 0.7 | 22.1 | 26.4 | 20.18 ± 4.43 |
| pting | input-pting | 23.4 ± 3.1 | 22.1 | 56.5 | 20.50 ± 5.19 |
| kcen | input-mattcl | 28.2 ± 0.8 | 26.9 | 30.9 | 24.74 ± 5.42 |
| kcen | input-lanjian | 29.1 ± 0.9 | 27.8 | 32.0 | 25.56 ± 5.60 |
| kcen | input-kcen | 29.3 ± 0.9 | 28.1 | 34.4 | 25.70 ± 5.63 |
| kcen | input-pting | 29.5 ± 0.7 | 28.3 | 31.8 | 25.88 ± 5.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|