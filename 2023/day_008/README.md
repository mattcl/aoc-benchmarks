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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.8 | 2.0 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 2.0 | 1.04 ± 0.30 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.8 | 2.0 | 1.04 ± 0.30 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 1.9 | 1.05 ± 0.31 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.9 | 2.0 | 1.05 ± 0.30 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.9 | 1.9 | 1.06 ± 0.30 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.9 | 2.0 | 1.06 ± 0.29 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.9 | 1.8 | 1.06 ± 0.30 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.16 ± 0.34 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.17 ± 0.34 |
| mattcl-ts | input-chancalan | 14.8 ± 0.3 | 14.0 | 15.8 | 12.89 ± 2.67 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.2 | 16.3 | 13.07 ± 2.70 |
| mattcl-ts | input-pting | 15.0 ± 0.3 | 14.3 | 15.9 | 13.09 ± 2.70 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.3 | 15.9 | 13.11 ± 2.71 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.4 | 16.5 | 13.13 ± 2.72 |
| mattcl-py | input-chancalan | 22.1 ± 0.6 | 21.0 | 24.5 | 19.23 ± 3.99 |
| pting | input-chancalan | 22.2 ± 0.7 | 21.3 | 24.4 | 19.31 ± 4.02 |
| mattcl-py | input-mattcl | 22.2 ± 0.6 | 21.2 | 25.0 | 19.36 ± 4.02 |
| pting | input-mattcl | 22.4 ± 0.6 | 21.4 | 25.1 | 19.51 ± 4.05 |
| mattcl-py | input-kcen | 22.7 ± 0.7 | 21.8 | 25.5 | 19.80 ± 4.12 |
| mattcl-py | input-lanjian | 22.8 ± 0.8 | 21.8 | 26.2 | 19.82 ± 4.14 |
| pting | input-kcen | 22.8 ± 0.6 | 22.0 | 26.0 | 19.83 ± 4.12 |
| pting | input-lanjian | 23.0 ± 0.8 | 21.9 | 25.5 | 19.98 ± 4.17 |
| mattcl-py | input-pting | 23.1 ± 0.8 | 21.8 | 25.8 | 20.14 ± 4.20 |
| pting | input-pting | 23.6 ± 4.0 | 22.1 | 62.1 | 20.57 ± 5.48 |
| chancalan | input-chancalan | 26.1 ± 0.6 | 25.3 | 29.3 | 22.69 ± 4.70 |
| chancalan | input-mattcl | 26.6 ± 1.2 | 25.5 | 34.4 | 23.17 ± 4.88 |
| chancalan | input-kcen | 27.3 ± 0.8 | 26.2 | 30.2 | 23.74 ± 4.94 |
| chancalan | input-lanjian | 27.3 ± 0.8 | 26.0 | 30.4 | 23.78 ± 4.95 |
| chancalan | input-pting | 27.9 ± 1.0 | 26.7 | 31.3 | 24.24 ± 5.07 |
| kcen | input-chancalan | 28.1 ± 1.0 | 27.0 | 32.7 | 24.44 ± 5.11 |
| kcen | input-mattcl | 28.7 ± 2.9 | 27.4 | 56.3 | 24.97 ± 5.71 |
| kcen | input-kcen | 29.4 ± 0.8 | 28.3 | 32.4 | 25.55 ± 5.30 |
| kcen | input-lanjian | 29.4 ± 1.1 | 28.0 | 32.6 | 25.58 ± 5.35 |
| kcen | input-pting | 29.8 ± 0.7 | 28.9 | 31.9 | 25.91 ± 5.37 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|