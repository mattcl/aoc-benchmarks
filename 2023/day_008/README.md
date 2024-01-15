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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.8 | 2.0 | 1.00 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.9 | 1.8 | 1.06 ± 0.29 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 2.1 | 1.07 ± 0.30 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.9 | 1.9 | 1.07 ± 0.30 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.07 ± 0.32 |
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.9 | 1.8 | 1.08 ± 0.33 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.09 ± 0.32 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.11 ± 0.32 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.0 | 2.2 | 1.18 ± 0.33 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.1 | 1.19 ± 0.34 |
| mattcl-ts | input-chancalan | 14.1 ± 0.4 | 13.2 | 15.3 | 12.07 ± 2.54 |
| mattcl-ts | input-mattcl | 14.3 ± 0.4 | 13.4 | 15.5 | 12.27 ± 2.58 |
| mattcl-ts | input-lanjian | 14.5 ± 0.4 | 13.4 | 16.0 | 12.38 ± 2.61 |
| mattcl-ts | input-kcen | 14.6 ± 0.5 | 13.4 | 15.7 | 12.47 ± 2.63 |
| mattcl-ts | input-pting | 14.7 ± 0.4 | 13.5 | 15.6 | 12.58 ± 2.65 |
| mattcl-py | input-chancalan | 22.1 ± 0.8 | 21.0 | 25.3 | 18.92 ± 4.01 |
| pting | input-chancalan | 22.2 ± 0.8 | 21.2 | 24.9 | 18.97 ± 4.02 |
| pting | input-mattcl | 22.2 ± 0.7 | 21.4 | 24.8 | 19.04 ± 4.02 |
| mattcl-py | input-mattcl | 22.3 ± 0.8 | 21.1 | 25.1 | 19.07 ± 4.04 |
| mattcl-py | input-lanjian | 22.6 ± 0.5 | 21.7 | 25.3 | 19.32 ± 4.06 |
| pting | input-lanjian | 22.6 ± 0.7 | 21.9 | 27.2 | 19.34 ± 4.09 |
| mattcl-py | input-kcen | 22.7 ± 0.8 | 22.0 | 26.3 | 19.43 ± 4.11 |
| pting | input-kcen | 22.7 ± 0.9 | 21.7 | 26.8 | 19.47 ± 4.14 |
| mattcl-py | input-pting | 22.9 ± 0.8 | 21.8 | 25.7 | 19.63 ± 4.16 |
| pting | input-pting | 23.0 ± 0.7 | 21.9 | 25.8 | 19.66 ± 4.16 |
| chancalan | input-chancalan | 23.4 ± 0.7 | 22.3 | 26.6 | 20.05 ± 4.23 |
| chancalan | input-mattcl | 23.7 ± 0.6 | 22.6 | 26.3 | 20.25 ± 4.27 |
| chancalan | input-lanjian | 24.0 ± 0.7 | 23.0 | 26.8 | 20.58 ± 4.34 |
| chancalan | input-kcen | 24.2 ± 0.7 | 23.0 | 26.9 | 20.68 ± 4.36 |
| chancalan | input-pting | 24.6 ± 0.9 | 23.5 | 28.2 | 21.06 ± 4.46 |
| kcen | input-chancalan | 27.7 ± 0.6 | 26.7 | 30.3 | 23.74 ± 4.99 |
| kcen | input-mattcl | 28.1 ± 0.9 | 26.9 | 31.3 | 24.05 ± 5.08 |
| kcen | input-lanjian | 28.9 ± 0.8 | 27.6 | 31.6 | 24.75 ± 5.22 |
| kcen | input-kcen | 29.1 ± 0.7 | 27.6 | 31.3 | 24.94 ± 5.25 |
| kcen | input-pting | 29.5 ± 0.8 | 28.5 | 32.9 | 25.26 ± 5.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|