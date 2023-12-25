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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.9 | 2.0 | 1.00 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.9 | 2.1 | 1.02 ± 0.30 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.9 | 1.9 | 1.03 ± 0.30 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.03 ± 0.31 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.9 | 1.9 | 1.04 ± 0.31 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.0 | 1.07 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.08 ± 0.32 |
| mattcl | input-pting | 1.4 ± 0.3 | 0.9 | 2.0 | 1.11 ± 0.33 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.0 | 2.1 | 1.13 ± 0.33 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.2 | 1.13 ± 0.34 |
| mattcl-ts | input-chancalan | 14.8 ± 0.3 | 13.8 | 15.5 | 12.14 ± 2.65 |
| mattcl-ts | input-mattcl | 14.9 ± 0.3 | 14.2 | 16.0 | 12.29 ± 2.69 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.2 | 16.1 | 12.41 ± 2.71 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.2 | 15.7 | 12.41 ± 2.71 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.4 | 15.9 | 12.42 ± 2.71 |
| pting | input-chancalan | 22.0 ± 1.1 | 20.8 | 31.7 | 18.05 ± 4.03 |
| mattcl-py | input-chancalan | 22.0 ± 0.8 | 20.9 | 24.8 | 18.07 ± 3.98 |
| mattcl-py | input-mattcl | 22.1 ± 0.7 | 21.0 | 25.1 | 18.22 ± 4.01 |
| pting | input-mattcl | 22.2 ± 0.7 | 20.9 | 25.3 | 18.23 ± 4.00 |
| pting | input-kcen | 22.5 ± 0.7 | 21.7 | 25.3 | 18.54 ± 4.08 |
| mattcl-py | input-lanjian | 22.7 ± 2.3 | 21.4 | 47.7 | 18.65 ± 4.48 |
| pting | input-pting | 22.7 ± 0.6 | 21.9 | 25.4 | 18.68 ± 4.09 |
| pting | input-lanjian | 22.8 ± 1.0 | 21.5 | 27.2 | 18.74 ± 4.16 |
| mattcl-py | input-pting | 22.9 ± 0.8 | 22.0 | 27.0 | 18.86 ± 4.16 |
| mattcl-py | input-kcen | 23.2 ± 3.8 | 21.5 | 56.3 | 19.07 ± 5.20 |
| chancalan | input-chancalan | 23.2 ± 0.9 | 21.9 | 26.7 | 19.11 ± 4.22 |
| chancalan | input-mattcl | 23.6 ± 0.9 | 22.2 | 27.4 | 19.43 ± 4.29 |
| chancalan | input-kcen | 23.9 ± 0.8 | 22.9 | 27.3 | 19.66 ± 4.32 |
| chancalan | input-lanjian | 24.0 ± 0.9 | 23.0 | 27.3 | 19.74 ± 4.36 |
| chancalan | input-pting | 24.4 ± 0.9 | 23.4 | 27.6 | 20.03 ± 4.41 |
| kcen | input-chancalan | 27.6 ± 0.7 | 26.7 | 30.5 | 22.69 ± 4.97 |
| kcen | input-mattcl | 28.1 ± 1.2 | 26.9 | 33.8 | 23.08 ± 5.11 |
| kcen | input-kcen | 28.9 ± 0.9 | 27.7 | 32.6 | 23.79 ± 5.23 |
| kcen | input-lanjian | 29.0 ± 0.9 | 27.6 | 32.2 | 23.88 ± 5.25 |
| kcen | input-pting | 29.4 ± 0.8 | 28.1 | 32.6 | 24.17 ± 5.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|