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
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.8 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.8 | 1.01 ± 0.31 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.1 | 1.01 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.02 ± 0.30 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.8 | 1.02 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 1.9 | 1.04 ± 0.31 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.9 | 1.9 | 1.04 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 1.9 | 1.08 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.08 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.12 ± 0.33 |
| mattcl-ts | input-chancalan | 14.5 ± 0.3 | 13.6 | 15.5 | 12.27 ± 2.60 |
| mattcl-ts | input-lanjian | 14.8 ± 0.3 | 13.9 | 16.0 | 12.54 ± 2.66 |
| mattcl-ts | input-kcen | 14.9 ± 0.3 | 14.0 | 15.8 | 12.58 ± 2.67 |
| mattcl-ts | input-pting | 14.9 ± 0.3 | 13.8 | 15.9 | 12.60 ± 2.67 |
| mattcl-ts | input-mattcl | 15.2 ± 4.0 | 13.7 | 51.0 | 12.89 ± 4.34 |
| mattcl-py | input-chancalan | 21.9 ± 0.8 | 21.1 | 25.2 | 18.55 ± 3.97 |
| pting | input-chancalan | 22.0 ± 0.9 | 21.0 | 25.2 | 18.63 ± 4.00 |
| mattcl-py | input-mattcl | 22.1 ± 0.6 | 21.2 | 25.6 | 18.72 ± 3.98 |
| pting | input-mattcl | 22.2 ± 0.7 | 21.3 | 25.1 | 18.80 ± 4.01 |
| mattcl-py | input-lanjian | 22.5 ± 0.8 | 21.4 | 26.2 | 19.09 ± 4.08 |
| pting | input-lanjian | 22.6 ± 0.7 | 21.5 | 25.9 | 19.11 ± 4.08 |
| pting | input-kcen | 22.7 ± 1.3 | 21.6 | 35.1 | 19.20 ± 4.20 |
| pting | input-pting | 22.8 ± 0.7 | 22.0 | 26.2 | 19.28 ± 4.10 |
| mattcl-py | input-pting | 22.8 ± 0.7 | 21.9 | 25.9 | 19.34 ± 4.12 |
| chancalan | input-chancalan | 23.4 ± 0.7 | 22.5 | 25.9 | 19.78 ± 4.21 |
| mattcl-py | input-kcen | 23.4 ± 5.7 | 21.5 | 69.4 | 19.80 ± 6.38 |
| chancalan | input-mattcl | 23.4 ± 0.6 | 22.5 | 26.0 | 19.85 ± 4.22 |
| chancalan | input-kcen | 23.9 ± 0.7 | 23.0 | 26.6 | 20.22 ± 4.30 |
| chancalan | input-lanjian | 24.2 ± 1.1 | 23.0 | 27.4 | 20.48 ± 4.41 |
| chancalan | input-pting | 24.4 ± 1.0 | 23.4 | 29.4 | 20.67 ± 4.43 |
| kcen | input-chancalan | 27.4 ± 0.8 | 26.5 | 30.5 | 23.21 ± 4.93 |
| kcen | input-mattcl | 28.1 ± 1.1 | 26.9 | 31.5 | 23.83 ± 5.11 |
| kcen | input-lanjian | 28.7 ± 0.7 | 27.8 | 30.8 | 24.31 ± 5.16 |
| kcen | input-kcen | 28.8 ± 0.8 | 27.7 | 32.3 | 24.39 ± 5.19 |
| kcen | input-pting | 29.5 ± 2.5 | 28.2 | 53.2 | 24.99 ± 5.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|