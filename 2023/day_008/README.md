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
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.8 | 1.00 ± 0.30 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.9 | 1.03 ± 0.32 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.8 | 1.8 | 1.03 ± 0.30 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 2.0 | 1.05 ± 0.32 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.9 | 1.9 | 1.05 ± 0.32 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 2.0 | 1.07 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.10 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.12 ± 0.33 |
| mattcl-ts | input-chancalan | 14.8 ± 0.3 | 13.9 | 15.7 | 12.75 ± 2.86 |
| mattcl-ts | input-mattcl | 14.9 ± 0.4 | 13.9 | 16.1 | 12.85 ± 2.89 |
| mattcl-ts | input-kcen | 15.0 ± 0.3 | 14.3 | 15.9 | 12.94 ± 2.90 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.1 | 16.1 | 12.97 ± 2.90 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.1 | 17.2 | 12.97 ± 2.91 |
| mattcl-py | input-chancalan | 21.8 ± 0.7 | 20.8 | 25.0 | 18.81 ± 4.24 |
| pting | input-chancalan | 22.1 ± 0.9 | 21.1 | 25.5 | 19.03 ± 4.32 |
| pting | input-mattcl | 22.1 ± 0.6 | 21.1 | 25.1 | 19.06 ± 4.29 |
| mattcl-py | input-mattcl | 22.1 ± 0.6 | 21.4 | 24.8 | 19.08 ± 4.29 |
| mattcl-py | input-lanjian | 22.6 ± 0.8 | 21.5 | 26.3 | 19.43 ± 4.40 |
| mattcl-py | input-kcen | 22.6 ± 0.6 | 21.9 | 25.4 | 19.48 ± 4.38 |
| pting | input-lanjian | 22.6 ± 0.7 | 21.7 | 25.4 | 19.51 ± 4.40 |
| pting | input-kcen | 22.6 ± 0.8 | 21.6 | 26.4 | 19.52 ± 4.41 |
| mattcl-py | input-pting | 22.8 ± 0.7 | 21.9 | 25.6 | 19.66 ± 4.42 |
| pting | input-pting | 23.2 ± 1.0 | 21.9 | 27.3 | 19.96 ± 4.54 |
| chancalan | input-chancalan | 23.2 ± 0.8 | 22.2 | 26.7 | 20.02 ± 4.52 |
| chancalan | input-mattcl | 23.6 ± 0.9 | 22.4 | 26.7 | 20.35 ± 4.60 |
| chancalan | input-lanjian | 23.9 ± 0.7 | 22.8 | 26.3 | 20.61 ± 4.64 |
| chancalan | input-kcen | 24.1 ± 0.9 | 22.9 | 26.9 | 20.73 ± 4.68 |
| chancalan | input-pting | 24.4 ± 0.9 | 23.2 | 27.8 | 21.04 ± 4.76 |
| kcen | input-chancalan | 27.6 ± 0.9 | 26.5 | 31.0 | 23.80 ± 5.37 |
| kcen | input-mattcl | 27.9 ± 0.9 | 26.7 | 30.6 | 24.07 ± 5.42 |
| kcen | input-lanjian | 28.9 ± 0.8 | 27.9 | 31.9 | 24.90 ± 5.60 |
| kcen | input-pting | 29.5 ± 0.9 | 28.3 | 32.8 | 25.42 ± 5.73 |
| kcen | input-kcen | 29.7 ± 4.1 | 28.2 | 61.4 | 25.60 ± 6.71 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|