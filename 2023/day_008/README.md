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
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 2.5 | 1.00 |
| mattcl | input-chancalan | 1.4 ± 0.2 | 1.1 | 2.1 | 1.02 ± 0.23 |
| lanjian | input-mattcl | 1.5 ± 0.3 | 1.1 | 2.5 | 1.05 ± 0.25 |
| lanjian | input-chancalan | 1.5 ± 0.3 | 1.2 | 2.5 | 1.07 ± 0.26 |
| mattcl | input-lanjian | 1.6 ± 0.3 | 1.1 | 2.2 | 1.10 ± 0.26 |
| lanjian | input-lanjian | 1.6 ± 0.2 | 1.1 | 2.3 | 1.10 ± 0.25 |
| mattcl | input-kcen | 1.6 ± 0.2 | 1.2 | 2.2 | 1.13 ± 0.25 |
| lanjian | input-pting | 1.6 ± 0.4 | 1.2 | 4.4 | 1.14 ± 0.33 |
| mattcl | input-pting | 1.6 ± 0.5 | 1.2 | 3.8 | 1.14 ± 0.37 |
| lanjian | input-kcen | 1.7 ± 0.2 | 1.3 | 2.5 | 1.18 ± 0.26 |
| mattcl-ts | input-pting | 15.9 ± 0.6 | 15.0 | 19.1 | 11.24 ± 1.89 |
| mattcl-ts | input-lanjian | 15.9 ± 0.6 | 15.0 | 22.3 | 11.27 ± 1.90 |
| mattcl-ts | input-kcen | 16.1 ± 0.5 | 15.0 | 17.8 | 11.36 ± 1.90 |
| mattcl-ts | input-mattcl | 16.1 ± 3.8 | 14.6 | 55.8 | 11.42 ± 3.29 |
| mattcl-ts | input-chancalan | 22.2 ± 14.9 | 15.1 | 95.4 | 15.72 ± 10.84 |
| mattcl-py | input-mattcl | 23.0 ± 0.8 | 21.6 | 25.7 | 16.23 ± 2.72 |
| pting | input-mattcl | 23.5 ± 3.0 | 21.8 | 55.1 | 16.62 ± 3.45 |
| pting | input-chancalan | 23.6 ± 0.7 | 22.6 | 26.0 | 16.71 ± 2.78 |
| pting | input-lanjian | 23.8 ± 0.6 | 22.7 | 26.3 | 16.79 ± 2.79 |
| pting | input-pting | 24.0 ± 0.6 | 22.6 | 26.3 | 16.94 ± 2.81 |
| pting | input-kcen | 24.0 ± 0.8 | 23.0 | 29.6 | 16.94 ± 2.84 |
| mattcl-py | input-lanjian | 24.1 ± 0.8 | 22.3 | 28.7 | 17.05 ± 2.86 |
| mattcl-py | input-kcen | 24.1 ± 0.6 | 23.0 | 26.1 | 17.05 ± 2.83 |
| mattcl-py | input-pting | 24.4 ± 1.6 | 22.0 | 33.0 | 17.27 ± 3.06 |
| chancalan | input-mattcl | 25.0 ± 0.6 | 23.9 | 27.1 | 17.65 ± 2.93 |
| chancalan | input-lanjian | 25.5 ± 1.2 | 24.0 | 37.3 | 18.04 ± 3.09 |
| chancalan | input-kcen | 25.7 ± 0.4 | 24.8 | 27.1 | 18.17 ± 3.00 |
| chancalan | input-pting | 26.0 ± 2.3 | 24.1 | 49.1 | 18.37 ± 3.42 |
| mattcl-py | input-chancalan | 26.1 ± 6.1 | 22.5 | 44.8 | 18.46 ± 5.29 |
| chancalan | input-chancalan | 26.9 ± 1.5 | 24.8 | 30.5 | 19.00 ± 3.29 |
| kcen | input-mattcl | 29.1 ± 1.0 | 27.5 | 31.9 | 20.57 ± 3.45 |
| kcen | input-chancalan | 29.9 ± 0.6 | 29.0 | 32.5 | 21.16 ± 3.50 |
| kcen | input-lanjian | 30.2 ± 0.6 | 29.0 | 32.9 | 21.36 ± 3.53 |
| kcen | input-kcen | 31.0 ± 0.6 | 29.9 | 33.1 | 21.90 ± 3.62 |
| kcen | input-pting | 31.6 ± 2.4 | 29.4 | 46.0 | 22.33 ± 4.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|