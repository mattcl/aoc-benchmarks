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

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.9 | 1.9 | 1.00 |
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.9 | 1.9 | 1.04 ± 0.30 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 1.9 | 1.04 ± 0.30 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.9 | 2.0 | 1.04 ± 0.28 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.05 ± 0.30 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.9 | 1.9 | 1.06 ± 0.29 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 1.0 | 1.9 | 1.09 ± 0.29 |
| mattcl | input-kcen | 1.3 ± 0.3 | 1.0 | 2.0 | 1.09 ± 0.31 |
| lanjian | input-pting | 1.4 ± 0.2 | 1.0 | 2.0 | 1.12 ± 0.30 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.1 | 1.18 ± 0.32 |
| mattcl-ts | input-chancalan | 14.9 ± 0.3 | 14.2 | 15.8 | 12.34 ± 2.52 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.0 | 15.9 | 12.41 ± 2.53 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.3 | 16.2 | 12.50 ± 2.55 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.2 | 16.7 | 12.53 ± 2.56 |
| mattcl-ts | input-pting | 15.2 ± 0.3 | 14.3 | 16.4 | 12.53 ± 2.56 |
| pting | input-chancalan | 22.1 ± 0.7 | 21.1 | 25.3 | 18.27 ± 3.75 |
| mattcl-py | input-chancalan | 22.1 ± 0.7 | 20.9 | 24.9 | 18.31 ± 3.76 |
| mattcl-py | input-mattcl | 22.3 ± 0.8 | 21.4 | 26.1 | 18.48 ± 3.81 |
| mattcl-py | input-lanjian | 22.7 ± 0.8 | 21.8 | 25.9 | 18.81 ± 3.88 |
| pting | input-mattcl | 22.7 ± 4.1 | 21.1 | 68.3 | 18.81 ± 5.09 |
| pting | input-lanjian | 22.7 ± 0.7 | 21.7 | 26.2 | 18.82 ± 3.87 |
| mattcl-py | input-kcen | 22.8 ± 0.8 | 21.8 | 26.1 | 18.88 ± 3.89 |
| pting | input-kcen | 22.9 ± 0.9 | 21.9 | 25.7 | 18.94 ± 3.92 |
| pting | input-pting | 23.0 ± 0.7 | 22.1 | 25.6 | 18.99 ± 3.90 |
| mattcl-py | input-pting | 23.1 ± 0.8 | 22.3 | 26.6 | 19.14 ± 3.95 |
| chancalan | input-chancalan | 23.5 ± 0.7 | 22.4 | 26.4 | 19.45 ± 3.99 |
| chancalan | input-mattcl | 23.7 ± 0.8 | 23.0 | 28.3 | 19.63 ± 4.04 |
| chancalan | input-kcen | 24.3 ± 0.7 | 23.4 | 27.4 | 20.06 ± 4.11 |
| chancalan | input-lanjian | 24.5 ± 1.0 | 23.3 | 27.7 | 20.23 ± 4.20 |
| chancalan | input-pting | 24.6 ± 0.8 | 23.4 | 27.9 | 20.35 ± 4.18 |
| kcen | input-chancalan | 28.0 ± 0.8 | 27.0 | 31.1 | 23.12 ± 4.74 |
| kcen | input-mattcl | 28.2 ± 0.9 | 27.1 | 31.2 | 23.33 ± 4.79 |
| kcen | input-lanjian | 29.1 ± 0.9 | 27.9 | 32.3 | 24.09 ± 4.94 |
| kcen | input-kcen | 29.3 ± 0.8 | 28.2 | 32.4 | 24.22 ± 4.96 |
| kcen | input-pting | 29.9 ± 1.0 | 28.5 | 33.3 | 24.71 ± 5.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|