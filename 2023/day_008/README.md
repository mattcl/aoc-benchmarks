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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.8 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.04 ± 0.30 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.9 | 1.05 ± 0.32 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.8 | 2.0 | 1.05 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 2.0 | 1.06 ± 0.32 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.9 | 1.9 | 1.07 ± 0.31 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 2.9 | 1.08 ± 0.34 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.8 | 2.0 | 1.09 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.12 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.14 ± 0.34 |
| mattcl-ts | input-chancalan | 15.0 ± 0.4 | 14.2 | 17.2 | 13.13 ± 2.86 |
| mattcl-ts | input-mattcl | 15.1 ± 0.3 | 14.2 | 16.4 | 13.21 ± 2.87 |
| mattcl-ts | input-kcen | 15.2 ± 0.4 | 14.4 | 16.6 | 13.26 ± 2.89 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.3 | 16.9 | 13.34 ± 2.91 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.4 | 16.8 | 13.35 ± 2.91 |
| mattcl-py | input-chancalan | 22.2 ± 0.7 | 21.0 | 25.4 | 19.36 ± 4.24 |
| pting | input-chancalan | 22.2 ± 0.8 | 21.2 | 25.4 | 19.38 ± 4.25 |
| pting | input-mattcl | 22.3 ± 0.8 | 21.3 | 26.0 | 19.51 ± 4.28 |
| pting | input-kcen | 22.7 ± 0.7 | 21.3 | 25.7 | 19.82 ± 4.34 |
| mattcl-py | input-lanjian | 22.7 ± 0.9 | 21.5 | 27.1 | 19.86 ± 4.36 |
| mattcl-py | input-mattcl | 22.8 ± 1.6 | 21.5 | 36.6 | 19.87 ± 4.53 |
| mattcl-py | input-kcen | 22.8 ± 0.7 | 21.8 | 26.0 | 19.90 ± 4.35 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.4 | 26.2 | 19.96 ± 4.37 |
| mattcl-py | input-pting | 23.1 ± 0.7 | 21.8 | 26.0 | 20.21 ± 4.42 |
| chancalan | input-chancalan | 23.4 ± 0.8 | 22.4 | 26.6 | 20.47 ± 4.48 |
| pting | input-pting | 23.6 ± 3.3 | 21.7 | 58.8 | 20.59 ± 5.29 |
| chancalan | input-mattcl | 23.7 ± 0.8 | 22.6 | 26.5 | 20.67 ± 4.52 |
| chancalan | input-lanjian | 24.2 ± 0.7 | 23.1 | 26.8 | 21.15 ± 4.61 |
| chancalan | input-kcen | 24.4 ± 0.8 | 23.4 | 27.0 | 21.30 ± 4.66 |
| chancalan | input-pting | 24.7 ± 1.2 | 23.7 | 35.1 | 21.53 ± 4.77 |
| kcen | input-chancalan | 28.1 ± 0.9 | 26.6 | 30.9 | 24.51 ± 5.36 |
| kcen | input-mattcl | 28.2 ± 0.9 | 27.2 | 31.4 | 24.65 ± 5.39 |
| kcen | input-kcen | 29.3 ± 0.7 | 28.2 | 31.4 | 25.61 ± 5.58 |
| kcen | input-lanjian | 29.4 ± 1.1 | 28.1 | 32.7 | 25.64 ± 5.63 |
| kcen | input-pting | 29.8 ± 0.9 | 28.6 | 32.5 | 26.03 ± 5.69 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|