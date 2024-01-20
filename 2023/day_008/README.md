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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.00 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.9 | 1.00 ± 0.32 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.8 | 1.02 ± 0.30 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 2.0 | 1.03 ± 0.30 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.05 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.9 | 1.05 ± 0.32 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.9 | 1.06 ± 0.32 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.9 | 2.0 | 1.08 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.11 ± 0.32 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.16 ± 0.35 |
| mattcl-ts | input-chancalan | 14.4 ± 0.4 | 13.2 | 15.4 | 12.49 ± 2.68 |
| mattcl-ts | input-mattcl | 14.6 ± 0.4 | 13.5 | 15.6 | 12.62 ± 2.72 |
| mattcl-ts | input-lanjian | 14.7 ± 0.4 | 13.9 | 15.9 | 12.77 ± 2.74 |
| mattcl-ts | input-kcen | 14.7 ± 0.4 | 13.7 | 15.9 | 12.77 ± 2.74 |
| mattcl-ts | input-pting | 14.8 ± 0.4 | 13.6 | 16.1 | 12.85 ± 2.76 |
| mattcl-py | input-chancalan | 22.2 ± 0.8 | 20.7 | 24.9 | 19.24 ± 4.16 |
| pting | input-mattcl | 22.3 ± 0.7 | 21.4 | 26.0 | 19.37 ± 4.17 |
| pting | input-chancalan | 22.3 ± 0.8 | 21.3 | 25.0 | 19.39 ± 4.19 |
| mattcl-py | input-mattcl | 22.5 ± 0.8 | 21.5 | 25.8 | 19.49 ± 4.22 |
| pting | input-lanjian | 22.9 ± 0.9 | 21.7 | 26.6 | 19.87 ± 4.31 |
| pting | input-kcen | 22.9 ± 0.8 | 21.5 | 25.9 | 19.88 ± 4.30 |
| mattcl-py | input-lanjian | 22.9 ± 0.9 | 21.7 | 26.0 | 19.90 ± 4.32 |
| mattcl-py | input-kcen | 23.0 ± 0.8 | 21.9 | 26.7 | 19.91 ± 4.30 |
| mattcl-py | input-pting | 23.1 ± 1.2 | 21.6 | 33.1 | 20.01 ± 4.38 |
| pting | input-pting | 23.1 ± 0.7 | 21.8 | 25.8 | 20.04 ± 4.32 |
| chancalan | input-chancalan | 23.5 ± 0.7 | 22.5 | 25.9 | 20.41 ± 4.40 |
| chancalan | input-mattcl | 23.8 ± 0.8 | 22.8 | 26.6 | 20.64 ± 4.46 |
| chancalan | input-lanjian | 24.2 ± 0.8 | 23.2 | 26.8 | 21.02 ± 4.53 |
| chancalan | input-kcen | 24.4 ± 0.7 | 23.2 | 27.6 | 21.18 ± 4.56 |
| chancalan | input-pting | 24.5 ± 0.8 | 23.3 | 27.3 | 21.25 ± 4.58 |
| kcen | input-chancalan | 28.3 ± 0.9 | 27.1 | 31.7 | 24.52 ± 5.29 |
| kcen | input-mattcl | 28.5 ± 0.8 | 27.3 | 30.8 | 24.70 ± 5.31 |
| kcen | input-lanjian | 29.5 ± 0.9 | 28.1 | 32.7 | 25.57 ± 5.51 |
| kcen | input-kcen | 29.6 ± 0.8 | 28.3 | 32.5 | 25.64 ± 5.51 |
| kcen | input-pting | 30.0 ± 1.0 | 28.4 | 33.3 | 26.02 ± 5.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|