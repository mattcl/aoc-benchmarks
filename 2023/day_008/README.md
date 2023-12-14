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
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 2.1 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.9 | 1.8 | 1.00 ± 0.30 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.9 | 2.1 | 1.02 ± 0.29 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.03 ± 0.30 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.9 | 1.9 | 1.03 ± 0.29 |
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.04 ± 0.30 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.9 | 1.9 | 1.05 ± 0.29 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.07 ± 0.30 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.0 | 2.2 | 1.11 ± 0.31 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.2 | 1.14 ± 0.31 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.0 | 16.2 | 12.23 ± 2.50 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.4 | 15.8 | 12.28 ± 2.50 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.1 | 16.4 | 12.28 ± 2.51 |
| mattcl-ts | input-pting | 15.2 ± 0.3 | 14.2 | 16.1 | 12.34 ± 2.52 |
| mattcl-ts | input-chancalan | 15.3 ± 4.9 | 13.8 | 83.4 | 12.45 ± 4.74 |
| mattcl-py | input-chancalan | 22.2 ± 0.8 | 21.4 | 25.5 | 18.08 ± 3.72 |
| mattcl-py | input-mattcl | 22.3 ± 0.7 | 21.3 | 25.4 | 18.17 ± 3.74 |
| pting | input-mattcl | 22.4 ± 0.6 | 21.6 | 25.7 | 18.21 ± 3.73 |
| pting | input-chancalan | 22.4 ± 1.6 | 21.3 | 38.5 | 18.26 ± 3.93 |
| mattcl-py | input-lanjian | 22.8 ± 0.8 | 21.7 | 25.8 | 18.53 ± 3.82 |
| mattcl-py | input-kcen | 22.8 ± 0.6 | 21.4 | 25.4 | 18.55 ± 3.80 |
| pting | input-kcen | 22.9 ± 0.8 | 22.0 | 25.8 | 18.64 ± 3.83 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.7 | 25.8 | 18.64 ± 3.83 |
| pting | input-pting | 23.1 ± 0.7 | 22.1 | 25.9 | 18.82 ± 3.86 |
| mattcl-py | input-pting | 23.2 ± 0.8 | 22.1 | 25.9 | 18.89 ± 3.89 |
| chancalan | input-chancalan | 23.7 ± 0.8 | 22.8 | 26.8 | 19.26 ± 3.97 |
| chancalan | input-mattcl | 24.0 ± 1.1 | 23.0 | 28.6 | 19.55 ± 4.06 |
| chancalan | input-lanjian | 24.3 ± 0.7 | 23.2 | 26.9 | 19.79 ± 4.06 |
| chancalan | input-kcen | 24.6 ± 0.9 | 23.3 | 27.4 | 19.99 ± 4.13 |
| chancalan | input-pting | 24.7 ± 0.8 | 23.6 | 27.5 | 20.11 ± 4.13 |
| kcen | input-chancalan | 28.2 ± 0.9 | 27.1 | 31.0 | 22.98 ± 4.72 |
| kcen | input-mattcl | 28.4 ± 0.8 | 27.3 | 31.0 | 23.13 ± 4.74 |
| kcen | input-lanjian | 29.3 ± 0.9 | 28.1 | 32.6 | 23.85 ± 4.90 |
| kcen | input-kcen | 29.5 ± 0.9 | 28.5 | 33.0 | 24.04 ± 4.93 |
| kcen | input-pting | 29.8 ± 0.8 | 28.7 | 32.6 | 24.24 ± 4.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|