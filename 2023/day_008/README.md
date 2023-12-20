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
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.9 | 2.1 | 1.02 ± 0.30 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 1.9 | 1.04 ± 0.31 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.9 | 2.0 | 1.05 ± 0.30 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.0 | 1.05 ± 0.31 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.06 ± 0.31 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.1 | 1.06 ± 0.30 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 2.0 | 1.08 ± 0.30 |
| lanjian | input-pting | 1.3 ± 0.2 | 1.0 | 2.1 | 1.11 ± 0.30 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.0 | 1.11 ± 0.31 |
| mattcl-ts | input-chancalan | 14.9 ± 0.3 | 14.2 | 15.9 | 12.20 ± 2.59 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 14.2 | 16.2 | 12.28 ± 2.61 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.1 | 16.0 | 12.35 ± 2.62 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.2 | 16.2 | 12.36 ± 2.63 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.3 | 16.4 | 12.38 ± 2.63 |
| mattcl-py | input-chancalan | 22.2 ± 0.7 | 21.0 | 25.3 | 18.19 ± 3.89 |
| pting | input-chancalan | 22.3 ± 0.7 | 21.3 | 24.9 | 18.29 ± 3.91 |
| mattcl-py | input-mattcl | 22.3 ± 0.6 | 21.5 | 25.7 | 18.29 ± 3.90 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.3 | 25.5 | 18.38 ± 3.93 |
| mattcl-py | input-kcen | 22.9 ± 0.8 | 21.8 | 26.5 | 18.76 ± 4.03 |
| pting | input-kcen | 22.9 ± 0.8 | 21.9 | 26.0 | 18.80 ± 4.03 |
| mattcl-py | input-lanjian | 23.0 ± 0.9 | 21.7 | 26.4 | 18.85 ± 4.05 |
| mattcl-py | input-pting | 23.0 ± 0.5 | 21.9 | 25.9 | 18.91 ± 4.02 |
| pting | input-pting | 23.2 ± 0.8 | 22.2 | 26.9 | 19.06 ± 4.08 |
| pting | input-lanjian | 23.2 ± 1.6 | 21.8 | 38.9 | 19.08 ± 4.25 |
| chancalan | input-chancalan | 23.5 ± 0.8 | 22.4 | 26.8 | 19.30 ± 4.13 |
| chancalan | input-mattcl | 23.8 ± 0.9 | 22.6 | 27.8 | 19.53 ± 4.19 |
| chancalan | input-lanjian | 24.4 ± 0.8 | 22.9 | 26.8 | 19.99 ± 4.27 |
| chancalan | input-kcen | 24.4 ± 0.7 | 23.4 | 26.8 | 20.05 ± 4.27 |
| chancalan | input-pting | 24.7 ± 0.8 | 23.6 | 27.5 | 20.24 ± 4.33 |
| kcen | input-chancalan | 28.1 ± 0.9 | 27.0 | 30.8 | 23.08 ± 4.94 |
| kcen | input-mattcl | 28.4 ± 0.9 | 27.1 | 31.4 | 23.29 ± 4.98 |
| kcen | input-kcen | 29.4 ± 0.8 | 28.1 | 31.7 | 24.13 ± 5.14 |
| kcen | input-lanjian | 29.5 ± 1.0 | 28.0 | 32.3 | 24.18 ± 5.18 |
| kcen | input-pting | 29.6 ± 0.7 | 28.5 | 32.4 | 24.30 ± 5.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|