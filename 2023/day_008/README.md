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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.8 | 1.00 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.8 | 2.0 | 1.02 ± 0.30 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.9 | 1.04 ± 0.31 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.9 | 1.8 | 1.07 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.9 | 2.0 | 1.07 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.0 | 1.08 ± 0.32 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.2 | 1.08 ± 0.33 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.11 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.14 ± 0.33 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.1 | 1.18 ± 0.34 |
| mattcl-ts | input-chancalan | 14.6 ± 0.4 | 13.6 | 15.9 | 12.76 ± 2.75 |
| mattcl-ts | input-mattcl | 14.8 ± 0.4 | 13.8 | 15.7 | 12.88 ± 2.77 |
| mattcl-ts | input-lanjian | 14.9 ± 0.4 | 13.9 | 15.8 | 12.98 ± 2.79 |
| mattcl-ts | input-kcen | 14.9 ± 0.3 | 13.6 | 15.8 | 12.99 ± 2.79 |
| mattcl-ts | input-pting | 14.9 ± 0.3 | 13.7 | 15.8 | 13.04 ± 2.80 |
| mattcl-py | input-chancalan | 22.2 ± 0.7 | 21.3 | 25.4 | 19.35 ± 4.18 |
| pting | input-chancalan | 22.2 ± 0.8 | 21.1 | 25.0 | 19.38 ± 4.20 |
| mattcl-py | input-mattcl | 22.4 ± 0.7 | 21.4 | 26.0 | 19.51 ± 4.22 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.6 | 25.6 | 19.58 ± 4.24 |
| mattcl-py | input-lanjian | 22.7 ± 0.7 | 21.8 | 25.7 | 19.81 ± 4.29 |
| pting | input-lanjian | 22.7 ± 0.7 | 21.8 | 25.8 | 19.84 ± 4.28 |
| pting | input-kcen | 22.9 ± 0.9 | 21.7 | 25.9 | 20.01 ± 4.36 |
| mattcl-py | input-kcen | 23.0 ± 0.8 | 22.0 | 25.8 | 20.05 ± 4.34 |
| mattcl-py | input-pting | 23.0 ± 0.7 | 21.9 | 26.3 | 20.05 ± 4.33 |
| pting | input-pting | 23.5 ± 2.6 | 22.1 | 51.1 | 20.46 ± 4.95 |
| chancalan | input-chancalan | 23.5 ± 1.4 | 22.0 | 36.3 | 20.50 ± 4.56 |
| chancalan | input-mattcl | 23.5 ± 0.8 | 22.4 | 26.6 | 20.51 ± 4.44 |
| chancalan | input-lanjian | 23.9 ± 0.8 | 22.9 | 27.1 | 20.88 ± 4.52 |
| chancalan | input-kcen | 24.3 ± 2.1 | 22.9 | 44.1 | 21.22 ± 4.91 |
| chancalan | input-pting | 24.5 ± 0.9 | 23.4 | 27.7 | 21.36 ± 4.63 |
| kcen | input-chancalan | 28.1 ± 0.9 | 26.8 | 31.0 | 24.51 ± 5.30 |
| kcen | input-mattcl | 28.2 ± 0.8 | 27.1 | 31.5 | 24.62 ± 5.31 |
| kcen | input-lanjian | 29.3 ± 0.8 | 28.1 | 31.8 | 25.60 ± 5.52 |
| kcen | input-pting | 29.7 ± 0.8 | 28.6 | 32.3 | 25.91 ± 5.58 |
| kcen | input-kcen | 30.2 ± 5.9 | 28.2 | 88.5 | 26.33 ± 7.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|