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
| mattcl | input-mattcl | 1.3 ± 0.3 | 0.9 | 1.9 | 1.00 |
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.03 ± 0.30 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.1 | 1.03 ± 0.30 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 1.0 | 2.0 | 1.04 ± 0.30 |
| mattcl | input-pting | 1.3 ± 0.3 | 1.0 | 2.0 | 1.05 ± 0.30 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.06 ± 0.30 |
| mattcl | input-kcen | 1.4 ± 0.3 | 1.0 | 2.0 | 1.07 ± 0.31 |
| lanjian | input-lanjian | 1.4 ± 0.3 | 1.0 | 2.1 | 1.10 ± 0.32 |
| lanjian | input-pting | 1.4 ± 0.2 | 1.0 | 2.0 | 1.11 ± 0.30 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.2 | 1.14 ± 0.32 |
| mattcl-ts | input-chancalan | 14.9 ± 0.3 | 13.8 | 15.8 | 11.82 ± 2.51 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 14.2 | 16.1 | 11.95 ± 2.54 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.4 | 16.2 | 12.00 ± 2.55 |
| mattcl-ts | input-lanjian | 15.1 ± 0.4 | 14.3 | 16.6 | 12.02 ± 2.55 |
| mattcl-ts | input-pting | 15.2 ± 0.3 | 14.3 | 16.5 | 12.06 ± 2.56 |
| pting | input-chancalan | 22.1 ± 0.7 | 21.0 | 25.1 | 17.58 ± 3.75 |
| mattcl-py | input-chancalan | 22.3 ± 0.9 | 21.3 | 25.2 | 17.69 ± 3.80 |
| mattcl-py | input-mattcl | 22.3 ± 0.7 | 21.5 | 25.7 | 17.70 ± 3.77 |
| pting | input-mattcl | 22.5 ± 0.8 | 21.4 | 25.7 | 17.89 ± 3.83 |
| pting | input-kcen | 22.8 ± 0.7 | 21.9 | 25.5 | 18.07 ± 3.85 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.9 | 26.5 | 18.17 ± 3.89 |
| mattcl-py | input-kcen | 22.9 ± 1.2 | 21.8 | 33.5 | 18.17 ± 3.95 |
| mattcl-py | input-pting | 23.1 ± 0.8 | 22.1 | 26.8 | 18.30 ± 3.91 |
| mattcl-py | input-lanjian | 23.1 ± 4.3 | 21.6 | 70.4 | 18.36 ± 5.16 |
| pting | input-pting | 23.2 ± 0.9 | 22.0 | 27.4 | 18.39 ± 3.95 |
| chancalan | input-chancalan | 23.5 ± 0.6 | 22.5 | 26.4 | 18.63 ± 3.96 |
| chancalan | input-mattcl | 23.7 ± 0.6 | 22.9 | 26.5 | 18.82 ± 4.00 |
| chancalan | input-lanjian | 24.3 ± 0.8 | 23.1 | 27.3 | 19.26 ± 4.12 |
| chancalan | input-kcen | 24.4 ± 0.8 | 23.2 | 27.3 | 19.39 ± 4.15 |
| chancalan | input-pting | 24.6 ± 0.7 | 23.6 | 27.7 | 19.57 ± 4.17 |
| kcen | input-chancalan | 28.0 ± 0.8 | 26.8 | 31.2 | 22.22 ± 4.74 |
| kcen | input-mattcl | 28.3 ± 0.9 | 27.1 | 31.1 | 22.49 ± 4.80 |
| kcen | input-lanjian | 29.1 ± 0.9 | 28.0 | 32.4 | 23.08 ± 4.92 |
| kcen | input-kcen | 29.3 ± 0.8 | 28.2 | 31.8 | 23.25 ± 4.95 |
| kcen | input-pting | 29.6 ± 0.9 | 28.6 | 33.3 | 23.51 ± 5.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|