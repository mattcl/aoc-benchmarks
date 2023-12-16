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
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.9 | 2.0 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.9 | 2.0 | 1.01 ± 0.30 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.9 | 1.9 | 1.03 ± 0.29 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.0 | 1.04 ± 0.32 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.9 | 1.9 | 1.04 ± 0.29 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.31 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.07 ± 0.30 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.08 ± 0.31 |
| lanjian | input-pting | 1.4 ± 0.3 | 0.9 | 2.2 | 1.12 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.3 | 1.14 ± 0.32 |
| mattcl-ts | input-chancalan | 15.1 ± 0.3 | 14.2 | 16.1 | 12.36 ± 2.58 |
| mattcl-ts | input-mattcl | 15.2 ± 0.4 | 14.1 | 17.0 | 12.51 ± 2.62 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 14.4 | 16.6 | 12.57 ± 2.63 |
| mattcl-ts | input-lanjian | 15.4 ± 0.4 | 14.4 | 17.2 | 12.61 ± 2.64 |
| mattcl-ts | input-pting | 15.4 ± 0.4 | 14.6 | 16.6 | 12.62 ± 2.64 |
| pting | input-chancalan | 22.3 ± 0.6 | 21.2 | 25.6 | 18.28 ± 3.83 |
| mattcl-py | input-chancalan | 22.3 ± 0.9 | 20.8 | 25.3 | 18.33 ± 3.88 |
| mattcl-py | input-mattcl | 22.5 ± 0.8 | 21.6 | 25.4 | 18.50 ± 3.90 |
| pting | input-mattcl | 22.6 ± 0.7 | 21.4 | 26.5 | 18.52 ± 3.89 |
| mattcl-py | input-lanjian | 22.9 ± 0.7 | 21.9 | 25.5 | 18.83 ± 3.95 |
| pting | input-lanjian | 22.9 ± 0.6 | 21.7 | 25.8 | 18.85 ± 3.95 |
| mattcl-py | input-kcen | 23.1 ± 0.7 | 21.8 | 26.0 | 18.94 ± 3.98 |
| mattcl-py | input-pting | 23.2 ± 0.7 | 21.9 | 26.4 | 19.05 ± 4.00 |
| pting | input-kcen | 23.4 ± 4.3 | 21.6 | 61.0 | 19.22 ± 5.33 |
| pting | input-pting | 23.5 ± 0.8 | 22.5 | 26.6 | 19.27 ± 4.05 |
| chancalan | input-chancalan | 23.7 ± 0.8 | 22.7 | 26.7 | 19.46 ± 4.10 |
| chancalan | input-mattcl | 24.0 ± 0.8 | 22.8 | 27.0 | 19.75 ± 4.16 |
| chancalan | input-kcen | 24.5 ± 0.8 | 23.4 | 27.4 | 20.11 ± 4.23 |
| chancalan | input-pting | 24.8 ± 0.8 | 23.6 | 27.8 | 20.37 ± 4.28 |
| chancalan | input-lanjian | 25.1 ± 4.8 | 23.4 | 66.1 | 20.65 ± 5.86 |
| kcen | input-chancalan | 28.2 ± 1.0 | 26.8 | 31.8 | 23.15 ± 4.88 |
| kcen | input-mattcl | 28.5 ± 0.9 | 27.3 | 31.5 | 23.42 ± 4.92 |
| kcen | input-lanjian | 29.4 ± 0.7 | 28.2 | 32.1 | 24.12 ± 5.04 |
| kcen | input-kcen | 29.5 ± 1.0 | 28.3 | 33.1 | 24.26 ± 5.11 |
| kcen | input-pting | 29.9 ± 0.9 | 28.2 | 32.7 | 24.55 ± 5.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|