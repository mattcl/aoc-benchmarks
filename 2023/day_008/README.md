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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.8 | 1.00 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.9 | 1.9 | 1.00 ± 0.30 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.05 ± 0.32 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.05 ± 0.31 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.1 | 1.05 ± 0.32 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 2.1 | 1.06 ± 0.30 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 1.9 | 1.08 ± 0.31 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 2.1 | 1.12 ± 0.31 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.2 | 1.15 ± 0.33 |
| mattcl | input-pting | 1.5 ± 3.8 | 0.9 | 54.2 | 1.25 ± 3.13 |
| mattcl-ts | input-mattcl | 15.2 ± 0.4 | 14.4 | 16.3 | 12.63 ± 2.66 |
| mattcl-ts | input-chancalan | 15.2 ± 1.8 | 14.1 | 39.9 | 12.69 ± 3.05 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.5 | 16.4 | 12.71 ± 2.68 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 14.5 | 16.7 | 12.72 ± 2.68 |
| mattcl-ts | input-pting | 15.4 ± 0.4 | 14.7 | 16.5 | 12.83 ± 2.70 |
| pting | input-chancalan | 22.2 ± 0.8 | 20.9 | 25.5 | 18.48 ± 3.92 |
| mattcl-py | input-chancalan | 22.2 ± 0.8 | 20.8 | 25.6 | 18.51 ± 3.93 |
| pting | input-mattcl | 22.4 ± 0.8 | 21.1 | 25.8 | 18.65 ± 3.96 |
| mattcl-py | input-mattcl | 22.5 ± 0.8 | 21.4 | 25.8 | 18.69 ± 3.96 |
| pting | input-kcen | 22.9 ± 0.8 | 21.9 | 26.5 | 19.08 ± 4.05 |
| mattcl-py | input-lanjian | 23.0 ± 0.8 | 21.7 | 27.1 | 19.14 ± 4.06 |
| pting | input-lanjian | 23.0 ± 0.8 | 21.8 | 25.9 | 19.16 ± 4.06 |
| mattcl-py | input-kcen | 23.0 ± 0.7 | 22.1 | 26.1 | 19.17 ± 4.05 |
| pting | input-pting | 23.3 ± 0.9 | 22.5 | 29.5 | 19.37 ± 4.11 |
| mattcl-py | input-pting | 23.3 ± 0.8 | 22.1 | 25.8 | 19.41 ± 4.11 |
| chancalan | input-mattcl | 23.7 ± 0.7 | 22.8 | 26.3 | 19.75 ± 4.17 |
| chancalan | input-chancalan | 24.1 ± 3.9 | 22.5 | 62.0 | 20.06 ± 5.30 |
| chancalan | input-lanjian | 24.3 ± 0.7 | 23.4 | 27.8 | 20.25 ± 4.28 |
| chancalan | input-kcen | 24.5 ± 0.8 | 23.3 | 27.4 | 20.37 ± 4.31 |
| chancalan | input-pting | 25.0 ± 1.6 | 23.6 | 37.2 | 20.78 ± 4.54 |
| kcen | input-chancalan | 28.1 ± 0.8 | 26.5 | 30.8 | 23.38 ± 4.93 |
| kcen | input-mattcl | 28.5 ± 0.8 | 27.3 | 31.2 | 23.69 ± 5.00 |
| kcen | input-lanjian | 29.3 ± 0.7 | 28.3 | 31.3 | 24.38 ± 5.13 |
| kcen | input-kcen | 29.4 ± 0.8 | 28.2 | 32.6 | 24.50 ± 5.17 |
| kcen | input-pting | 30.1 ± 1.7 | 28.7 | 43.5 | 25.02 ± 5.41 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|