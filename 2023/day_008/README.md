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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.9 | 1.9 | 1.00 ± 0.29 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.9 | 1.02 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 2.0 | 1.04 ± 0.31 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.07 ± 0.33 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.1 | 1.08 ± 0.32 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.0 | 1.09 ± 0.34 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.10 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.13 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.9 | 2.1 | 1.14 ± 0.32 |
| mattcl-ts | input-chancalan | 15.0 ± 0.4 | 14.2 | 16.3 | 12.75 ± 2.80 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.4 | 16.3 | 12.84 ± 2.81 |
| mattcl-ts | input-lanjian | 15.2 ± 0.4 | 14.6 | 16.3 | 12.92 ± 2.83 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 14.5 | 17.1 | 12.96 ± 2.85 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.7 | 17.3 | 12.99 ± 2.85 |
| mattcl-py | input-chancalan | 22.2 ± 0.6 | 21.3 | 24.6 | 18.85 ± 4.14 |
| pting | input-chancalan | 22.3 ± 0.7 | 21.0 | 25.2 | 18.91 ± 4.16 |
| pting | input-mattcl | 22.5 ± 0.7 | 21.2 | 25.4 | 19.05 ± 4.19 |
| mattcl-py | input-lanjian | 22.8 ± 0.7 | 21.8 | 25.6 | 19.34 ± 4.25 |
| pting | input-kcen | 23.0 ± 0.9 | 21.9 | 25.9 | 19.47 ± 4.31 |
| mattcl-py | input-mattcl | 23.0 ± 5.4 | 21.7 | 82.8 | 19.54 ± 6.22 |
| pting | input-lanjian | 23.1 ± 0.9 | 21.7 | 25.8 | 19.58 ± 4.33 |
| mattcl-py | input-kcen | 23.2 ± 0.9 | 22.0 | 26.2 | 19.66 ± 4.35 |
| pting | input-pting | 23.2 ± 0.8 | 21.6 | 26.1 | 19.66 ± 4.34 |
| mattcl-py | input-pting | 23.2 ± 0.7 | 21.8 | 26.0 | 19.69 ± 4.33 |
| chancalan | input-chancalan | 23.5 ± 0.6 | 22.6 | 26.0 | 19.94 ± 4.37 |
| chancalan | input-mattcl | 24.0 ± 1.0 | 22.8 | 27.2 | 20.36 ± 4.51 |
| chancalan | input-kcen | 24.6 ± 0.9 | 22.7 | 27.4 | 20.82 ± 4.60 |
| chancalan | input-lanjian | 24.6 ± 0.9 | 23.4 | 27.5 | 20.82 ± 4.60 |
| chancalan | input-pting | 25.0 ± 0.9 | 23.7 | 28.4 | 21.16 ± 4.68 |
| kcen | input-chancalan | 28.0 ± 1.0 | 26.8 | 34.1 | 23.76 ± 5.25 |
| kcen | input-mattcl | 28.4 ± 0.7 | 27.2 | 30.9 | 24.06 ± 5.28 |
| kcen | input-kcen | 29.3 ± 0.8 | 28.3 | 32.3 | 24.87 ± 5.46 |
| kcen | input-lanjian | 29.4 ± 0.8 | 28.2 | 32.2 | 24.96 ± 5.48 |
| kcen | input-pting | 29.7 ± 0.9 | 28.3 | 33.1 | 25.22 ± 5.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|