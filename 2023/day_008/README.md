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
| mattcl | input-mattcl | 1.1 ± 0.3 | 0.8 | 1.7 | 1.00 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.03 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.9 | 1.03 ± 0.32 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.33 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.33 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.0 | 1.06 ± 0.33 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.9 | 2.1 | 1.06 ± 0.31 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.07 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.14 ± 0.35 |
| mattcl-ts | input-mattcl | 14.9 ± 0.3 | 14.0 | 15.6 | 13.03 ± 2.95 |
| mattcl-ts | input-chancalan | 14.9 ± 2.5 | 13.9 | 49.9 | 13.06 ± 3.67 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.2 | 16.0 | 13.08 ± 2.96 |
| mattcl-ts | input-kcen | 15.0 ± 0.3 | 14.1 | 16.1 | 13.14 ± 2.97 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.2 | 16.2 | 13.17 ± 2.98 |
| mattcl-py | input-chancalan | 21.9 ± 0.8 | 20.7 | 25.3 | 19.18 ± 4.38 |
| pting | input-chancalan | 22.2 ± 3.0 | 20.8 | 56.1 | 19.40 ± 5.11 |
| mattcl-py | input-mattcl | 22.2 ± 0.7 | 21.2 | 25.1 | 19.40 ± 4.42 |
| pting | input-mattcl | 22.2 ± 0.7 | 21.3 | 25.0 | 19.44 ± 4.42 |
| mattcl-py | input-lanjian | 22.6 ± 0.7 | 21.7 | 25.3 | 19.72 ± 4.48 |
| pting | input-kcen | 22.6 ± 0.8 | 21.5 | 25.7 | 19.72 ± 4.49 |
| mattcl-py | input-kcen | 22.6 ± 0.7 | 21.6 | 26.0 | 19.73 ± 4.48 |
| pting | input-pting | 22.8 ± 0.6 | 21.9 | 25.4 | 19.91 ± 4.52 |
| pting | input-lanjian | 22.8 ± 0.9 | 21.9 | 26.0 | 19.96 ± 4.57 |
| mattcl-py | input-pting | 22.9 ± 0.8 | 21.8 | 26.9 | 19.98 ± 4.55 |
| chancalan | input-chancalan | 23.3 ± 0.6 | 22.2 | 26.0 | 20.39 ± 4.62 |
| chancalan | input-mattcl | 23.6 ± 0.9 | 22.8 | 27.0 | 20.66 ± 4.71 |
| chancalan | input-kcen | 24.1 ± 0.7 | 23.3 | 27.4 | 21.06 ± 4.79 |
| chancalan | input-lanjian | 24.1 ± 0.9 | 22.8 | 26.8 | 21.11 ± 4.82 |
| chancalan | input-pting | 24.5 ± 0.7 | 23.4 | 27.8 | 21.40 ± 4.86 |
| kcen | input-chancalan | 27.6 ± 0.8 | 26.6 | 30.6 | 24.13 ± 5.48 |
| kcen | input-mattcl | 28.1 ± 0.9 | 27.0 | 31.4 | 24.59 ± 5.60 |
| kcen | input-kcen | 29.0 ± 0.9 | 27.9 | 32.3 | 25.37 ± 5.76 |
| kcen | input-lanjian | 29.1 ± 1.2 | 27.9 | 38.8 | 25.41 ± 5.83 |
| kcen | input-pting | 29.5 ± 0.9 | 28.3 | 32.9 | 25.83 ± 5.87 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|