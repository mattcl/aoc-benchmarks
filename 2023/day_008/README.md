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
| mattcl | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.0 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 1.0 | 2.0 | 1.00 ± 0.29 |
| mattcl | input-pting | 1.3 ± 0.2 | 1.0 | 2.1 | 1.00 ± 0.28 |
| lanjian | input-chancalan | 1.4 ± 0.3 | 1.0 | 2.2 | 1.02 ± 0.29 |
| lanjian | input-mattcl | 1.4 ± 0.3 | 1.0 | 2.1 | 1.02 ± 0.29 |
| mattcl | input-chancalan | 1.4 ± 0.3 | 1.0 | 2.0 | 1.03 ± 0.29 |
| mattcl | input-kcen | 1.4 ± 0.3 | 1.0 | 2.0 | 1.03 ± 0.29 |
| lanjian | input-lanjian | 1.4 ± 0.3 | 1.0 | 2.2 | 1.05 ± 0.29 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.0 | 2.3 | 1.06 ± 0.29 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.2 | 1.09 ± 0.29 |
| mattcl-ts | input-chancalan | 15.1 ± 0.3 | 14.1 | 16.2 | 11.42 ± 2.37 |
| mattcl-ts | input-mattcl | 15.2 ± 0.3 | 14.3 | 16.2 | 11.46 ± 2.38 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.6 | 16.7 | 11.59 ± 2.41 |
| mattcl-ts | input-kcen | 15.4 ± 0.4 | 14.7 | 16.4 | 11.62 ± 2.41 |
| mattcl-ts | input-pting | 15.5 ± 0.4 | 14.6 | 16.8 | 11.68 ± 2.43 |
| pting | input-chancalan | 22.2 ± 0.7 | 21.1 | 25.1 | 16.74 ± 3.49 |
| mattcl-py | input-chancalan | 22.3 ± 0.7 | 21.2 | 25.2 | 16.80 ± 3.51 |
| mattcl-py | input-mattcl | 22.4 ± 0.7 | 21.4 | 26.1 | 16.95 ± 3.54 |
| pting | input-mattcl | 22.6 ± 0.9 | 21.4 | 25.6 | 17.09 ± 3.60 |
| mattcl-py | input-lanjian | 22.9 ± 0.8 | 21.9 | 26.2 | 17.27 ± 3.61 |
| pting | input-lanjian | 23.0 ± 0.9 | 21.6 | 27.2 | 17.34 ± 3.64 |
| pting | input-kcen | 23.0 ± 0.8 | 21.5 | 25.7 | 17.38 ± 3.64 |
| pting | input-pting | 23.1 ± 0.6 | 22.2 | 26.0 | 17.45 ± 3.63 |
| mattcl-py | input-kcen | 23.1 ± 0.8 | 21.9 | 26.5 | 17.46 ± 3.65 |
| mattcl-py | input-pting | 23.3 ± 0.8 | 22.1 | 26.2 | 17.58 ± 3.68 |
| chancalan | input-chancalan | 23.7 ± 0.8 | 22.6 | 26.8 | 17.86 ± 3.74 |
| chancalan | input-mattcl | 23.7 ± 0.6 | 22.9 | 26.3 | 17.90 ± 3.72 |
| chancalan | input-lanjian | 24.3 ± 0.6 | 23.2 | 27.2 | 18.37 ± 3.82 |
| chancalan | input-kcen | 24.5 ± 0.8 | 23.4 | 28.1 | 18.51 ± 3.87 |
| chancalan | input-pting | 25.2 ± 4.3 | 23.3 | 70.8 | 19.00 ± 5.07 |
| kcen | input-mattcl | 28.4 ± 1.1 | 26.8 | 36.2 | 21.48 ± 4.51 |
| kcen | input-chancalan | 28.4 ± 4.1 | 26.9 | 69.4 | 21.48 ± 5.41 |
| kcen | input-lanjian | 29.3 ± 0.9 | 27.7 | 32.6 | 22.10 ± 4.61 |
| kcen | input-kcen | 29.5 ± 1.4 | 27.7 | 39.5 | 22.31 ± 4.72 |
| kcen | input-pting | 30.8 ± 6.6 | 28.5 | 74.5 | 23.27 ± 6.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|