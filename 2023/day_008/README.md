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
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.9 | 1.9 | 1.01 ± 0.28 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 1.8 | 1.02 ± 0.29 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.0 | 1.04 ± 0.29 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.05 ± 0.30 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.1 | 1.05 ± 0.30 |
| mattcl | input-kcen | 1.3 ± 0.3 | 1.0 | 2.2 | 1.06 ± 0.30 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.08 ± 0.30 |
| lanjian | input-pting | 1.3 ± 0.2 | 1.0 | 2.2 | 1.09 ± 0.29 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.2 | 1.12 ± 0.30 |
| mattcl-ts | input-chancalan | 15.0 ± 0.4 | 13.9 | 16.0 | 12.09 ± 2.38 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.2 | 16.9 | 12.20 ± 2.41 |
| mattcl-ts | input-lanjian | 15.2 ± 0.3 | 14.2 | 16.2 | 12.25 ± 2.41 |
| mattcl-ts | input-kcen | 15.3 ± 0.3 | 14.6 | 17.1 | 12.31 ± 2.43 |
| mattcl-ts | input-pting | 15.6 ± 2.8 | 14.4 | 54.0 | 12.57 ± 3.35 |
| pting | input-chancalan | 22.1 ± 0.7 | 21.2 | 25.3 | 17.86 ± 3.54 |
| mattcl-py | input-chancalan | 22.2 ± 0.7 | 21.0 | 25.2 | 17.92 ± 3.56 |
| mattcl-py | input-mattcl | 22.4 ± 0.7 | 21.4 | 25.3 | 18.04 ± 3.58 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.3 | 25.6 | 18.06 ± 3.59 |
| pting | input-kcen | 22.8 ± 0.7 | 21.7 | 25.7 | 18.38 ± 3.64 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.9 | 26.0 | 18.46 ± 3.67 |
| mattcl-py | input-lanjian | 22.9 ± 0.9 | 21.7 | 26.5 | 18.48 ± 3.69 |
| mattcl-py | input-kcen | 22.9 ± 0.8 | 21.8 | 26.5 | 18.49 ± 3.68 |
| mattcl-py | input-pting | 23.2 ± 0.8 | 22.1 | 26.0 | 18.73 ± 3.72 |
| pting | input-pting | 23.4 ± 0.9 | 22.1 | 26.1 | 18.83 ± 3.76 |
| chancalan | input-chancalan | 23.5 ± 0.7 | 22.3 | 26.2 | 18.98 ± 3.76 |
| chancalan | input-mattcl | 23.7 ± 0.7 | 22.6 | 26.8 | 19.09 ± 3.78 |
| chancalan | input-lanjian | 24.3 ± 0.8 | 22.6 | 27.3 | 19.57 ± 3.89 |
| chancalan | input-kcen | 24.4 ± 1.2 | 22.9 | 33.8 | 19.66 ± 3.96 |
| chancalan | input-pting | 24.8 ± 0.8 | 23.4 | 27.5 | 19.96 ± 3.96 |
| kcen | input-chancalan | 28.0 ± 0.9 | 26.9 | 31.2 | 22.60 ± 4.48 |
| kcen | input-mattcl | 28.4 ± 0.8 | 26.9 | 31.2 | 22.86 ± 4.52 |
| kcen | input-kcen | 29.3 ± 1.0 | 28.0 | 32.9 | 23.66 ± 4.71 |
| kcen | input-lanjian | 29.4 ± 1.0 | 28.1 | 33.1 | 23.72 ± 4.71 |
| kcen | input-pting | 29.8 ± 1.0 | 28.3 | 32.9 | 24.05 ± 4.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|