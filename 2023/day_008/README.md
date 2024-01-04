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
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 1.8 | 1.00 ± 0.27 |
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.06 ± 0.30 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.9 | 1.9 | 1.06 ± 0.29 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.9 | 1.9 | 1.06 ± 0.28 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 2.2 | 1.06 ± 0.29 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.1 | 1.08 ± 0.31 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 1.9 | 1.09 ± 0.30 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 1.9 | 1.09 ± 0.29 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.9 | 2.2 | 1.14 ± 0.30 |
| mattcl-ts | input-chancalan | 15.0 ± 2.1 | 13.7 | 43.3 | 12.56 ± 3.02 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.0 | 15.8 | 12.59 ± 2.48 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.3 | 15.9 | 12.62 ± 2.48 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.3 | 16.0 | 12.68 ± 2.49 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.4 | 16.1 | 12.70 ± 2.50 |
| mattcl-py | input-chancalan | 21.9 ± 0.7 | 21.0 | 25.5 | 18.36 ± 3.64 |
| mattcl-py | input-mattcl | 22.1 ± 0.7 | 20.8 | 25.4 | 18.60 ± 3.69 |
| pting | input-mattcl | 22.2 ± 1.0 | 21.0 | 28.8 | 18.66 ± 3.75 |
| pting | input-chancalan | 22.4 ± 3.2 | 20.7 | 49.5 | 18.79 ± 4.56 |
| pting | input-kcen | 22.5 ± 0.7 | 21.3 | 25.9 | 18.89 ± 3.74 |
| mattcl-py | input-lanjian | 22.6 ± 1.0 | 21.6 | 26.1 | 18.97 ± 3.80 |
| mattcl-py | input-kcen | 22.6 ± 0.8 | 21.8 | 27.2 | 18.98 ± 3.78 |
| pting | input-lanjian | 22.6 ± 0.8 | 21.7 | 26.4 | 19.01 ± 3.78 |
| mattcl-py | input-pting | 22.8 ± 0.9 | 21.6 | 26.5 | 19.14 ± 3.82 |
| pting | input-pting | 22.8 ± 0.8 | 21.9 | 25.9 | 19.18 ± 3.82 |
| chancalan | input-chancalan | 23.3 ± 0.8 | 22.3 | 26.6 | 19.58 ± 3.90 |
| chancalan | input-mattcl | 23.4 ± 0.7 | 22.5 | 26.1 | 19.67 ± 3.89 |
| chancalan | input-kcen | 24.0 ± 0.7 | 23.0 | 27.1 | 20.19 ± 4.00 |
| chancalan | input-lanjian | 24.1 ± 0.9 | 22.6 | 26.8 | 20.26 ± 4.03 |
| chancalan | input-pting | 24.2 ± 0.7 | 23.1 | 27.5 | 20.29 ± 4.01 |
| kcen | input-chancalan | 27.5 ± 0.7 | 26.6 | 30.3 | 23.09 ± 4.56 |
| kcen | input-mattcl | 27.8 ± 0.7 | 26.9 | 30.4 | 23.35 ± 4.61 |
| kcen | input-kcen | 28.9 ± 0.8 | 27.8 | 31.4 | 24.28 ± 4.80 |
| kcen | input-lanjian | 28.9 ± 1.4 | 27.8 | 40.9 | 24.30 ± 4.90 |
| kcen | input-pting | 29.2 ± 0.8 | 28.0 | 32.2 | 24.53 ± 4.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|