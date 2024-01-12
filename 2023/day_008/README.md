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
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.9 | 1.9 | 1.02 ± 0.30 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.31 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.9 | 2.1 | 1.06 ± 0.31 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.2 | 1.06 ± 0.32 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.07 ± 0.32 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.09 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.10 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.9 | 2.2 | 1.12 ± 0.31 |
| lanjian | input-pting | 1.4 ± 0.3 | 0.9 | 2.2 | 1.15 ± 0.35 |
| mattcl-ts | input-chancalan | 15.0 ± 0.4 | 14.0 | 16.6 | 12.62 ± 2.70 |
| mattcl-ts | input-mattcl | 15.2 ± 0.4 | 14.4 | 16.9 | 12.75 ± 2.73 |
| mattcl-ts | input-kcen | 15.2 ± 0.4 | 14.4 | 16.4 | 12.81 ± 2.74 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.4 | 16.6 | 12.82 ± 2.74 |
| mattcl-ts | input-pting | 15.4 ± 0.4 | 14.6 | 16.5 | 12.90 ± 2.76 |
| pting | input-chancalan | 22.1 ± 0.7 | 21.1 | 25.1 | 18.59 ± 4.00 |
| mattcl-py | input-chancalan | 22.2 ± 0.8 | 20.9 | 25.4 | 18.70 ± 4.04 |
| mattcl-py | input-mattcl | 22.4 ± 0.8 | 21.2 | 25.6 | 18.81 ± 4.06 |
| pting | input-mattcl | 22.5 ± 0.7 | 21.5 | 25.0 | 18.90 ± 4.07 |
| mattcl-py | input-lanjian | 22.9 ± 0.9 | 21.8 | 25.8 | 19.24 ± 4.15 |
| pting | input-kcen | 22.9 ± 0.9 | 21.4 | 29.8 | 19.24 ± 4.16 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.7 | 26.3 | 19.26 ± 4.15 |
| mattcl-py | input-kcen | 23.0 ± 0.8 | 21.5 | 25.5 | 19.31 ± 4.16 |
| pting | input-pting | 23.2 ± 0.8 | 22.1 | 26.5 | 19.52 ± 4.20 |
| mattcl-py | input-pting | 23.2 ± 0.9 | 21.9 | 26.0 | 19.54 ± 4.22 |
| chancalan | input-chancalan | 23.5 ± 0.6 | 22.7 | 26.5 | 19.74 ± 4.23 |
| chancalan | input-mattcl | 23.7 ± 0.7 | 22.3 | 27.0 | 19.93 ± 4.28 |
| chancalan | input-lanjian | 24.3 ± 0.8 | 23.1 | 27.0 | 20.46 ± 4.40 |
| chancalan | input-kcen | 24.4 ± 1.1 | 23.1 | 32.6 | 20.53 ± 4.47 |
| chancalan | input-pting | 24.6 ± 1.0 | 23.5 | 30.0 | 20.70 ± 4.47 |
| kcen | input-chancalan | 28.2 ± 1.0 | 26.7 | 31.0 | 23.73 ± 5.11 |
| kcen | input-mattcl | 28.5 ± 0.9 | 26.8 | 31.0 | 23.93 ± 5.15 |
| kcen | input-kcen | 29.3 ± 0.9 | 28.2 | 32.8 | 24.65 ± 5.29 |
| kcen | input-pting | 29.7 ± 0.9 | 28.4 | 32.3 | 24.97 ± 5.36 |
| kcen | input-lanjian | 30.2 ± 6.2 | 27.4 | 74.7 | 25.35 ± 7.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|