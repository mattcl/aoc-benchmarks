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
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.9 | 2.0 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.3 | 0.9 | 1.9 | 1.01 ± 0.29 |
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.9 | 1.9 | 1.02 ± 0.29 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.05 ± 0.30 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.1 | 1.05 ± 0.30 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.4 | 1.05 ± 0.29 |
| mattcl | input-kcen | 1.3 ± 0.3 | 1.0 | 2.2 | 1.06 ± 0.29 |
| lanjian | input-lanjian | 1.4 ± 0.3 | 0.9 | 2.3 | 1.10 ± 0.31 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.0 | 2.2 | 1.10 ± 0.31 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.2 | 1.12 ± 0.31 |
| mattcl-ts | input-chancalan | 15.0 ± 0.3 | 14.0 | 16.3 | 11.95 ± 2.32 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.0 | 16.1 | 12.04 ± 2.33 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.3 | 16.2 | 12.07 ± 2.34 |
| mattcl-ts | input-kcen | 15.2 ± 0.3 | 14.5 | 16.2 | 12.15 ± 2.35 |
| mattcl-ts | input-pting | 15.3 ± 0.3 | 14.6 | 16.4 | 12.17 ± 2.36 |
| mattcl-py | input-chancalan | 22.1 ± 0.8 | 21.0 | 25.4 | 17.65 ± 3.45 |
| pting | input-chancalan | 22.2 ± 0.8 | 21.0 | 25.8 | 17.69 ± 3.47 |
| pting | input-mattcl | 22.4 ± 0.9 | 21.2 | 26.3 | 17.86 ± 3.52 |
| mattcl-py | input-mattcl | 22.5 ± 0.8 | 21.2 | 25.5 | 17.91 ± 3.51 |
| mattcl-py | input-lanjian | 22.8 ± 0.9 | 21.7 | 27.0 | 18.14 ± 3.56 |
| pting | input-lanjian | 22.8 ± 0.7 | 21.8 | 26.3 | 18.21 ± 3.55 |
| pting | input-kcen | 22.9 ± 0.9 | 21.9 | 26.8 | 18.27 ± 3.58 |
| mattcl-py | input-pting | 22.9 ± 0.7 | 22.1 | 26.0 | 18.30 ± 3.57 |
| mattcl-py | input-kcen | 23.1 ± 2.1 | 21.5 | 42.1 | 18.41 ± 3.93 |
| pting | input-pting | 23.1 ± 0.9 | 21.7 | 26.3 | 18.44 ± 3.62 |
| chancalan | input-chancalan | 23.5 ± 0.8 | 22.4 | 27.1 | 18.74 ± 3.67 |
| chancalan | input-mattcl | 23.8 ± 0.8 | 22.7 | 26.4 | 18.97 ± 3.70 |
| chancalan | input-lanjian | 24.4 ± 0.8 | 23.2 | 27.6 | 19.45 ± 3.80 |
| chancalan | input-kcen | 24.6 ± 1.0 | 22.7 | 27.5 | 19.61 ± 3.86 |
| chancalan | input-pting | 24.8 ± 1.2 | 23.2 | 30.0 | 19.74 ± 3.91 |
| kcen | input-chancalan | 28.2 ± 0.7 | 26.9 | 30.9 | 22.51 ± 4.37 |
| kcen | input-mattcl | 28.4 ± 1.1 | 26.9 | 32.2 | 22.64 ± 4.44 |
| kcen | input-lanjian | 29.2 ± 0.7 | 27.6 | 32.1 | 23.25 ± 4.51 |
| kcen | input-kcen | 29.3 ± 0.8 | 27.8 | 32.2 | 23.35 ± 4.53 |
| kcen | input-pting | 29.6 ± 1.0 | 28.1 | 32.6 | 23.57 ± 4.60 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|