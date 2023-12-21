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
| mattcl | input-chancalan | 1.1 ± 0.3 | 0.8 | 1.9 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.30 |
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.9 | 1.01 ± 0.32 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.8 | 1.03 ± 0.31 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.1 | 1.05 ± 0.33 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.9 | 2.2 | 1.06 ± 0.34 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.9 | 1.9 | 1.06 ± 0.32 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.10 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 1.9 | 1.13 ± 0.34 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.13 ± 0.34 |
| mattcl-ts | input-chancalan | 14.9 ± 0.4 | 14.0 | 16.5 | 13.00 ± 2.87 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.1 | 16.2 | 13.08 ± 2.89 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.2 | 16.3 | 13.14 ± 2.90 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.5 | 16.3 | 13.19 ± 2.91 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 14.2 | 16.8 | 13.20 ± 2.92 |
| pting | input-chancalan | 22.3 ± 0.8 | 21.0 | 25.0 | 19.44 ± 4.32 |
| mattcl-py | input-mattcl | 22.4 ± 0.7 | 21.4 | 26.0 | 19.52 ± 4.33 |
| mattcl-py | input-chancalan | 22.4 ± 0.9 | 21.2 | 26.3 | 19.54 ± 4.37 |
| pting | input-mattcl | 22.5 ± 0.6 | 21.6 | 26.5 | 19.59 ± 4.34 |
| pting | input-kcen | 22.8 ± 0.6 | 21.6 | 26.5 | 19.89 ± 4.40 |
| mattcl-py | input-kcen | 22.8 ± 0.7 | 21.9 | 25.6 | 19.93 ± 4.42 |
| mattcl-py | input-lanjian | 23.0 ± 0.9 | 21.9 | 26.2 | 20.06 ± 4.48 |
| pting | input-lanjian | 23.1 ± 1.3 | 22.2 | 34.6 | 20.19 ± 4.57 |
| mattcl-py | input-pting | 23.3 ± 0.8 | 21.9 | 26.5 | 20.32 ± 4.52 |
| pting | input-pting | 23.3 ± 0.8 | 22.2 | 26.2 | 20.34 ± 4.52 |
| chancalan | input-chancalan | 23.6 ± 0.7 | 22.6 | 26.2 | 20.59 ± 4.57 |
| chancalan | input-kcen | 24.5 ± 0.8 | 23.3 | 28.1 | 21.34 ± 4.74 |
| chancalan | input-lanjian | 24.5 ± 1.3 | 23.2 | 33.0 | 21.38 ± 4.83 |
| chancalan | input-mattcl | 24.5 ± 5.7 | 22.3 | 78.6 | 21.38 ± 6.82 |
| chancalan | input-pting | 24.8 ± 0.9 | 23.5 | 27.7 | 21.61 ± 4.81 |
| kcen | input-chancalan | 28.2 ± 0.9 | 26.7 | 31.0 | 24.57 ± 5.46 |
| kcen | input-mattcl | 28.4 ± 0.9 | 26.7 | 31.0 | 24.75 ± 5.49 |
| kcen | input-lanjian | 29.2 ± 0.7 | 27.8 | 31.7 | 25.48 ± 5.63 |
| kcen | input-kcen | 29.4 ± 1.0 | 28.1 | 31.9 | 25.65 ± 5.70 |
| kcen | input-pting | 29.9 ± 1.0 | 28.3 | 32.6 | 26.10 ± 5.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|