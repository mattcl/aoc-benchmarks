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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.8 | 1.7 | 1.02 ± 0.31 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.9 | 1.03 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.8 | 1.7 | 1.07 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 2.0 | 1.08 ± 0.33 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.9 | 1.11 ± 0.34 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.15 ± 0.35 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.16 ± 0.35 |
| mattcl-ts | input-mattcl | 14.7 ± 0.4 | 13.8 | 15.9 | 13.43 ± 2.98 |
| mattcl-ts | input-lanjian | 14.9 ± 0.3 | 13.9 | 15.8 | 13.53 ± 2.99 |
| mattcl-ts | input-kcen | 14.9 ± 0.3 | 14.0 | 16.0 | 13.59 ± 3.00 |
| mattcl-ts | input-pting | 15.0 ± 0.4 | 14.1 | 16.4 | 13.63 ± 3.01 |
| mattcl-py | input-mattcl | 22.3 ± 0.7 | 21.4 | 25.3 | 20.32 ± 4.52 |
| pting | input-mattcl | 22.4 ± 1.0 | 21.0 | 26.6 | 20.44 ± 4.58 |
| mattcl-py | input-lanjian | 22.6 ± 0.7 | 21.2 | 25.4 | 20.62 ± 4.58 |
| mattcl-py | input-kcen | 22.7 ± 0.7 | 21.3 | 25.4 | 20.65 ± 4.59 |
| pting | input-kcen | 22.7 ± 0.8 | 21.4 | 25.7 | 20.66 ± 4.60 |
| pting | input-lanjian | 22.9 ± 1.3 | 21.7 | 35.3 | 20.83 ± 4.74 |
| pting | input-pting | 23.0 ± 0.7 | 22.0 | 25.8 | 20.93 ± 4.65 |
| mattcl-py | input-pting | 23.0 ± 0.7 | 22.0 | 25.3 | 20.95 ± 4.65 |
| kcen | input-mattcl | 28.3 ± 0.8 | 27.2 | 31.0 | 25.74 ± 5.71 |
| kcen | input-lanjian | 29.0 ± 0.6 | 28.0 | 31.3 | 26.43 ± 5.84 |
| kcen | input-kcen | 29.5 ± 2.8 | 28.0 | 56.3 | 26.86 ± 6.43 |
| kcen | input-pting | 29.6 ± 0.9 | 28.3 | 32.4 | 27.00 ± 6.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|