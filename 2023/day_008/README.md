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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.8 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.9 | 1.9 | 1.04 ± 0.29 |
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.9 | 1.9 | 1.04 ± 0.30 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.04 ± 0.30 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.1 | 1.04 ± 0.31 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.0 | 1.05 ± 0.30 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 1.9 | 1.07 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 2.1 | 1.07 ± 0.29 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.0 | 2.2 | 1.14 ± 0.31 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.3 | 1.15 ± 0.32 |
| mattcl-ts | input-chancalan | 15.1 ± 0.3 | 14.3 | 16.2 | 12.37 ± 2.53 |
| mattcl-ts | input-mattcl | 15.2 ± 0.4 | 14.4 | 16.5 | 12.48 ± 2.56 |
| mattcl-ts | input-kcen | 15.3 ± 0.6 | 14.5 | 21.6 | 12.57 ± 2.61 |
| mattcl-ts | input-lanjian | 15.4 ± 0.4 | 14.3 | 17.0 | 12.59 ± 2.58 |
| mattcl-ts | input-pting | 15.5 ± 0.4 | 14.6 | 16.9 | 12.66 ± 2.61 |
| mattcl-py | input-chancalan | 22.2 ± 0.7 | 21.2 | 24.8 | 18.19 ± 3.75 |
| pting | input-chancalan | 22.3 ± 0.8 | 21.2 | 25.4 | 18.24 ± 3.77 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.3 | 25.8 | 18.34 ± 3.78 |
| mattcl-py | input-mattcl | 22.5 ± 0.9 | 21.5 | 25.5 | 18.41 ± 3.82 |
| pting | input-lanjian | 22.9 ± 0.7 | 21.8 | 25.8 | 18.74 ± 3.86 |
| mattcl-py | input-lanjian | 22.9 ± 0.8 | 21.7 | 26.1 | 18.76 ± 3.88 |
| mattcl-py | input-kcen | 22.9 ± 0.7 | 21.7 | 25.9 | 18.80 ± 3.87 |
| pting | input-pting | 23.2 ± 0.7 | 22.1 | 26.1 | 19.00 ± 3.92 |
| mattcl-py | input-pting | 23.2 ± 0.8 | 22.2 | 26.2 | 19.03 ± 3.93 |
| chancalan | input-chancalan | 23.6 ± 0.9 | 22.3 | 26.7 | 19.35 ± 4.01 |
| chancalan | input-mattcl | 24.0 ± 0.8 | 22.7 | 26.6 | 19.65 ± 4.05 |
| pting | input-kcen | 24.3 ± 6.4 | 21.9 | 69.8 | 19.96 ± 6.61 |
| chancalan | input-lanjian | 24.4 ± 0.9 | 23.3 | 27.7 | 19.98 ± 4.13 |
| chancalan | input-kcen | 24.4 ± 0.8 | 23.3 | 27.9 | 20.00 ± 4.13 |
| chancalan | input-pting | 24.6 ± 0.9 | 23.6 | 30.0 | 20.20 ± 4.17 |
| kcen | input-chancalan | 28.0 ± 0.8 | 26.9 | 31.0 | 22.94 ± 4.72 |
| kcen | input-mattcl | 28.4 ± 0.8 | 27.0 | 31.0 | 23.25 ± 4.78 |
| kcen | input-kcen | 29.5 ± 1.0 | 27.7 | 32.2 | 24.20 ± 5.00 |
| kcen | input-lanjian | 29.6 ± 2.3 | 28.1 | 49.7 | 24.28 ± 5.30 |
| kcen | input-pting | 29.7 ± 0.9 | 28.5 | 32.7 | 24.31 ± 5.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|