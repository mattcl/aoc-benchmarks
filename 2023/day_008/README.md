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
| mattcl | input-chancalan | 1.3 ± 0.3 | 1.0 | 2.1 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.3 | 1.0 | 2.0 | 1.01 ± 0.27 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.1 | 1.02 ± 0.27 |
| mattcl | input-lanjian | 1.4 ± 0.3 | 1.0 | 2.0 | 1.03 ± 0.28 |
| mattcl | input-pting | 1.4 ± 0.3 | 1.0 | 2.2 | 1.04 ± 0.28 |
| lanjian | input-chancalan | 1.4 ± 0.3 | 1.0 | 2.0 | 1.05 ± 0.28 |
| mattcl | input-kcen | 1.4 ± 0.3 | 1.0 | 2.1 | 1.06 ± 0.28 |
| lanjian | input-lanjian | 1.4 ± 0.3 | 1.0 | 2.2 | 1.07 ± 0.29 |
| lanjian | input-pting | 1.5 ± 0.3 | 1.0 | 2.3 | 1.09 ± 0.28 |
| lanjian | input-kcen | 1.5 ± 0.3 | 1.1 | 2.3 | 1.14 ± 0.29 |
| mattcl-ts | input-chancalan | 15.2 ± 0.4 | 14.2 | 16.9 | 11.34 ± 2.23 |
| mattcl-ts | input-mattcl | 15.3 ± 0.4 | 14.3 | 16.9 | 11.40 ± 2.24 |
| mattcl-ts | input-lanjian | 15.4 ± 0.4 | 14.5 | 17.8 | 11.50 ± 2.26 |
| mattcl-ts | input-kcen | 15.4 ± 0.4 | 14.5 | 16.6 | 11.50 ± 2.26 |
| mattcl-ts | input-pting | 15.5 ± 0.4 | 14.7 | 17.6 | 11.55 ± 2.27 |
| mattcl-py | input-chancalan | 22.4 ± 0.6 | 21.5 | 24.8 | 16.72 ± 3.28 |
| pting | input-mattcl | 22.4 ± 0.6 | 21.2 | 25.4 | 16.76 ± 3.29 |
| mattcl-py | input-mattcl | 22.5 ± 0.9 | 21.5 | 26.4 | 16.83 ± 3.34 |
| pting | input-chancalan | 22.6 ± 3.7 | 21.0 | 63.6 | 16.89 ± 4.27 |
| pting | input-kcen | 23.0 ± 0.6 | 22.1 | 25.6 | 17.16 ± 3.37 |
| mattcl-py | input-lanjian | 23.0 ± 0.8 | 21.9 | 26.5 | 17.17 ± 3.39 |
| mattcl-py | input-kcen | 23.0 ± 0.7 | 21.8 | 25.9 | 17.18 ± 3.39 |
| pting | input-lanjian | 23.0 ± 0.7 | 21.8 | 26.3 | 17.19 ± 3.39 |
| pting | input-pting | 23.1 ± 0.7 | 22.0 | 26.1 | 17.26 ± 3.39 |
| mattcl-py | input-pting | 23.3 ± 0.7 | 21.9 | 25.9 | 17.41 ± 3.43 |
| chancalan | input-chancalan | 23.5 ± 0.8 | 22.3 | 26.7 | 17.56 ± 3.47 |
| chancalan | input-mattcl | 23.9 ± 0.9 | 22.8 | 26.9 | 17.87 ± 3.54 |
| chancalan | input-lanjian | 24.5 ± 0.8 | 23.6 | 28.5 | 18.29 ± 3.61 |
| chancalan | input-kcen | 24.7 ± 1.0 | 23.1 | 27.3 | 18.44 ± 3.67 |
| chancalan | input-pting | 24.7 ± 0.8 | 23.6 | 27.4 | 18.45 ± 3.64 |
| kcen | input-chancalan | 28.0 ± 0.8 | 26.7 | 31.0 | 20.92 ± 4.11 |
| kcen | input-mattcl | 28.4 ± 1.0 | 27.0 | 31.5 | 21.20 ± 4.19 |
| kcen | input-lanjian | 29.5 ± 0.9 | 27.7 | 32.8 | 21.99 ± 4.33 |
| kcen | input-kcen | 29.5 ± 1.0 | 27.8 | 33.1 | 22.04 ± 4.36 |
| kcen | input-pting | 29.8 ± 0.9 | 28.4 | 32.4 | 22.25 ± 4.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|