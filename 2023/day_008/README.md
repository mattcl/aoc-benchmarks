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
| mattcl | input-mattcl | 1.3 ± 0.3 | 0.9 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 1.0 | 2.0 | 1.03 ± 0.29 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.9 | 2.2 | 1.03 ± 0.28 |
| mattcl | input-pting | 1.3 ± 0.3 | 1.0 | 2.0 | 1.05 ± 0.29 |
| lanjian | input-mattcl | 1.4 ± 0.3 | 1.0 | 2.1 | 1.07 ± 0.31 |
| mattcl | input-kcen | 1.4 ± 0.3 | 1.0 | 2.1 | 1.07 ± 0.29 |
| lanjian | input-chancalan | 1.4 ± 0.3 | 1.0 | 2.1 | 1.10 ± 0.31 |
| lanjian | input-kcen | 1.4 ± 0.2 | 1.0 | 2.1 | 1.13 ± 0.30 |
| lanjian | input-pting | 1.5 ± 0.3 | 1.0 | 2.2 | 1.15 ± 0.31 |
| lanjian | input-lanjian | 1.5 ± 1.6 | 1.0 | 24.0 | 1.17 ± 1.29 |
| mattcl-ts | input-chancalan | 15.0 ± 0.3 | 14.1 | 16.3 | 11.75 ± 2.39 |
| mattcl-ts | input-mattcl | 15.1 ± 0.3 | 14.2 | 16.1 | 11.84 ± 2.40 |
| mattcl-ts | input-kcen | 15.2 ± 0.3 | 14.4 | 15.9 | 11.90 ± 2.41 |
| mattcl-ts | input-lanjian | 15.2 ± 0.4 | 14.5 | 16.6 | 11.93 ± 2.43 |
| mattcl-ts | input-pting | 15.2 ± 0.3 | 14.2 | 16.4 | 11.95 ± 2.43 |
| mattcl-py | input-chancalan | 22.2 ± 0.8 | 21.2 | 25.1 | 17.45 ± 3.59 |
| mattcl-py | input-mattcl | 22.4 ± 0.6 | 21.4 | 25.1 | 17.55 ± 3.58 |
| pting | input-chancalan | 22.4 ± 0.9 | 21.4 | 25.5 | 17.56 ± 3.62 |
| pting | input-mattcl | 22.4 ± 0.8 | 21.4 | 25.5 | 17.61 ± 3.61 |
| pting | input-kcen | 22.8 ± 0.7 | 22.0 | 25.8 | 17.87 ± 3.65 |
| pting | input-lanjian | 22.8 ± 0.8 | 22.0 | 26.5 | 17.92 ± 3.67 |
| mattcl-py | input-kcen | 22.9 ± 0.7 | 22.0 | 26.0 | 17.98 ± 3.68 |
| mattcl-py | input-lanjian | 23.0 ± 1.0 | 21.7 | 31.0 | 18.03 ± 3.73 |
| mattcl-py | input-pting | 23.2 ± 0.7 | 22.0 | 26.1 | 18.21 ± 3.72 |
| pting | input-pting | 23.2 ± 0.9 | 22.3 | 27.5 | 18.23 ± 3.75 |
| chancalan | input-chancalan | 23.6 ± 0.8 | 22.4 | 26.8 | 18.55 ± 3.79 |
| chancalan | input-mattcl | 23.7 ± 0.8 | 22.7 | 27.1 | 18.63 ± 3.81 |
| chancalan | input-lanjian | 24.3 ± 0.7 | 23.1 | 26.8 | 19.07 ± 3.89 |
| chancalan | input-kcen | 24.4 ± 0.8 | 23.4 | 27.5 | 19.17 ± 3.92 |
| chancalan | input-pting | 24.6 ± 1.1 | 23.5 | 33.5 | 19.34 ± 4.00 |
| kcen | input-chancalan | 27.9 ± 0.8 | 26.9 | 31.3 | 21.93 ± 4.47 |
| kcen | input-mattcl | 28.3 ± 0.8 | 27.1 | 30.9 | 22.23 ± 4.53 |
| kcen | input-lanjian | 29.3 ± 0.9 | 28.2 | 31.9 | 23.02 ± 4.70 |
| kcen | input-kcen | 29.4 ± 1.0 | 28.2 | 33.7 | 23.06 ± 4.73 |
| kcen | input-pting | 29.5 ± 0.6 | 28.6 | 33.0 | 23.16 ± 4.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|