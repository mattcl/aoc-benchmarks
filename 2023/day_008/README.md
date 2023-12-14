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
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 1.9 | 1.02 ± 0.30 |
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.8 | 2.0 | 1.03 ± 0.31 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.0 | 1.03 ± 0.31 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.04 ± 0.31 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.9 | 2.0 | 1.05 ± 0.30 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.08 ± 0.31 |
| lanjian | input-pting | 1.4 ± 0.3 | 0.9 | 2.1 | 1.11 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.2 | 1.12 ± 0.32 |
| mattcl-ts | input-chancalan | 15.1 ± 0.3 | 14.1 | 16.3 | 12.38 ± 2.62 |
| mattcl-ts | input-mattcl | 15.1 ± 0.3 | 14.3 | 16.0 | 12.41 ± 2.63 |
| mattcl-ts | input-kcen | 15.2 ± 0.4 | 14.5 | 16.5 | 12.50 ± 2.65 |
| mattcl-ts | input-lanjian | 15.2 ± 0.4 | 14.4 | 16.1 | 12.51 ± 2.65 |
| mattcl-ts | input-pting | 15.3 ± 0.3 | 14.5 | 16.1 | 12.55 ± 2.66 |
| pting | input-chancalan | 22.3 ± 0.8 | 21.1 | 25.1 | 18.31 ± 3.91 |
| mattcl-py | input-chancalan | 22.3 ± 0.8 | 21.0 | 26.9 | 18.35 ± 3.92 |
| pting | input-mattcl | 22.5 ± 1.1 | 21.1 | 30.9 | 18.48 ± 4.00 |
| mattcl-py | input-mattcl | 22.7 ± 3.6 | 21.3 | 63.4 | 18.66 ± 4.95 |
| mattcl-py | input-kcen | 22.8 ± 0.5 | 21.8 | 25.2 | 18.73 ± 3.97 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.8 | 26.4 | 18.81 ± 4.02 |
| pting | input-kcen | 22.9 ± 0.8 | 21.8 | 25.9 | 18.83 ± 4.02 |
| mattcl-py | input-lanjian | 23.0 ± 0.9 | 21.4 | 26.9 | 18.87 ± 4.04 |
| pting | input-pting | 23.1 ± 0.6 | 22.3 | 25.9 | 18.96 ± 4.03 |
| mattcl-py | input-pting | 23.3 ± 0.8 | 22.0 | 26.1 | 19.13 ± 4.09 |
| chancalan | input-chancalan | 23.6 ± 0.7 | 22.6 | 26.6 | 19.36 ± 4.12 |
| chancalan | input-mattcl | 23.7 ± 0.7 | 22.7 | 27.3 | 19.49 ± 4.15 |
| chancalan | input-lanjian | 24.3 ± 0.8 | 23.1 | 27.1 | 20.00 ± 4.26 |
| chancalan | input-kcen | 24.5 ± 0.8 | 23.2 | 27.4 | 20.13 ± 4.30 |
| chancalan | input-pting | 24.7 ± 0.8 | 23.2 | 27.4 | 20.25 ± 4.32 |
| kcen | input-mattcl | 28.2 ± 0.8 | 27.0 | 31.8 | 23.20 ± 4.93 |
| kcen | input-chancalan | 28.3 ± 1.3 | 26.8 | 36.4 | 23.28 ± 5.01 |
| kcen | input-lanjian | 29.3 ± 0.8 | 28.0 | 32.4 | 24.07 ± 5.12 |
| kcen | input-kcen | 29.4 ± 0.7 | 28.2 | 32.4 | 24.16 ± 5.13 |
| kcen | input-pting | 29.5 ± 0.8 | 28.1 | 32.3 | 24.26 ± 5.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|