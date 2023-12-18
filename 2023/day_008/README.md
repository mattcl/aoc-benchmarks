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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.9 | 1.00 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.9 | 1.9 | 1.03 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 1.9 | 1.04 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.9 | 2.0 | 1.06 ± 0.31 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.9 | 3.2 | 1.06 ± 0.34 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.06 ± 0.33 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.0 | 1.06 ± 0.33 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.08 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 2.2 | 1.11 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.2 | 1.15 ± 0.34 |
| mattcl-ts | input-chancalan | 14.8 ± 0.4 | 13.8 | 15.9 | 12.53 ± 2.81 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.1 | 16.1 | 12.65 ± 2.84 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.3 | 16.1 | 12.74 ± 2.86 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.3 | 16.1 | 12.76 ± 2.86 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.3 | 16.7 | 12.80 ± 2.87 |
| mattcl-py | input-chancalan | 22.1 ± 0.7 | 21.1 | 24.8 | 18.65 ± 4.21 |
| pting | input-chancalan | 22.2 ± 0.8 | 21.2 | 25.5 | 18.75 ± 4.24 |
| pting | input-mattcl | 22.3 ± 0.7 | 21.3 | 25.2 | 18.88 ± 4.26 |
| mattcl-py | input-lanjian | 22.5 ± 0.6 | 21.7 | 25.6 | 19.02 ± 4.28 |
| mattcl-py | input-mattcl | 22.6 ± 4.3 | 21.6 | 71.5 | 19.11 ± 5.61 |
| mattcl-py | input-kcen | 22.7 ± 0.7 | 21.9 | 25.5 | 19.22 ± 4.33 |
| pting | input-kcen | 22.8 ± 0.7 | 21.9 | 25.2 | 19.25 ± 4.34 |
| pting | input-lanjian | 22.8 ± 0.8 | 21.6 | 26.0 | 19.30 ± 4.37 |
| mattcl-py | input-pting | 23.0 ± 0.8 | 22.1 | 26.1 | 19.42 ± 4.39 |
| pting | input-pting | 23.0 ± 0.6 | 22.2 | 25.9 | 19.46 ± 4.38 |
| chancalan | input-chancalan | 23.4 ± 0.8 | 22.5 | 26.6 | 19.78 ± 4.46 |
| chancalan | input-mattcl | 23.6 ± 0.7 | 22.5 | 26.9 | 19.92 ± 4.49 |
| chancalan | input-lanjian | 24.2 ± 1.0 | 23.1 | 27.5 | 20.46 ± 4.64 |
| chancalan | input-kcen | 24.3 ± 0.8 | 23.3 | 27.1 | 20.51 ± 4.63 |
| chancalan | input-pting | 24.4 ± 0.7 | 23.2 | 27.1 | 20.64 ± 4.64 |
| kcen | input-chancalan | 28.0 ± 0.9 | 26.8 | 31.0 | 23.69 ± 5.34 |
| kcen | input-mattcl | 28.3 ± 0.9 | 27.0 | 31.0 | 23.88 ± 5.38 |
| kcen | input-lanjian | 29.2 ± 0.9 | 28.2 | 32.3 | 24.70 ± 5.56 |
| kcen | input-kcen | 29.3 ± 0.9 | 28.2 | 31.8 | 24.74 ± 5.57 |
| kcen | input-pting | 29.6 ± 0.8 | 28.4 | 32.0 | 25.02 ± 5.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|