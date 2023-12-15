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
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 2.1 | 1.00 |
| mattcl | input-pting | 1.4 ± 0.2 | 1.1 | 2.1 | 1.01 ± 0.24 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 2.1 | 1.02 ± 0.23 |
| mattcl | input-chancalan | 1.4 ± 0.2 | 1.1 | 2.1 | 1.02 ± 0.24 |
| mattcl | input-kcen | 1.5 ± 0.2 | 1.1 | 2.1 | 1.03 ± 0.24 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.2 | 1.04 ± 0.24 |
| lanjian | input-chancalan | 1.5 ± 0.2 | 1.2 | 2.4 | 1.06 ± 0.24 |
| lanjian | input-pting | 1.5 ± 0.2 | 1.1 | 2.4 | 1.07 ± 0.24 |
| lanjian | input-lanjian | 1.5 ± 0.3 | 1.1 | 3.0 | 1.08 ± 0.26 |
| lanjian | input-kcen | 1.6 ± 0.2 | 1.2 | 2.4 | 1.10 ± 0.25 |
| mattcl-ts | input-kcen | 15.5 ± 0.4 | 14.5 | 17.0 | 10.97 ± 1.86 |
| mattcl-ts | input-pting | 15.7 ± 0.4 | 14.8 | 17.2 | 11.11 ± 1.89 |
| mattcl-ts | input-mattcl | 16.4 ± 4.9 | 14.4 | 60.5 | 11.58 ± 3.98 |
| mattcl-ts | input-chancalan | 17.2 ± 6.9 | 14.5 | 53.2 | 12.13 ± 5.26 |
| mattcl-ts | input-lanjian | 17.5 ± 8.4 | 14.7 | 79.5 | 12.37 ± 6.26 |
| pting | input-chancalan | 22.7 ± 0.6 | 21.8 | 24.8 | 16.00 ± 2.72 |
| mattcl-py | input-chancalan | 22.8 ± 0.7 | 21.5 | 25.7 | 16.07 ± 2.74 |
| pting | input-lanjian | 23.1 ± 0.6 | 22.0 | 26.2 | 16.32 ± 2.78 |
| mattcl-py | input-mattcl | 23.1 ± 0.9 | 22.0 | 28.0 | 16.32 ± 2.81 |
| mattcl-py | input-kcen | 23.4 ± 0.8 | 22.2 | 28.6 | 16.52 ± 2.83 |
| pting | input-kcen | 23.7 ± 2.4 | 22.3 | 38.4 | 16.71 ± 3.27 |
| pting | input-pting | 23.9 ± 0.7 | 22.9 | 26.2 | 16.86 ± 2.87 |
| mattcl-py | input-lanjian | 24.0 ± 3.0 | 22.4 | 48.6 | 16.92 ± 3.55 |
| chancalan | input-chancalan | 24.3 ± 0.7 | 23.0 | 26.6 | 17.18 ± 2.93 |
| chancalan | input-pting | 25.0 ± 0.8 | 23.8 | 30.6 | 17.62 ± 3.01 |
| chancalan | input-kcen | 25.1 ± 1.5 | 23.8 | 36.1 | 17.68 ± 3.16 |
| chancalan | input-mattcl | 25.2 ± 5.4 | 23.3 | 75.4 | 17.77 ± 4.84 |
| mattcl-py | input-pting | 25.3 ± 4.4 | 22.5 | 37.6 | 17.84 ± 4.29 |
| pting | input-mattcl | 25.4 ± 5.9 | 21.8 | 44.0 | 17.95 ± 5.13 |
| chancalan | input-lanjian | 27.0 ± 5.5 | 23.7 | 44.0 | 19.07 ± 5.02 |
| kcen | input-chancalan | 28.9 ± 0.8 | 27.5 | 31.9 | 20.38 ± 3.47 |
| kcen | input-lanjian | 30.2 ± 0.8 | 28.9 | 33.1 | 21.34 ± 3.63 |
| kcen | input-pting | 30.3 ± 1.0 | 29.0 | 35.4 | 21.38 ± 3.65 |
| kcen | input-mattcl | 31.6 ± 6.6 | 27.6 | 55.8 | 22.32 ± 5.98 |
| kcen | input-kcen | 32.2 ± 6.7 | 28.7 | 53.8 | 22.72 ± 6.07 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|