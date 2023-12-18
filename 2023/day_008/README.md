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
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.0 | 1.02 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.9 | 1.9 | 1.05 ± 0.30 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.9 | 1.8 | 1.06 ± 0.30 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.0 | 1.06 ± 0.32 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.2 | 1.08 ± 0.32 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.10 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.15 ± 0.34 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.2 | 1.19 ± 0.35 |
| mattcl-ts | input-chancalan | 14.8 ± 0.3 | 13.9 | 15.6 | 12.64 ± 2.68 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.2 | 15.9 | 12.77 ± 2.71 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.2 | 15.9 | 12.85 ± 2.72 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.0 | 16.3 | 12.85 ± 2.72 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.2 | 16.1 | 12.85 ± 2.72 |
| mattcl-py | input-chancalan | 21.9 ± 0.6 | 20.9 | 24.6 | 18.69 ± 3.97 |
| pting | input-chancalan | 22.2 ± 0.8 | 21.1 | 25.7 | 18.91 ± 4.05 |
| mattcl-py | input-mattcl | 22.2 ± 0.6 | 21.3 | 25.4 | 18.96 ± 4.04 |
| pting | input-mattcl | 22.5 ± 0.9 | 21.4 | 25.4 | 19.16 ± 4.12 |
| pting | input-kcen | 22.7 ± 0.7 | 21.6 | 25.6 | 19.34 ± 4.12 |
| mattcl-py | input-lanjian | 22.8 ± 0.9 | 21.5 | 26.1 | 19.40 ± 4.16 |
| pting | input-lanjian | 22.8 ± 0.8 | 21.7 | 26.3 | 19.43 ± 4.15 |
| mattcl-py | input-kcen | 22.9 ± 1.1 | 21.9 | 32.2 | 19.48 ± 4.22 |
| pting | input-pting | 23.1 ± 0.8 | 21.7 | 25.5 | 19.66 ± 4.20 |
| mattcl-py | input-pting | 23.1 ± 0.8 | 22.0 | 26.4 | 19.66 ± 4.20 |
| chancalan | input-chancalan | 23.4 ± 0.8 | 22.3 | 26.5 | 19.92 ± 4.26 |
| chancalan | input-mattcl | 23.6 ± 0.7 | 22.7 | 27.3 | 20.13 ± 4.28 |
| chancalan | input-lanjian | 24.1 ± 0.8 | 23.1 | 27.8 | 20.55 ± 4.39 |
| chancalan | input-pting | 24.6 ± 0.8 | 23.6 | 27.3 | 20.94 ± 4.46 |
| chancalan | input-kcen | 24.7 ± 3.1 | 23.0 | 52.5 | 21.07 ± 5.19 |
| kcen | input-chancalan | 28.0 ± 1.1 | 27.0 | 31.6 | 23.91 ± 5.12 |
| kcen | input-mattcl | 28.1 ± 0.6 | 27.2 | 30.6 | 23.92 ± 5.07 |
| kcen | input-lanjian | 29.1 ± 0.8 | 27.7 | 31.4 | 24.80 ± 5.27 |
| kcen | input-kcen | 29.1 ± 0.7 | 27.9 | 31.3 | 24.83 ± 5.27 |
| kcen | input-pting | 29.7 ± 0.9 | 28.2 | 32.5 | 25.32 ± 5.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|