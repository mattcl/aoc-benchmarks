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
| mattcl | input-lanjian | 1.3 ± 0.2 | 1.0 | 1.9 | 1.02 ± 0.28 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.9 | 1.9 | 1.04 ± 0.29 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.9 | 2.1 | 1.05 ± 0.29 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.9 | 2.0 | 1.08 ± 0.30 |
| mattcl | input-pting | 1.4 ± 0.3 | 1.0 | 2.1 | 1.09 ± 0.30 |
| mattcl | input-kcen | 1.4 ± 0.3 | 1.0 | 2.0 | 1.10 ± 0.30 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.0 | 2.0 | 1.12 ± 0.30 |
| lanjian | input-kcen | 1.5 ± 0.3 | 1.0 | 2.3 | 1.17 ± 0.33 |
| lanjian | input-lanjian | 1.5 ± 2.7 | 1.0 | 39.2 | 1.21 ± 2.18 |
| mattcl-ts | input-chancalan | 15.0 ± 0.3 | 14.1 | 15.9 | 12.05 ± 2.42 |
| mattcl-ts | input-mattcl | 15.1 ± 0.3 | 14.2 | 15.9 | 12.12 ± 2.44 |
| mattcl-ts | input-lanjian | 15.2 ± 0.3 | 14.5 | 16.1 | 12.21 ± 2.45 |
| mattcl-ts | input-kcen | 15.2 ± 0.3 | 14.6 | 17.1 | 12.21 ± 2.46 |
| mattcl-ts | input-pting | 15.2 ± 0.3 | 14.6 | 16.4 | 12.24 ± 2.46 |
| pting | input-chancalan | 22.3 ± 0.6 | 21.2 | 25.0 | 17.91 ± 3.62 |
| mattcl-py | input-chancalan | 22.3 ± 0.8 | 21.3 | 25.3 | 17.93 ± 3.64 |
| pting | input-mattcl | 22.5 ± 0.7 | 21.3 | 25.8 | 18.06 ± 3.66 |
| mattcl-py | input-lanjian | 22.7 ± 0.7 | 21.9 | 26.0 | 18.24 ± 3.69 |
| pting | input-kcen | 22.8 ± 0.7 | 21.9 | 26.7 | 18.31 ± 3.70 |
| mattcl-py | input-mattcl | 22.9 ± 4.6 | 21.4 | 74.9 | 18.38 ± 5.21 |
| mattcl-py | input-kcen | 23.0 ± 0.7 | 22.0 | 25.8 | 18.50 ± 3.75 |
| pting | input-lanjian | 23.0 ± 0.9 | 21.9 | 26.1 | 18.51 ± 3.77 |
| pting | input-pting | 23.1 ± 0.7 | 22.1 | 26.5 | 18.56 ± 3.76 |
| mattcl-py | input-pting | 23.2 ± 0.8 | 22.0 | 26.0 | 18.64 ± 3.79 |
| chancalan | input-chancalan | 23.7 ± 0.7 | 22.9 | 26.5 | 19.06 ± 3.86 |
| chancalan | input-mattcl | 23.8 ± 0.7 | 22.8 | 27.0 | 19.11 ± 3.86 |
| chancalan | input-lanjian | 24.3 ± 0.6 | 23.1 | 27.2 | 19.53 ± 3.94 |
| chancalan | input-kcen | 24.5 ± 0.9 | 23.6 | 30.3 | 19.73 ± 4.02 |
| chancalan | input-pting | 24.7 ± 0.6 | 23.7 | 27.3 | 19.84 ± 4.00 |
| kcen | input-chancalan | 28.2 ± 0.8 | 27.2 | 31.1 | 22.69 ± 4.59 |
| kcen | input-mattcl | 28.4 ± 0.7 | 27.3 | 30.9 | 22.87 ± 4.61 |
| kcen | input-kcen | 29.4 ± 0.7 | 28.3 | 31.4 | 23.62 ± 4.76 |
| kcen | input-lanjian | 29.7 ± 3.1 | 28.0 | 60.4 | 23.86 ± 5.40 |
| kcen | input-pting | 29.9 ± 0.8 | 28.3 | 32.6 | 24.01 ± 4.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|