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
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.9 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 2.1 | 1.00 ± 0.31 |
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.8 | 1.00 ± 0.32 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.9 | 1.9 | 1.02 ± 0.30 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 1.9 | 1.03 ± 0.32 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.8 | 1.03 ± 0.31 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.04 ± 0.32 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.09 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.11 ± 0.34 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.12 ± 0.33 |
| mattcl-ts | input-chancalan | 14.4 ± 0.3 | 13.5 | 15.4 | 12.35 ± 2.75 |
| mattcl-ts | input-mattcl | 14.7 ± 0.4 | 13.5 | 15.5 | 12.60 ± 2.81 |
| mattcl-ts | input-lanjian | 14.8 ± 0.3 | 13.8 | 15.8 | 12.71 ± 2.83 |
| mattcl-ts | input-kcen | 14.8 ± 0.4 | 13.6 | 15.5 | 12.71 ± 2.83 |
| mattcl-ts | input-pting | 14.8 ± 0.4 | 13.7 | 15.5 | 12.71 ± 2.83 |
| pting | input-chancalan | 21.9 ± 0.6 | 21.1 | 25.1 | 18.81 ± 4.19 |
| mattcl-py | input-chancalan | 22.2 ± 0.9 | 21.2 | 25.2 | 19.03 ± 4.29 |
| pting | input-mattcl | 22.2 ± 0.5 | 21.4 | 25.0 | 19.08 ± 4.25 |
| mattcl-py | input-mattcl | 22.3 ± 0.8 | 21.2 | 25.4 | 19.14 ± 4.29 |
| mattcl-py | input-lanjian | 22.5 ± 0.6 | 21.8 | 25.6 | 19.34 ± 4.31 |
| pting | input-kcen | 22.7 ± 0.8 | 21.8 | 25.8 | 19.53 ± 4.38 |
| mattcl-py | input-kcen | 22.8 ± 0.8 | 21.7 | 25.9 | 19.59 ± 4.39 |
| pting | input-lanjian | 22.9 ± 1.0 | 21.9 | 28.9 | 19.67 ± 4.44 |
| mattcl-py | input-pting | 23.1 ± 1.1 | 22.1 | 31.3 | 19.84 ± 4.49 |
| pting | input-pting | 23.1 ± 0.9 | 22.0 | 26.7 | 19.86 ± 4.47 |
| chancalan | input-chancalan | 23.4 ± 0.7 | 22.5 | 26.5 | 20.11 ± 4.50 |
| chancalan | input-mattcl | 23.8 ± 1.3 | 22.8 | 35.3 | 20.40 ± 4.66 |
| chancalan | input-lanjian | 24.2 ± 0.8 | 23.2 | 26.8 | 20.80 ± 4.66 |
| chancalan | input-kcen | 24.3 ± 0.9 | 23.2 | 29.8 | 20.84 ± 4.68 |
| chancalan | input-pting | 24.6 ± 1.0 | 23.6 | 30.7 | 21.14 ± 4.76 |
| kcen | input-chancalan | 27.9 ± 0.9 | 26.9 | 30.9 | 23.96 ± 5.36 |
| kcen | input-mattcl | 28.3 ± 0.8 | 27.1 | 31.2 | 24.28 ± 5.43 |
| kcen | input-kcen | 29.1 ± 0.8 | 27.9 | 31.9 | 25.03 ± 5.59 |
| kcen | input-lanjian | 29.2 ± 0.8 | 28.2 | 32.0 | 25.04 ± 5.59 |
| kcen | input-pting | 30.1 ± 3.1 | 28.4 | 52.4 | 25.84 ± 6.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|