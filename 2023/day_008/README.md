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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.0 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.8 | 1.02 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.0 | 1.02 ± 0.32 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.9 | 1.03 ± 0.34 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.9 | 1.04 ± 0.33 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.9 | 1.8 | 1.04 ± 0.31 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.33 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.09 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.12 ± 0.35 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.3 | 1.16 ± 0.35 |
| mattcl-ts | input-chancalan | 15.0 ± 0.2 | 14.2 | 15.7 | 12.71 ± 2.90 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.3 | 16.4 | 12.76 ± 2.92 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.3 | 16.6 | 12.82 ± 2.93 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.3 | 16.3 | 12.85 ± 2.94 |
| mattcl-ts | input-pting | 15.3 ± 0.3 | 14.6 | 16.4 | 12.97 ± 2.97 |
| mattcl-py | input-chancalan | 22.1 ± 0.7 | 21.1 | 25.4 | 18.80 ± 4.33 |
| mattcl-py | input-mattcl | 22.4 ± 0.7 | 21.0 | 25.3 | 18.99 ± 4.37 |
| pting | input-mattcl | 22.4 ± 1.0 | 21.3 | 31.5 | 19.02 ± 4.42 |
| pting | input-chancalan | 22.4 ± 0.9 | 21.3 | 25.2 | 19.03 ± 4.40 |
| mattcl-py | input-lanjian | 22.8 ± 0.8 | 21.6 | 25.9 | 19.40 ± 4.47 |
| pting | input-kcen | 22.9 ± 0.7 | 22.0 | 26.0 | 19.49 ± 4.48 |
| pting | input-lanjian | 23.0 ± 0.7 | 21.9 | 26.4 | 19.49 ± 4.48 |
| mattcl-py | input-kcen | 23.0 ± 0.8 | 21.7 | 26.3 | 19.54 ± 4.51 |
| mattcl-py | input-pting | 23.1 ± 0.6 | 22.2 | 25.8 | 19.61 ± 4.50 |
| pting | input-pting | 23.3 ± 0.6 | 22.4 | 26.1 | 19.81 ± 4.55 |
| chancalan | input-chancalan | 23.6 ± 0.7 | 22.8 | 26.6 | 20.01 ± 4.60 |
| chancalan | input-mattcl | 23.8 ± 0.8 | 22.4 | 26.8 | 20.19 ± 4.66 |
| chancalan | input-lanjian | 24.2 ± 0.7 | 22.9 | 26.6 | 20.53 ± 4.72 |
| chancalan | input-kcen | 24.4 ± 0.8 | 23.2 | 27.0 | 20.76 ± 4.78 |
| chancalan | input-pting | 24.8 ± 0.8 | 23.8 | 28.1 | 21.03 ± 4.84 |
| kcen | input-mattcl | 28.4 ± 0.7 | 27.2 | 31.8 | 24.14 ± 5.54 |
| kcen | input-chancalan | 28.4 ± 0.8 | 27.2 | 31.6 | 24.15 ± 5.55 |
| kcen | input-lanjian | 29.4 ± 0.9 | 28.1 | 32.5 | 24.96 ± 5.74 |
| kcen | input-kcen | 29.6 ± 0.8 | 28.1 | 32.1 | 25.10 ± 5.76 |
| kcen | input-pting | 30.0 ± 0.9 | 28.8 | 32.8 | 25.51 ± 5.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|