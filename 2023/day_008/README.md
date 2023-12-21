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
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.9 | 2.0 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.3 | 0.9 | 1.9 | 1.01 ± 0.28 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.9 | 1.9 | 1.02 ± 0.28 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.9 | 2.0 | 1.03 ± 0.27 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.9 | 2.0 | 1.03 ± 0.28 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 1.9 | 1.04 ± 0.29 |
| mattcl | input-kcen | 1.3 ± 0.3 | 1.0 | 1.9 | 1.05 ± 0.28 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 1.0 | 2.2 | 1.07 ± 0.29 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.0 | 2.2 | 1.11 ± 0.29 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.3 | 1.12 ± 0.31 |
| mattcl-ts | input-chancalan | 14.7 ± 0.4 | 13.5 | 15.9 | 11.67 ± 2.25 |
| mattcl-ts | input-mattcl | 14.8 ± 0.4 | 13.6 | 15.8 | 11.79 ± 2.27 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 13.6 | 16.1 | 11.91 ± 2.29 |
| mattcl-ts | input-kcen | 15.0 ± 0.3 | 13.9 | 16.5 | 11.95 ± 2.30 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.2 | 15.8 | 12.00 ± 2.30 |
| mattcl-py | input-chancalan | 21.9 ± 0.6 | 21.0 | 24.8 | 17.47 ± 3.37 |
| pting | input-chancalan | 22.2 ± 1.0 | 21.1 | 27.4 | 17.66 ± 3.46 |
| pting | input-mattcl | 22.3 ± 0.8 | 21.4 | 25.7 | 17.78 ± 3.45 |
| mattcl-py | input-mattcl | 22.4 ± 0.9 | 21.3 | 25.4 | 17.82 ± 3.47 |
| mattcl-py | input-lanjian | 22.6 ± 0.6 | 21.9 | 25.8 | 17.97 ± 3.46 |
| pting | input-kcen | 22.7 ± 0.7 | 21.9 | 25.3 | 18.06 ± 3.48 |
| pting | input-lanjian | 22.7 ± 1.2 | 21.6 | 33.0 | 18.06 ± 3.57 |
| mattcl-py | input-kcen | 22.8 ± 0.8 | 21.6 | 25.6 | 18.14 ± 3.52 |
| mattcl-py | input-pting | 23.1 ± 0.9 | 22.0 | 26.2 | 18.39 ± 3.57 |
| pting | input-pting | 23.4 ± 4.0 | 21.9 | 56.0 | 18.61 ± 4.79 |
| chancalan | input-chancalan | 23.6 ± 1.7 | 22.2 | 39.0 | 18.76 ± 3.83 |
| chancalan | input-mattcl | 23.6 ± 0.7 | 22.3 | 27.0 | 18.78 ± 3.63 |
| chancalan | input-lanjian | 24.0 ± 0.8 | 23.2 | 27.2 | 19.12 ± 3.71 |
| chancalan | input-kcen | 24.2 ± 0.9 | 23.0 | 27.4 | 19.31 ± 3.75 |
| chancalan | input-pting | 24.5 ± 0.8 | 23.5 | 27.4 | 19.53 ± 3.78 |
| kcen | input-chancalan | 27.6 ± 0.7 | 26.5 | 30.3 | 21.99 ± 4.23 |
| kcen | input-mattcl | 28.1 ± 1.1 | 26.9 | 34.5 | 22.34 ± 4.34 |
| kcen | input-lanjian | 29.0 ± 0.9 | 27.8 | 31.7 | 23.10 ± 4.46 |
| kcen | input-kcen | 29.1 ± 0.9 | 28.2 | 32.5 | 23.21 ± 4.49 |
| kcen | input-pting | 29.6 ± 1.1 | 28.5 | 33.8 | 23.61 ± 4.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|