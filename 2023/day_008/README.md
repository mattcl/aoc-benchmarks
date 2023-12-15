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
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.9 | 1.02 ± 0.31 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.9 | 1.9 | 1.03 ± 0.29 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.8 | 2.0 | 1.04 ± 0.30 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.9 | 2.0 | 1.05 ± 0.32 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.0 | 1.08 ± 0.32 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.0 | 1.09 ± 0.34 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.2 | 1.10 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.16 ± 0.34 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.2 | 1.19 ± 0.35 |
| mattcl-ts | input-chancalan | 14.6 ± 0.4 | 13.6 | 15.5 | 12.56 ± 2.69 |
| mattcl-ts | input-mattcl | 14.8 ± 0.4 | 13.5 | 15.6 | 12.70 ± 2.72 |
| mattcl-ts | input-pting | 14.9 ± 0.3 | 13.8 | 16.0 | 12.86 ± 2.75 |
| mattcl-ts | input-kcen | 15.2 ± 4.7 | 14.2 | 80.8 | 13.10 ± 4.89 |
| mattcl-ts | input-lanjian | 15.4 ± 5.1 | 14.0 | 71.6 | 13.29 ± 5.20 |
| pting | input-chancalan | 22.2 ± 0.8 | 21.0 | 25.7 | 19.07 ± 4.11 |
| mattcl-py | input-chancalan | 22.2 ± 0.8 | 21.1 | 25.2 | 19.14 ± 4.13 |
| mattcl-py | input-mattcl | 22.3 ± 1.1 | 21.2 | 32.7 | 19.21 ± 4.19 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.3 | 25.5 | 19.28 ± 4.15 |
| mattcl-py | input-lanjian | 22.7 ± 0.7 | 21.7 | 25.5 | 19.57 ± 4.21 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.8 | 26.8 | 19.69 ± 4.25 |
| mattcl-py | input-kcen | 23.0 ± 0.9 | 21.8 | 26.4 | 19.77 ± 4.28 |
| mattcl-py | input-pting | 23.1 ± 0.8 | 22.1 | 26.4 | 19.89 ± 4.29 |
| pting | input-pting | 23.2 ± 1.0 | 22.2 | 30.3 | 19.98 ± 4.35 |
| chancalan | input-chancalan | 23.5 ± 0.7 | 22.6 | 26.5 | 20.26 ± 4.36 |
| chancalan | input-mattcl | 23.6 ± 0.6 | 22.7 | 26.6 | 20.30 ± 4.36 |
| pting | input-kcen | 23.7 ± 4.9 | 22.1 | 68.9 | 20.39 ± 6.08 |
| chancalan | input-lanjian | 24.2 ± 0.7 | 23.3 | 27.0 | 20.83 ± 4.48 |
| chancalan | input-kcen | 24.5 ± 1.1 | 23.4 | 31.6 | 21.12 ± 4.59 |
| chancalan | input-pting | 24.9 ± 0.8 | 23.5 | 27.4 | 21.43 ± 4.62 |
| kcen | input-chancalan | 28.1 ± 0.9 | 26.9 | 31.1 | 24.14 ± 5.19 |
| kcen | input-mattcl | 28.3 ± 0.8 | 27.0 | 31.5 | 24.39 ± 5.24 |
| kcen | input-lanjian | 29.3 ± 0.8 | 28.1 | 32.3 | 25.17 ± 5.40 |
| kcen | input-kcen | 29.4 ± 0.8 | 28.5 | 32.5 | 25.30 ± 5.43 |
| kcen | input-pting | 29.7 ± 0.8 | 28.6 | 33.3 | 25.57 ± 5.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|