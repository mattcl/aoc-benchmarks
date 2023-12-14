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
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.9 | 1.00 ± 0.30 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.9 | 2.1 | 1.01 ± 0.30 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.9 | 1.9 | 1.01 ± 0.30 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.9 | 1.9 | 1.01 ± 0.29 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.03 ± 0.29 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.04 ± 0.30 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 1.9 | 1.05 ± 0.29 |
| lanjian | input-pting | 1.4 ± 0.3 | 0.9 | 2.2 | 1.10 ± 0.31 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.2 | 1.11 ± 0.32 |
| mattcl-ts | input-chancalan | 15.1 ± 0.3 | 14.3 | 15.8 | 12.20 ± 2.50 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 14.6 | 16.6 | 12.40 ± 2.55 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.3 | 16.7 | 12.42 ± 2.56 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.3 | 16.5 | 12.42 ± 2.55 |
| mattcl-ts | input-mattcl | 16.1 ± 8.2 | 14.3 | 100.3 | 13.08 ± 7.13 |
| mattcl-py | input-chancalan | 22.1 ± 0.5 | 21.2 | 24.3 | 17.92 ± 3.68 |
| pting | input-chancalan | 22.3 ± 1.2 | 20.8 | 32.2 | 18.08 ± 3.82 |
| pting | input-mattcl | 22.4 ± 0.9 | 21.5 | 26.1 | 18.19 ± 3.78 |
| mattcl-py | input-mattcl | 22.5 ± 0.8 | 21.5 | 26.1 | 18.20 ± 3.78 |
| mattcl-py | input-lanjian | 22.9 ± 0.8 | 21.4 | 25.8 | 18.52 ± 3.84 |
| pting | input-kcen | 22.9 ± 0.9 | 21.9 | 26.6 | 18.59 ± 3.86 |
| mattcl-py | input-kcen | 23.0 ± 0.8 | 21.9 | 25.9 | 18.66 ± 3.86 |
| pting | input-pting | 23.0 ± 0.6 | 22.2 | 25.9 | 18.67 ± 3.85 |
| mattcl-py | input-pting | 23.2 ± 0.8 | 22.2 | 26.5 | 18.82 ± 3.89 |
| chancalan | input-chancalan | 23.6 ± 0.8 | 22.5 | 26.5 | 19.10 ± 3.95 |
| pting | input-lanjian | 23.7 ± 6.7 | 21.9 | 66.9 | 19.18 ± 6.69 |
| chancalan | input-mattcl | 23.9 ± 0.9 | 22.7 | 27.2 | 19.36 ± 4.03 |
| chancalan | input-kcen | 24.3 ± 0.8 | 23.3 | 27.4 | 19.72 ± 4.08 |
| chancalan | input-lanjian | 24.4 ± 0.8 | 23.1 | 27.4 | 19.74 ± 4.09 |
| chancalan | input-pting | 24.6 ± 0.8 | 23.3 | 27.2 | 19.96 ± 4.12 |
| kcen | input-chancalan | 28.2 ± 1.3 | 26.6 | 37.7 | 22.88 ± 4.79 |
| kcen | input-mattcl | 28.4 ± 1.0 | 27.0 | 31.4 | 23.02 ± 4.77 |
| kcen | input-kcen | 29.3 ± 0.9 | 27.9 | 32.6 | 23.77 ± 4.91 |
| kcen | input-lanjian | 29.4 ± 1.0 | 28.0 | 32.6 | 23.82 ± 4.94 |
| kcen | input-pting | 29.9 ± 1.0 | 28.5 | 32.6 | 24.20 ± 5.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|