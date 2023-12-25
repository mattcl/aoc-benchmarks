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
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 2.0 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.9 | 1.8 | 1.00 ± 0.29 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.9 | 2.0 | 1.01 ± 0.28 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.9 | 1.9 | 1.02 ± 0.28 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.9 | 1.9 | 1.02 ± 0.28 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.9 | 1.9 | 1.03 ± 0.27 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 2.0 | 1.06 ± 0.28 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.06 ± 0.30 |
| lanjian | input-kcen | 1.3 ± 0.3 | 1.0 | 2.1 | 1.09 ± 0.30 |
| lanjian | input-pting | 1.4 ± 0.2 | 1.0 | 2.3 | 1.10 ± 0.29 |
| mattcl-ts | input-chancalan | 14.6 ± 0.3 | 13.8 | 15.7 | 11.83 ± 2.26 |
| mattcl-ts | input-mattcl | 14.9 ± 0.4 | 13.7 | 15.9 | 12.03 ± 2.30 |
| mattcl-ts | input-kcen | 14.9 ± 0.3 | 13.9 | 16.1 | 12.10 ± 2.31 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.1 | 16.2 | 12.11 ± 2.31 |
| mattcl-ts | input-pting | 15.0 ± 0.3 | 14.2 | 16.2 | 12.16 ± 2.32 |
| mattcl-py | input-chancalan | 21.9 ± 0.7 | 21.1 | 24.7 | 17.72 ± 3.40 |
| pting | input-chancalan | 22.0 ± 0.8 | 21.1 | 25.7 | 17.82 ± 3.44 |
| mattcl-py | input-mattcl | 22.1 ± 1.1 | 21.1 | 32.4 | 17.92 ± 3.51 |
| pting | input-mattcl | 22.3 ± 0.8 | 21.3 | 25.4 | 18.03 ± 3.48 |
| mattcl-py | input-lanjian | 22.4 ± 0.5 | 21.6 | 25.5 | 18.12 ± 3.46 |
| pting | input-kcen | 22.6 ± 0.8 | 21.5 | 26.4 | 18.30 ± 3.53 |
| mattcl-py | input-kcen | 22.6 ± 0.7 | 21.7 | 25.8 | 18.30 ± 3.52 |
| pting | input-lanjian | 22.6 ± 0.6 | 21.8 | 25.5 | 18.31 ± 3.51 |
| pting | input-pting | 22.9 ± 0.8 | 21.9 | 26.2 | 18.52 ± 3.57 |
| mattcl-py | input-pting | 22.9 ± 0.9 | 21.8 | 27.7 | 18.56 ± 3.59 |
| chancalan | input-chancalan | 23.3 ± 0.7 | 22.2 | 26.2 | 18.88 ± 3.63 |
| chancalan | input-mattcl | 23.6 ± 0.7 | 22.7 | 26.5 | 19.13 ± 3.68 |
| chancalan | input-lanjian | 24.0 ± 0.9 | 23.1 | 27.1 | 19.45 ± 3.76 |
| chancalan | input-kcen | 24.1 ± 0.7 | 23.0 | 27.0 | 19.48 ± 3.74 |
| chancalan | input-pting | 24.4 ± 0.8 | 23.4 | 27.1 | 19.75 ± 3.81 |
| kcen | input-chancalan | 27.7 ± 1.0 | 26.5 | 31.1 | 22.40 ± 4.32 |
| kcen | input-mattcl | 28.6 ± 4.7 | 27.1 | 74.0 | 23.15 ± 5.78 |
| kcen | input-lanjian | 28.9 ± 0.8 | 27.8 | 31.9 | 23.42 ± 4.49 |
| kcen | input-kcen | 28.9 ± 0.8 | 27.8 | 31.7 | 23.44 ± 4.49 |
| kcen | input-pting | 29.3 ± 0.9 | 28.2 | 32.9 | 23.75 ± 4.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|