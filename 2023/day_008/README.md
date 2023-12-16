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
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.8 | 1.04 ± 0.32 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.8 | 1.07 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.3 | 1.07 ± 0.33 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.8 | 1.08 ± 0.33 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 3.0 | 1.09 ± 0.35 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.2 | 1.11 ± 0.36 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 2.0 | 1.14 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.17 ± 0.35 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.2 | 1.21 ± 0.37 |
| mattcl-ts | input-chancalan | 14.8 ± 0.4 | 13.9 | 17.0 | 13.30 ± 2.87 |
| mattcl-ts | input-mattcl | 14.9 ± 0.3 | 13.9 | 15.8 | 13.40 ± 2.88 |
| mattcl-ts | input-kcen | 15.0 ± 0.3 | 14.2 | 16.5 | 13.44 ± 2.89 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.2 | 16.3 | 13.47 ± 2.90 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.1 | 16.3 | 13.51 ± 2.90 |
| mattcl-py | input-chancalan | 22.0 ± 0.8 | 21.1 | 24.7 | 19.69 ± 4.27 |
| pting | input-chancalan | 22.0 ± 0.8 | 20.8 | 25.0 | 19.74 ± 4.29 |
| pting | input-mattcl | 22.1 ± 0.5 | 21.2 | 24.8 | 19.86 ± 4.28 |
| mattcl-py | input-lanjian | 22.5 ± 0.7 | 21.6 | 26.2 | 20.18 ± 4.36 |
| mattcl-py | input-kcen | 22.6 ± 0.8 | 21.4 | 26.3 | 20.23 ± 4.38 |
| pting | input-lanjian | 22.6 ± 0.8 | 21.8 | 25.6 | 20.31 ± 4.41 |
| pting | input-kcen | 22.7 ± 0.7 | 21.6 | 26.0 | 20.31 ± 4.39 |
| mattcl-py | input-mattcl | 22.7 ± 3.2 | 20.9 | 45.5 | 20.36 ± 5.22 |
| mattcl-py | input-pting | 22.8 ± 0.7 | 21.9 | 25.6 | 20.48 ± 4.43 |
| pting | input-pting | 23.0 ± 0.8 | 21.9 | 28.3 | 20.64 ± 4.48 |
| chancalan | input-chancalan | 23.2 ± 0.7 | 22.1 | 26.0 | 20.84 ± 4.50 |
| chancalan | input-mattcl | 23.6 ± 0.6 | 22.6 | 26.7 | 21.13 ± 4.56 |
| chancalan | input-kcen | 24.1 ± 0.8 | 23.1 | 28.0 | 21.64 ± 4.69 |
| chancalan | input-lanjian | 24.2 ± 0.8 | 23.2 | 27.0 | 21.67 ± 4.70 |
| chancalan | input-pting | 24.5 ± 0.9 | 23.0 | 28.1 | 21.96 ± 4.77 |
| kcen | input-chancalan | 27.7 ± 0.9 | 26.6 | 30.8 | 24.85 ± 5.38 |
| kcen | input-mattcl | 28.0 ± 0.8 | 26.7 | 30.4 | 25.10 ± 5.42 |
| kcen | input-lanjian | 28.8 ± 0.7 | 27.7 | 31.8 | 25.81 ± 5.56 |
| kcen | input-kcen | 29.1 ± 0.9 | 27.9 | 31.8 | 26.11 ± 5.65 |
| kcen | input-pting | 29.4 ± 0.8 | 28.1 | 31.9 | 26.33 ± 5.68 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|