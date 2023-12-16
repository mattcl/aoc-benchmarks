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
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.9 | 2.1 | 1.04 ± 0.31 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.9 | 1.9 | 1.04 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 1.8 | 1.06 ± 0.31 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.9 | 1.9 | 1.07 ± 0.30 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.9 | 2.0 | 1.07 ± 0.31 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.1 | 1.07 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.10 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 2.2 | 1.12 ± 0.31 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.2 | 1.17 ± 0.33 |
| mattcl-ts | input-chancalan | 14.9 ± 0.3 | 14.2 | 15.7 | 12.69 ± 2.66 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.0 | 16.2 | 12.78 ± 2.68 |
| mattcl-ts | input-kcen | 15.0 ± 0.3 | 14.2 | 15.9 | 12.81 ± 2.68 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.3 | 16.0 | 12.84 ± 2.69 |
| mattcl-ts | input-pting | 15.4 ± 3.8 | 14.4 | 66.2 | 13.12 ± 4.21 |
| mattcl-py | input-chancalan | 22.1 ± 0.7 | 20.9 | 25.6 | 18.81 ± 3.97 |
| pting | input-chancalan | 22.3 ± 0.8 | 20.9 | 26.7 | 18.96 ± 4.02 |
| mattcl-py | input-mattcl | 22.3 ± 0.7 | 21.2 | 25.4 | 18.99 ± 4.00 |
| pting | input-mattcl | 22.4 ± 0.6 | 21.5 | 25.1 | 19.04 ± 4.01 |
| mattcl-py | input-lanjian | 22.6 ± 0.6 | 21.7 | 25.3 | 19.26 ± 4.05 |
| mattcl-py | input-kcen | 22.7 ± 0.6 | 21.9 | 25.5 | 19.37 ± 4.07 |
| pting | input-kcen | 22.8 ± 0.8 | 21.8 | 26.0 | 19.39 ± 4.09 |
| pting | input-lanjian | 22.8 ± 0.8 | 22.1 | 26.0 | 19.44 ± 4.10 |
| pting | input-pting | 23.0 ± 0.6 | 22.2 | 25.6 | 19.56 ± 4.11 |
| mattcl-py | input-pting | 23.0 ± 0.8 | 21.8 | 26.0 | 19.61 ± 4.14 |
| chancalan | input-chancalan | 23.5 ± 0.8 | 22.5 | 27.0 | 20.03 ± 4.23 |
| chancalan | input-mattcl | 23.8 ± 1.0 | 22.6 | 29.4 | 20.25 ± 4.30 |
| chancalan | input-lanjian | 24.2 ± 0.8 | 23.0 | 27.1 | 20.63 ± 4.36 |
| chancalan | input-pting | 24.7 ± 0.8 | 23.8 | 27.0 | 21.02 ± 4.43 |
| chancalan | input-kcen | 24.9 ± 5.0 | 23.2 | 68.9 | 21.21 ± 6.11 |
| kcen | input-chancalan | 27.9 ± 0.9 | 26.8 | 30.8 | 23.79 ± 5.01 |
| kcen | input-mattcl | 28.2 ± 0.8 | 27.3 | 31.1 | 24.01 ± 5.05 |
| kcen | input-kcen | 29.1 ± 0.8 | 28.1 | 32.1 | 24.81 ± 5.22 |
| kcen | input-lanjian | 29.3 ± 0.9 | 28.1 | 31.8 | 24.92 ± 5.25 |
| kcen | input-pting | 29.4 ± 0.7 | 28.5 | 32.1 | 25.07 ± 5.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|