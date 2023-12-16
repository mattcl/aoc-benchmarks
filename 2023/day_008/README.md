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
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.8 | 1.9 | 1.04 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.8 | 1.8 | 1.04 ± 0.32 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.8 | 1.04 ± 0.33 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.3 | 1.06 ± 0.34 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.9 | 1.9 | 1.08 ± 0.33 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.0 | 1.09 ± 0.35 |
| lanjian | input-pting | 1.2 ± 0.3 | 0.9 | 2.0 | 1.11 ± 0.35 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.16 ± 0.35 |
| mattcl-ts | input-chancalan | 14.8 ± 0.3 | 14.0 | 15.7 | 13.22 ± 3.00 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.1 | 15.8 | 13.35 ± 3.02 |
| mattcl-ts | input-kcen | 15.0 ± 0.3 | 13.9 | 16.0 | 13.41 ± 3.04 |
| mattcl-ts | input-lanjian | 15.0 ± 0.4 | 13.9 | 16.5 | 13.43 ± 3.04 |
| mattcl-ts | input-pting | 15.3 ± 3.9 | 14.2 | 68.6 | 13.67 ± 4.66 |
| mattcl-py | input-chancalan | 21.9 ± 0.8 | 21.1 | 26.5 | 19.58 ± 4.47 |
| pting | input-chancalan | 22.0 ± 0.6 | 21.2 | 24.8 | 19.66 ± 4.47 |
| pting | input-mattcl | 22.3 ± 0.8 | 21.3 | 25.4 | 19.88 ± 4.54 |
| mattcl-py | input-lanjian | 22.5 ± 0.7 | 21.7 | 25.7 | 20.13 ± 4.58 |
| mattcl-py | input-kcen | 22.6 ± 0.7 | 21.9 | 25.6 | 20.16 ± 4.58 |
| pting | input-kcen | 22.6 ± 0.7 | 21.5 | 25.4 | 20.18 ± 4.60 |
| pting | input-lanjian | 22.8 ± 1.4 | 21.7 | 34.7 | 20.35 ± 4.76 |
| pting | input-pting | 22.8 ± 0.7 | 22.0 | 25.6 | 20.39 ± 4.63 |
| mattcl-py | input-pting | 22.8 ± 0.7 | 21.9 | 25.7 | 20.40 ± 4.65 |
| chancalan | input-chancalan | 23.3 ± 0.7 | 22.1 | 26.1 | 20.76 ± 4.72 |
| mattcl-py | input-mattcl | 23.3 ± 6.6 | 21.0 | 71.7 | 20.77 ± 7.52 |
| chancalan | input-mattcl | 24.0 ± 4.0 | 22.5 | 67.0 | 21.40 ± 6.03 |
| chancalan | input-kcen | 24.0 ± 0.6 | 23.0 | 27.2 | 21.41 ± 4.86 |
| chancalan | input-lanjian | 24.1 ± 0.9 | 22.8 | 27.4 | 21.53 ± 4.92 |
| chancalan | input-pting | 24.5 ± 0.9 | 23.5 | 27.4 | 21.87 ± 4.99 |
| kcen | input-chancalan | 27.6 ± 0.9 | 26.6 | 31.0 | 24.68 ± 5.62 |
| kcen | input-mattcl | 28.0 ± 0.7 | 27.0 | 31.0 | 25.01 ± 5.68 |
| kcen | input-kcen | 28.9 ± 0.8 | 27.7 | 31.9 | 25.82 ± 5.86 |
| kcen | input-lanjian | 28.9 ± 0.8 | 27.7 | 32.1 | 25.83 ± 5.86 |
| kcen | input-pting | 29.3 ± 0.8 | 28.0 | 32.5 | 26.20 ± 5.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|