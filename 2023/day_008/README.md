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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.9 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 1.9 | 1.05 ± 0.30 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.1 | 1.06 ± 0.30 |
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.9 | 1.9 | 1.07 ± 0.31 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.08 ± 0.32 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 1.9 | 1.08 ± 0.31 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.10 ± 0.31 |
| lanjian | input-lanjian | 1.4 ± 0.3 | 1.0 | 2.1 | 1.12 ± 0.31 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.0 | 2.2 | 1.13 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.3 | 1.14 ± 0.31 |
| mattcl-ts | input-chancalan | 14.8 ± 0.4 | 13.8 | 15.8 | 12.17 ± 2.51 |
| mattcl-ts | input-mattcl | 14.9 ± 0.3 | 13.8 | 15.7 | 12.27 ± 2.53 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.0 | 16.2 | 12.35 ± 2.54 |
| mattcl-ts | input-kcen | 15.0 ± 0.4 | 13.9 | 16.4 | 12.35 ± 2.55 |
| mattcl-ts | input-pting | 15.0 ± 0.3 | 13.9 | 16.1 | 12.37 ± 2.54 |
| pting | input-chancalan | 22.1 ± 0.6 | 21.2 | 24.6 | 18.20 ± 3.75 |
| mattcl-py | input-chancalan | 22.3 ± 0.7 | 21.2 | 25.3 | 18.32 ± 3.80 |
| mattcl-py | input-mattcl | 22.4 ± 0.7 | 21.5 | 26.6 | 18.45 ± 3.82 |
| pting | input-mattcl | 22.5 ± 0.7 | 20.9 | 25.9 | 18.49 ± 3.83 |
| mattcl-py | input-lanjian | 22.8 ± 0.7 | 21.5 | 25.9 | 18.74 ± 3.88 |
| mattcl-py | input-kcen | 23.0 ± 0.6 | 22.0 | 26.3 | 18.88 ± 3.89 |
| pting | input-lanjian | 23.0 ± 0.7 | 21.9 | 26.0 | 18.88 ± 3.91 |
| pting | input-kcen | 23.0 ± 0.7 | 22.0 | 25.8 | 18.94 ± 3.92 |
| mattcl-py | input-pting | 23.1 ± 0.9 | 21.9 | 26.5 | 19.01 ± 3.95 |
| pting | input-pting | 23.2 ± 0.8 | 22.3 | 26.6 | 19.07 ± 3.96 |
| chancalan | input-chancalan | 23.8 ± 0.9 | 22.4 | 26.7 | 19.54 ± 4.07 |
| chancalan | input-mattcl | 23.8 ± 0.9 | 22.7 | 29.5 | 19.59 ± 4.08 |
| chancalan | input-kcen | 24.4 ± 0.7 | 23.5 | 27.8 | 20.10 ± 4.16 |
| chancalan | input-lanjian | 24.5 ± 0.9 | 23.0 | 27.4 | 20.16 ± 4.19 |
| chancalan | input-pting | 24.7 ± 0.8 | 23.4 | 27.4 | 20.27 ± 4.20 |
| kcen | input-chancalan | 28.3 ± 0.9 | 26.9 | 31.1 | 23.24 ± 4.82 |
| kcen | input-mattcl | 28.3 ± 0.9 | 27.0 | 31.4 | 23.25 ± 4.81 |
| kcen | input-kcen | 29.2 ± 1.0 | 27.8 | 32.7 | 24.02 ± 4.98 |
| kcen | input-lanjian | 29.3 ± 0.8 | 27.8 | 32.1 | 24.13 ± 4.98 |
| kcen | input-pting | 29.7 ± 0.9 | 28.2 | 33.0 | 24.44 ± 5.05 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|