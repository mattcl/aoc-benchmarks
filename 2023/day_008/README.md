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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.8 | 1.00 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.9 | 1.9 | 1.01 ± 0.30 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 2.0 | 1.02 ± 0.31 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.8 | 2.0 | 1.02 ± 0.30 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 2.1 | 1.02 ± 0.30 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.9 | 1.9 | 1.04 ± 0.29 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.9 | 2.0 | 1.04 ± 0.30 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.05 ± 0.31 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.09 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.1 | 1.15 ± 0.34 |
| mattcl-ts | input-chancalan | 14.8 ± 0.3 | 14.0 | 15.9 | 12.48 ± 2.70 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.3 | 16.3 | 12.68 ± 2.75 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.3 | 16.2 | 12.70 ± 2.75 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.3 | 16.5 | 12.70 ± 2.75 |
| mattcl-ts | input-mattcl | 15.3 ± 3.1 | 14.1 | 57.8 | 12.85 ± 3.81 |
| mattcl-py | input-chancalan | 21.8 ± 0.4 | 21.0 | 24.2 | 18.40 ± 3.99 |
| pting | input-chancalan | 22.1 ± 0.7 | 21.3 | 25.5 | 18.63 ± 4.06 |
| mattcl-py | input-mattcl | 22.2 ± 0.8 | 21.2 | 25.2 | 18.73 ± 4.09 |
| pting | input-mattcl | 22.3 ± 0.5 | 21.4 | 24.3 | 18.77 ± 4.07 |
| mattcl-py | input-lanjian | 22.6 ± 0.7 | 21.9 | 26.1 | 19.05 ± 4.15 |
| mattcl-py | input-kcen | 22.6 ± 0.6 | 21.8 | 25.4 | 19.06 ± 4.14 |
| mattcl-py | input-pting | 22.8 ± 0.7 | 21.9 | 25.7 | 19.23 ± 4.18 |
| pting | input-lanjian | 22.8 ± 0.9 | 21.9 | 25.8 | 19.24 ± 4.22 |
| pting | input-kcen | 22.8 ± 0.8 | 21.6 | 26.0 | 19.24 ± 4.20 |
| pting | input-pting | 23.0 ± 0.8 | 22.2 | 25.6 | 19.41 ± 4.24 |
| chancalan | input-chancalan | 23.5 ± 0.7 | 22.6 | 26.7 | 19.82 ± 4.32 |
| chancalan | input-mattcl | 23.6 ± 0.7 | 22.7 | 26.7 | 19.86 ± 4.32 |
| chancalan | input-lanjian | 24.2 ± 0.8 | 23.1 | 27.4 | 20.39 ± 4.45 |
| chancalan | input-kcen | 24.3 ± 0.8 | 23.2 | 27.1 | 20.50 ± 4.47 |
| chancalan | input-pting | 24.5 ± 0.8 | 23.5 | 27.7 | 20.67 ± 4.51 |
| kcen | input-chancalan | 27.8 ± 0.8 | 26.7 | 31.5 | 23.42 ± 5.09 |
| kcen | input-mattcl | 28.2 ± 1.0 | 27.0 | 30.9 | 23.78 ± 5.19 |
| kcen | input-lanjian | 28.9 ± 0.6 | 28.1 | 31.4 | 24.31 ± 5.27 |
| kcen | input-kcen | 29.2 ± 0.7 | 28.2 | 31.4 | 24.57 ± 5.33 |
| kcen | input-pting | 29.8 ± 1.0 | 28.3 | 33.1 | 25.10 ± 5.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|