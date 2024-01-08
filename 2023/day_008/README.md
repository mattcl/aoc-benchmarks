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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.4 | 1.00 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.9 | 2.0 | 1.02 ± 0.29 |
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.1 | 1.03 ± 0.30 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 1.9 | 1.05 ± 0.30 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.0 | 1.06 ± 0.30 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.06 ± 0.31 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.1 | 1.08 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.6 | 1.09 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.2 | 1.0 | 2.0 | 1.13 ± 0.31 |
| lanjian | input-pting | 1.4 ± 0.2 | 1.0 | 2.3 | 1.15 ± 0.31 |
| mattcl-ts | input-chancalan | 14.9 ± 0.3 | 14.1 | 16.1 | 12.11 ± 2.49 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.2 | 15.9 | 12.18 ± 2.51 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.4 | 16.1 | 12.27 ± 2.52 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.1 | 16.1 | 12.28 ± 2.53 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.3 | 16.2 | 12.30 ± 2.53 |
| pting | input-chancalan | 22.2 ± 0.9 | 21.0 | 24.9 | 18.08 ± 3.77 |
| pting | input-mattcl | 22.3 ± 0.7 | 21.4 | 25.3 | 18.16 ± 3.76 |
| mattcl-py | input-chancalan | 22.5 ± 2.0 | 21.1 | 40.4 | 18.32 ± 4.07 |
| mattcl-py | input-mattcl | 22.7 ± 3.6 | 21.2 | 63.2 | 18.44 ± 4.80 |
| mattcl-py | input-kcen | 22.7 ± 0.6 | 21.7 | 26.1 | 18.46 ± 3.81 |
| pting | input-kcen | 22.7 ± 1.3 | 21.8 | 33.8 | 18.49 ± 3.92 |
| mattcl-py | input-lanjian | 22.7 ± 0.9 | 21.8 | 26.2 | 18.50 ± 3.85 |
| pting | input-lanjian | 22.8 ± 0.7 | 21.9 | 25.5 | 18.52 ± 3.83 |
| mattcl-py | input-pting | 22.9 ± 0.7 | 22.0 | 25.8 | 18.63 ± 3.85 |
| pting | input-pting | 23.0 ± 0.9 | 21.8 | 26.5 | 18.75 ± 3.90 |
| chancalan | input-chancalan | 23.6 ± 1.3 | 22.4 | 34.8 | 19.23 ± 4.07 |
| chancalan | input-mattcl | 23.7 ± 0.8 | 22.4 | 26.9 | 19.27 ± 3.99 |
| chancalan | input-lanjian | 24.3 ± 0.9 | 23.2 | 27.1 | 19.79 ± 4.11 |
| chancalan | input-pting | 24.5 ± 0.7 | 23.6 | 29.0 | 19.97 ± 4.13 |
| chancalan | input-kcen | 24.6 ± 2.9 | 23.2 | 55.8 | 20.00 ± 4.73 |
| kcen | input-chancalan | 27.9 ± 0.9 | 26.8 | 30.8 | 22.67 ± 4.70 |
| kcen | input-mattcl | 28.3 ± 1.0 | 27.0 | 31.4 | 23.03 ± 4.79 |
| kcen | input-kcen | 29.1 ± 0.8 | 28.0 | 32.5 | 23.67 ± 4.89 |
| kcen | input-lanjian | 29.2 ± 0.9 | 27.9 | 31.6 | 23.73 ± 4.91 |
| kcen | input-pting | 29.8 ± 0.9 | 28.4 | 33.0 | 24.22 ± 5.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|