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
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 2.0 | 1.03 ± 0.31 |
| mattcl | input-chancalan | 1.2 ± 0.4 | 0.8 | 4.9 | 1.04 ± 0.38 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.9 | 1.9 | 1.05 ± 0.30 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.9 | 2.0 | 1.06 ± 0.30 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.0 | 1.07 ± 0.32 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.2 | 1.10 ± 0.31 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.13 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.2 | 1.15 ± 0.32 |
| lanjian | input-chancalan | 1.4 ± 3.3 | 0.9 | 47.9 | 1.20 ± 2.80 |
| mattcl-ts | input-chancalan | 15.0 ± 0.4 | 13.9 | 16.1 | 12.66 ± 2.61 |
| mattcl-ts | input-mattcl | 15.2 ± 0.4 | 14.2 | 16.7 | 12.80 ± 2.64 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.4 | 16.5 | 12.89 ± 2.66 |
| mattcl-ts | input-kcen | 15.5 ± 3.5 | 14.4 | 62.0 | 13.07 ± 3.97 |
| mattcl-ts | input-pting | 15.8 ± 5.7 | 14.5 | 93.5 | 13.33 ± 5.56 |
| pting | input-chancalan | 22.2 ± 0.8 | 21.2 | 25.1 | 18.68 ± 3.88 |
| mattcl-py | input-chancalan | 22.4 ± 0.9 | 21.1 | 25.7 | 18.85 ± 3.94 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.0 | 24.9 | 18.89 ± 3.91 |
| mattcl-py | input-mattcl | 22.5 ± 0.8 | 21.4 | 26.2 | 18.93 ± 3.94 |
| mattcl-py | input-kcen | 22.8 ± 0.7 | 21.8 | 25.8 | 19.25 ± 3.99 |
| mattcl-py | input-lanjian | 22.9 ± 0.8 | 22.0 | 25.9 | 19.32 ± 4.02 |
| pting | input-kcen | 22.9 ± 0.7 | 21.9 | 25.7 | 19.33 ± 4.01 |
| mattcl-py | input-pting | 23.3 ± 0.8 | 22.0 | 26.2 | 19.63 ± 4.08 |
| pting | input-pting | 23.3 ± 0.9 | 22.2 | 26.8 | 19.65 ± 4.10 |
| pting | input-lanjian | 23.3 ± 3.1 | 22.0 | 55.3 | 19.67 ± 4.79 |
| chancalan | input-chancalan | 23.6 ± 0.7 | 22.7 | 26.8 | 19.88 ± 4.12 |
| chancalan | input-mattcl | 23.8 ± 0.8 | 22.7 | 26.7 | 20.10 ± 4.17 |
| chancalan | input-lanjian | 24.2 ± 0.7 | 23.3 | 27.1 | 20.40 ± 4.22 |
| chancalan | input-kcen | 24.3 ± 0.7 | 23.3 | 27.0 | 20.51 ± 4.25 |
| chancalan | input-pting | 24.6 ± 0.7 | 23.2 | 27.9 | 20.74 ± 4.30 |
| kcen | input-chancalan | 28.2 ± 0.9 | 26.8 | 31.5 | 23.80 ± 4.94 |
| kcen | input-mattcl | 28.3 ± 0.9 | 27.2 | 31.2 | 23.88 ± 4.95 |
| kcen | input-lanjian | 29.2 ± 0.9 | 27.8 | 32.2 | 24.60 ± 5.10 |
| kcen | input-kcen | 29.4 ± 0.8 | 28.1 | 32.9 | 24.77 ± 5.12 |
| kcen | input-pting | 30.0 ± 1.0 | 28.5 | 33.1 | 25.25 ± 5.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|