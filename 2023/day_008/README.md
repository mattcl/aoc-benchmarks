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
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.30 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.8 | 1.02 ± 0.30 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.0 | 1.07 ± 0.33 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.9 | 1.07 ± 0.32 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 1.8 | 1.08 ± 0.32 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.8 | 2.4 | 1.10 ± 0.34 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 1.9 | 1.10 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.15 ± 0.34 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.16 ± 0.34 |
| mattcl-ts | input-chancalan | 14.9 ± 0.3 | 14.0 | 15.8 | 12.92 ± 2.76 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 14.0 | 16.7 | 13.05 ± 2.79 |
| mattcl-ts | input-kcen | 15.0 ± 0.4 | 14.2 | 16.4 | 13.08 ± 2.80 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 13.8 | 16.2 | 13.09 ± 2.80 |
| mattcl-ts | input-pting | 15.1 ± 0.4 | 14.2 | 16.5 | 13.10 ± 2.80 |
| mattcl-py | input-chancalan | 22.2 ± 0.5 | 21.1 | 25.1 | 19.27 ± 4.12 |
| mattcl-py | input-mattcl | 22.5 ± 1.2 | 21.2 | 32.6 | 19.60 ± 4.30 |
| pting | input-mattcl | 22.6 ± 0.8 | 21.5 | 25.6 | 19.61 ± 4.22 |
| pting | input-chancalan | 22.6 ± 3.0 | 21.0 | 55.7 | 19.63 ± 4.91 |
| mattcl-py | input-lanjian | 22.8 ± 0.8 | 21.9 | 26.5 | 19.81 ± 4.26 |
| mattcl-py | input-kcen | 23.0 ± 0.7 | 21.8 | 25.8 | 20.02 ± 4.30 |
| mattcl-py | input-pting | 23.1 ± 0.6 | 21.9 | 25.6 | 20.04 ± 4.29 |
| pting | input-lanjian | 23.1 ± 1.0 | 21.9 | 27.0 | 20.07 ± 4.34 |
| pting | input-kcen | 23.1 ± 0.9 | 21.5 | 28.0 | 20.08 ± 4.34 |
| pting | input-pting | 23.3 ± 0.9 | 21.8 | 26.6 | 20.25 ± 4.38 |
| chancalan | input-chancalan | 23.9 ± 0.8 | 22.8 | 27.1 | 20.75 ± 4.46 |
| chancalan | input-mattcl | 24.2 ± 0.8 | 22.9 | 27.1 | 21.04 ± 4.52 |
| chancalan | input-lanjian | 24.6 ± 0.8 | 23.4 | 27.4 | 21.39 ± 4.59 |
| chancalan | input-kcen | 24.7 ± 0.8 | 23.3 | 27.9 | 21.52 ± 4.62 |
| chancalan | input-pting | 25.0 ± 0.8 | 23.5 | 27.7 | 21.74 ± 4.67 |
| kcen | input-chancalan | 28.2 ± 0.9 | 26.8 | 31.7 | 24.52 ± 5.27 |
| kcen | input-mattcl | 28.3 ± 0.9 | 27.1 | 31.9 | 24.62 ± 5.29 |
| kcen | input-lanjian | 29.4 ± 1.0 | 27.7 | 32.5 | 25.54 ± 5.50 |
| kcen | input-kcen | 29.6 ± 1.1 | 28.1 | 37.3 | 25.75 ± 5.56 |
| kcen | input-pting | 29.8 ± 1.1 | 28.5 | 35.5 | 25.93 ± 5.60 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|