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
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.9 | 2.1 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.1 | 1.00 ± 0.28 |
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.01 ± 0.29 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 1.9 | 1.02 ± 0.28 |
| mattcl | input-pting | 1.3 ± 0.2 | 1.0 | 1.9 | 1.03 ± 0.27 |
| lanjian | input-lanjian | 1.4 ± 0.3 | 0.9 | 2.0 | 1.06 ± 0.28 |
| lanjian | input-chancalan | 1.4 ± 0.3 | 0.9 | 2.1 | 1.09 ± 0.30 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.0 | 2.1 | 1.09 ± 0.28 |
| lanjian | input-kcen | 1.4 ± 0.2 | 1.0 | 2.2 | 1.10 ± 0.28 |
| mattcl | input-kcen | 1.4 ± 0.3 | 1.0 | 2.2 | 1.10 ± 0.30 |
| mattcl-ts | input-chancalan | 14.9 ± 0.4 | 14.0 | 16.2 | 11.61 ± 2.22 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 13.9 | 17.9 | 11.66 ± 2.23 |
| mattcl-ts | input-lanjian | 15.1 ± 0.4 | 13.6 | 17.5 | 11.69 ± 2.23 |
| mattcl-ts | input-pting | 15.1 ± 0.4 | 14.1 | 16.5 | 11.73 ± 2.24 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 14.1 | 17.3 | 11.74 ± 2.24 |
| mattcl-py | input-chancalan | 22.3 ± 0.9 | 21.1 | 25.7 | 17.30 ± 3.34 |
| mattcl-py | input-mattcl | 22.3 ± 0.7 | 21.0 | 25.1 | 17.35 ± 3.32 |
| pting | input-chancalan | 22.4 ± 0.8 | 20.9 | 25.3 | 17.42 ± 3.36 |
| pting | input-mattcl | 22.6 ± 0.8 | 21.6 | 25.6 | 17.52 ± 3.37 |
| mattcl-py | input-lanjian | 22.7 ± 0.7 | 21.7 | 25.4 | 17.64 ± 3.39 |
| mattcl-py | input-kcen | 22.9 ± 0.8 | 21.7 | 25.7 | 17.77 ± 3.42 |
| pting | input-kcen | 22.9 ± 0.9 | 21.5 | 26.8 | 17.79 ± 3.44 |
| pting | input-lanjian | 23.0 ± 0.8 | 22.0 | 26.1 | 17.85 ± 3.44 |
| mattcl-py | input-pting | 23.2 ± 0.8 | 21.9 | 26.2 | 18.04 ± 3.48 |
| pting | input-pting | 23.5 ± 2.6 | 21.9 | 49.9 | 18.28 ± 3.99 |
| chancalan | input-chancalan | 23.6 ± 0.7 | 22.5 | 26.2 | 18.30 ± 3.51 |
| chancalan | input-mattcl | 23.9 ± 0.8 | 22.9 | 27.4 | 18.59 ± 3.57 |
| chancalan | input-lanjian | 24.4 ± 0.8 | 23.1 | 27.6 | 18.92 ± 3.64 |
| chancalan | input-kcen | 24.5 ± 0.8 | 23.0 | 27.3 | 19.00 ± 3.64 |
| chancalan | input-pting | 24.7 ± 0.7 | 23.6 | 27.7 | 19.18 ± 3.68 |
| kcen | input-chancalan | 28.1 ± 0.9 | 26.7 | 31.5 | 21.84 ± 4.19 |
| kcen | input-mattcl | 28.3 ± 0.9 | 26.4 | 30.7 | 21.97 ± 4.22 |
| kcen | input-lanjian | 29.2 ± 0.8 | 27.9 | 32.5 | 22.71 ± 4.34 |
| kcen | input-kcen | 29.4 ± 1.0 | 27.8 | 32.7 | 22.83 ± 4.39 |
| kcen | input-pting | 29.6 ± 0.9 | 28.4 | 34.3 | 23.02 ± 4.41 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|