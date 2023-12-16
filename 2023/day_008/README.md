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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.9 | 2.0 | 1.00 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.9 | 2.0 | 1.03 ± 0.31 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.9 | 2.0 | 1.04 ± 0.29 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.05 ± 0.31 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.0 | 1.06 ± 0.31 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.08 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.08 ± 0.31 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.1 | 1.09 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 2.1 | 1.11 ± 0.29 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.2 | 1.15 ± 0.33 |
| mattcl-ts | input-chancalan | 15.1 ± 0.3 | 14.3 | 16.3 | 12.42 ± 2.58 |
| mattcl-ts | input-kcen | 15.3 ± 0.3 | 14.5 | 16.6 | 12.58 ± 2.62 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.7 | 17.0 | 12.60 ± 2.62 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.5 | 16.7 | 12.65 ± 2.63 |
| mattcl-ts | input-mattcl | 16.0 ± 5.7 | 14.3 | 61.6 | 13.21 ± 5.47 |
| pting | input-chancalan | 22.2 ± 0.7 | 21.4 | 25.3 | 18.33 ± 3.83 |
| mattcl-py | input-chancalan | 22.3 ± 0.9 | 21.0 | 26.0 | 18.37 ± 3.87 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.5 | 26.3 | 18.52 ± 3.87 |
| mattcl-py | input-mattcl | 22.6 ± 0.8 | 21.2 | 26.2 | 18.61 ± 3.91 |
| mattcl-py | input-lanjian | 22.9 ± 0.8 | 21.7 | 26.5 | 18.88 ± 3.97 |
| mattcl-py | input-kcen | 22.9 ± 0.6 | 21.8 | 25.9 | 18.92 ± 3.95 |
| pting | input-kcen | 23.0 ± 0.8 | 21.8 | 26.7 | 18.95 ± 3.97 |
| pting | input-lanjian | 23.0 ± 0.9 | 21.8 | 26.4 | 18.98 ± 3.99 |
| mattcl-py | input-pting | 23.2 ± 0.6 | 22.1 | 26.3 | 19.12 ± 3.98 |
| pting | input-pting | 23.4 ± 0.8 | 22.4 | 26.7 | 19.29 ± 4.04 |
| chancalan | input-chancalan | 23.6 ± 0.8 | 22.5 | 26.9 | 19.48 ± 4.09 |
| chancalan | input-mattcl | 23.9 ± 0.8 | 22.8 | 26.7 | 19.74 ± 4.14 |
| chancalan | input-lanjian | 24.5 ± 0.8 | 23.5 | 27.5 | 20.25 ± 4.24 |
| chancalan | input-kcen | 24.6 ± 0.8 | 23.1 | 27.4 | 20.27 ± 4.25 |
| chancalan | input-pting | 24.7 ± 0.6 | 23.5 | 27.1 | 20.34 ± 4.24 |
| kcen | input-chancalan | 28.1 ± 0.8 | 27.0 | 31.0 | 23.19 ± 4.85 |
| kcen | input-mattcl | 28.4 ± 0.9 | 27.3 | 31.2 | 23.45 ± 4.90 |
| kcen | input-lanjian | 29.4 ± 0.9 | 27.8 | 32.2 | 24.22 ± 5.07 |
| kcen | input-kcen | 29.6 ± 1.1 | 28.1 | 33.5 | 24.38 ± 5.12 |
| kcen | input-pting | 29.7 ± 0.6 | 28.3 | 31.9 | 24.47 ± 5.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|