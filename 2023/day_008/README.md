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
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.1 | 1.03 ± 0.31 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.9 | 1.03 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.9 | 1.8 | 1.04 ± 0.30 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.06 ± 0.32 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.1 | 1.06 ± 0.31 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 1.9 | 1.07 ± 0.30 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.07 ± 0.32 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.2 | 1.08 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.1 | 1.14 ± 0.33 |
| mattcl-ts | input-chancalan | 15.0 ± 0.3 | 14.1 | 16.0 | 12.50 ± 2.71 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.3 | 17.2 | 12.61 ± 2.74 |
| mattcl-ts | input-pting | 15.2 ± 0.4 | 14.2 | 16.4 | 12.69 ± 2.75 |
| mattcl-ts | input-kcen | 15.2 ± 0.4 | 14.4 | 16.2 | 12.70 ± 2.76 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.3 | 16.9 | 12.72 ± 2.76 |
| mattcl-py | input-chancalan | 22.1 ± 0.8 | 21.2 | 25.6 | 18.43 ± 4.03 |
| pting | input-chancalan | 22.1 ± 0.8 | 21.0 | 25.8 | 18.46 ± 4.04 |
| mattcl-py | input-mattcl | 22.2 ± 0.7 | 21.3 | 25.5 | 18.55 ± 4.04 |
| pting | input-mattcl | 22.3 ± 1.0 | 20.9 | 30.2 | 18.60 ± 4.10 |
| pting | input-lanjian | 22.7 ± 0.7 | 21.4 | 25.8 | 18.92 ± 4.12 |
| mattcl-py | input-lanjian | 22.7 ± 0.7 | 21.6 | 25.4 | 18.97 ± 4.13 |
| mattcl-py | input-kcen | 22.9 ± 0.7 | 22.0 | 26.4 | 19.13 ± 4.17 |
| pting | input-pting | 23.1 ± 0.8 | 21.9 | 26.3 | 19.26 ± 4.21 |
| mattcl-py | input-pting | 23.1 ± 0.9 | 21.6 | 26.6 | 19.27 ± 4.22 |
| pting | input-kcen | 23.3 ± 3.9 | 21.3 | 62.6 | 19.39 ± 5.32 |
| chancalan | input-chancalan | 23.6 ± 0.9 | 22.5 | 28.6 | 19.66 ± 4.30 |
| chancalan | input-mattcl | 23.7 ± 0.8 | 22.6 | 26.6 | 19.80 ± 4.32 |
| chancalan | input-kcen | 24.2 ± 0.8 | 23.1 | 27.2 | 20.21 ± 4.41 |
| chancalan | input-lanjian | 24.3 ± 0.9 | 22.9 | 27.3 | 20.25 ± 4.43 |
| chancalan | input-pting | 24.4 ± 0.7 | 23.1 | 27.2 | 20.36 ± 4.43 |
| kcen | input-chancalan | 27.8 ± 0.8 | 26.9 | 31.1 | 23.20 ± 5.04 |
| kcen | input-mattcl | 28.3 ± 0.9 | 27.0 | 31.1 | 23.56 ± 5.14 |
| kcen | input-lanjian | 29.3 ± 0.8 | 28.0 | 32.0 | 24.39 ± 5.30 |
| kcen | input-pting | 29.5 ± 0.7 | 28.3 | 31.8 | 24.62 ± 5.34 |
| kcen | input-kcen | 29.7 ± 2.3 | 27.9 | 49.8 | 24.72 ± 5.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|