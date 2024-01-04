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
| mattcl | input-mattcl | 1.3 ± 0.2 | 1.0 | 2.0 | 1.00 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 1.0 | 2.0 | 1.00 ± 0.27 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 1.0 | 2.0 | 1.01 ± 0.27 |
| mattcl | input-lanjian | 1.4 ± 0.3 | 1.0 | 2.0 | 1.03 ± 0.28 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 1.0 | 2.2 | 1.03 ± 0.27 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.0 | 1.04 ± 0.27 |
| mattcl | input-pting | 1.4 ± 0.3 | 1.0 | 2.0 | 1.05 ± 0.28 |
| lanjian | input-lanjian | 1.4 ± 0.3 | 1.0 | 2.2 | 1.09 ± 0.30 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.0 | 2.0 | 1.10 ± 0.29 |
| lanjian | input-kcen | 1.5 ± 0.3 | 1.0 | 2.3 | 1.12 ± 0.30 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.1 | 16.3 | 11.54 ± 2.21 |
| mattcl-ts | input-kcen | 15.3 ± 0.3 | 14.4 | 16.4 | 11.68 ± 2.23 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.5 | 16.9 | 11.69 ± 2.23 |
| mattcl-ts | input-pting | 15.4 ± 0.4 | 14.6 | 16.9 | 11.74 ± 2.25 |
| mattcl-ts | input-chancalan | 15.9 ± 4.8 | 14.0 | 54.1 | 12.11 ± 4.29 |
| mattcl-py | input-chancalan | 22.3 ± 0.8 | 21.2 | 25.1 | 16.98 ± 3.27 |
| mattcl-py | input-mattcl | 22.4 ± 0.7 | 21.4 | 26.4 | 17.10 ± 3.29 |
| pting | input-mattcl | 22.5 ± 0.8 | 21.2 | 25.5 | 17.15 ± 3.31 |
| pting | input-lanjian | 22.8 ± 0.7 | 21.9 | 25.9 | 17.40 ± 3.34 |
| pting | input-kcen | 22.8 ± 0.7 | 21.8 | 26.0 | 17.41 ± 3.34 |
| mattcl-py | input-kcen | 22.9 ± 0.7 | 21.5 | 25.9 | 17.44 ± 3.35 |
| pting | input-chancalan | 23.0 ± 6.2 | 20.8 | 70.3 | 17.52 ± 5.76 |
| mattcl-py | input-lanjian | 23.0 ± 0.8 | 21.7 | 26.0 | 17.52 ± 3.37 |
| mattcl-py | input-pting | 23.2 ± 0.6 | 22.0 | 25.8 | 17.70 ± 3.39 |
| pting | input-pting | 23.2 ± 0.8 | 22.0 | 26.2 | 17.71 ± 3.41 |
| chancalan | input-chancalan | 23.7 ± 1.3 | 22.4 | 34.6 | 18.07 ± 3.56 |
| chancalan | input-mattcl | 23.8 ± 0.7 | 22.5 | 26.8 | 18.13 ± 3.48 |
| chancalan | input-lanjian | 24.3 ± 0.7 | 23.0 | 27.7 | 18.54 ± 3.56 |
| chancalan | input-pting | 24.7 ± 0.7 | 23.6 | 27.8 | 18.83 ± 3.61 |
| chancalan | input-kcen | 24.9 ± 3.7 | 22.9 | 54.2 | 18.96 ± 4.55 |
| kcen | input-chancalan | 27.9 ± 0.7 | 26.9 | 30.5 | 21.31 ± 4.07 |
| kcen | input-mattcl | 28.4 ± 0.9 | 26.9 | 32.3 | 21.64 ± 4.16 |
| kcen | input-lanjian | 29.3 ± 0.9 | 28.1 | 32.4 | 22.39 ± 4.30 |
| kcen | input-kcen | 29.8 ± 4.1 | 28.0 | 70.2 | 22.71 ± 5.33 |
| kcen | input-pting | 29.8 ± 0.8 | 28.4 | 32.4 | 22.75 ± 4.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|