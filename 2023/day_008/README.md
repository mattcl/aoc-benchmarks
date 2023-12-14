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
| mattcl | input-chancalan | 1.1 ± 0.3 | 0.8 | 1.9 | 1.04 ± 0.35 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.8 | 1.06 ± 0.33 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.9 | 1.07 ± 0.35 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.8 | 1.9 | 1.08 ± 0.34 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.8 | 1.08 ± 0.35 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.8 | 2.0 | 1.12 ± 0.35 |
| mattcl | input-lanjian | 1.3 ± 1.6 | 0.8 | 23.7 | 1.15 ± 1.50 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.8 | 1.9 | 1.16 ± 0.36 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.16 ± 0.36 |
| mattcl-ts | input-chancalan | 14.4 ± 0.4 | 13.5 | 15.4 | 13.21 ± 3.09 |
| mattcl-ts | input-mattcl | 14.6 ± 0.4 | 13.6 | 15.7 | 13.40 ± 3.14 |
| mattcl-ts | input-kcen | 14.7 ± 0.3 | 13.8 | 15.8 | 13.50 ± 3.16 |
| mattcl-ts | input-lanjian | 14.8 ± 0.3 | 13.7 | 15.9 | 13.54 ± 3.17 |
| mattcl-ts | input-pting | 14.9 ± 0.3 | 13.9 | 15.7 | 13.61 ± 3.18 |
| pting | input-chancalan | 22.1 ± 0.8 | 21.0 | 25.3 | 20.21 ± 4.75 |
| mattcl-py | input-chancalan | 22.2 ± 0.9 | 21.1 | 25.2 | 20.30 ± 4.79 |
| pting | input-mattcl | 22.3 ± 0.9 | 21.3 | 28.4 | 20.39 ± 4.81 |
| mattcl-py | input-mattcl | 22.3 ± 0.8 | 21.0 | 25.8 | 20.40 ± 4.80 |
| mattcl-py | input-kcen | 22.7 ± 0.8 | 21.7 | 26.1 | 20.75 ± 4.88 |
| pting | input-kcen | 22.7 ± 0.8 | 21.9 | 26.6 | 20.80 ± 4.89 |
| pting | input-lanjian | 22.8 ± 0.9 | 21.5 | 26.5 | 20.90 ± 4.93 |
| pting | input-pting | 22.8 ± 0.6 | 21.8 | 26.4 | 20.93 ± 4.90 |
| mattcl-py | input-pting | 23.0 ± 0.8 | 21.9 | 26.1 | 21.09 ± 4.96 |
| mattcl-py | input-lanjian | 23.1 ± 3.5 | 21.8 | 53.4 | 21.16 ± 5.88 |
| chancalan | input-chancalan | 23.4 ± 0.9 | 22.2 | 26.7 | 21.46 ± 5.06 |
| chancalan | input-mattcl | 23.6 ± 0.6 | 22.9 | 26.2 | 21.60 ± 5.06 |
| chancalan | input-kcen | 24.1 ± 0.7 | 22.9 | 27.7 | 22.10 ± 5.18 |
| chancalan | input-lanjian | 24.2 ± 0.9 | 23.1 | 26.9 | 22.17 ± 5.22 |
| chancalan | input-pting | 24.6 ± 0.8 | 23.5 | 27.3 | 22.50 ± 5.28 |
| kcen | input-chancalan | 27.7 ± 0.7 | 26.6 | 30.3 | 25.37 ± 5.94 |
| kcen | input-mattcl | 28.2 ± 0.9 | 27.1 | 31.6 | 25.81 ± 6.06 |
| kcen | input-lanjian | 29.3 ± 4.7 | 28.0 | 75.8 | 26.86 ± 7.59 |
| kcen | input-kcen | 29.4 ± 0.9 | 28.2 | 32.4 | 26.91 ± 6.32 |
| kcen | input-pting | 29.6 ± 0.9 | 28.4 | 32.3 | 27.16 ± 6.37 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|