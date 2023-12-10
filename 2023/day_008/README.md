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
| mattcl | input-lanjian | 1.1 ± 0.3 | 0.8 | 1.8 | 1.04 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 2.2 | 1.08 ± 0.33 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 4.1 | 1.08 ± 0.39 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.8 | 1.09 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.15 ± 0.34 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.8 | 2.0 | 1.16 ± 0.35 |
| lanjian | input-kcen | 1.6 ± 4.5 | 0.9 | 64.6 | 1.46 ± 4.11 |
| mattcl-ts | input-mattcl | 14.6 ± 0.4 | 13.6 | 15.6 | 13.31 ± 2.88 |
| mattcl-ts | input-lanjian | 14.7 ± 0.4 | 13.8 | 15.9 | 13.39 ± 2.90 |
| mattcl-ts | input-pting | 14.8 ± 0.4 | 13.8 | 15.7 | 13.47 ± 2.91 |
| mattcl-ts | input-kcen | 14.8 ± 0.4 | 13.7 | 15.9 | 13.47 ± 2.92 |
| mattcl-py | input-mattcl | 22.3 ± 0.6 | 21.3 | 25.1 | 20.34 ± 4.41 |
| pting | input-kcen | 22.7 ± 0.7 | 21.7 | 25.5 | 20.70 ± 4.49 |
| pting | input-lanjian | 22.8 ± 0.9 | 21.7 | 26.1 | 20.79 ± 4.53 |
| mattcl-py | input-lanjian | 22.8 ± 0.9 | 21.5 | 26.1 | 20.80 ± 4.54 |
| pting | input-mattcl | 23.0 ± 1.3 | 21.6 | 28.0 | 20.95 ± 4.66 |
| mattcl-py | input-kcen | 23.0 ± 0.8 | 21.8 | 25.5 | 20.96 ± 4.56 |
| pting | input-pting | 23.2 ± 1.0 | 21.7 | 29.7 | 21.15 ± 4.63 |
| mattcl-py | input-pting | 23.6 ± 3.2 | 22.2 | 57.1 | 21.53 ± 5.48 |
| kcen | input-mattcl | 28.4 ± 0.9 | 27.0 | 31.6 | 25.91 ± 5.63 |
| kcen | input-lanjian | 29.1 ± 0.9 | 27.7 | 32.2 | 26.60 ± 5.78 |
| kcen | input-kcen | 29.5 ± 2.1 | 27.8 | 48.5 | 26.91 ± 6.10 |
| kcen | input-pting | 29.9 ± 1.0 | 28.2 | 32.7 | 27.28 ± 5.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|