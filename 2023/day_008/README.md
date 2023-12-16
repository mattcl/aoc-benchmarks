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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.8 | 1.9 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.8 | 1.00 ± 0.30 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.29 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.04 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.9 | 1.06 ± 0.33 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.9 | 1.07 ± 0.31 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.0 | 1.08 ± 0.33 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.08 ± 0.34 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 1.9 | 1.12 ± 0.31 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.16 ± 0.34 |
| mattcl-ts | input-chancalan | 14.8 ± 0.3 | 13.9 | 16.0 | 12.99 ± 2.74 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.2 | 15.7 | 13.12 ± 2.76 |
| mattcl-ts | input-kcen | 15.0 ± 0.3 | 14.1 | 15.9 | 13.17 ± 2.77 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.2 | 16.3 | 13.18 ± 2.77 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.3 | 16.3 | 13.19 ± 2.77 |
| mattcl-py | input-chancalan | 22.0 ± 0.6 | 21.2 | 25.1 | 19.29 ± 4.07 |
| pting | input-chancalan | 22.1 ± 0.7 | 21.3 | 26.3 | 19.35 ± 4.10 |
| mattcl-py | input-mattcl | 22.2 ± 0.6 | 21.0 | 24.9 | 19.42 ± 4.10 |
| pting | input-mattcl | 22.3 ± 0.6 | 21.6 | 25.7 | 19.52 ± 4.12 |
| pting | input-kcen | 22.6 ± 0.7 | 21.7 | 25.4 | 19.82 ± 4.19 |
| mattcl-py | input-lanjian | 22.8 ± 0.9 | 21.8 | 26.0 | 19.91 ± 4.24 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.8 | 25.7 | 20.00 ± 4.25 |
| mattcl-py | input-kcen | 22.9 ± 1.1 | 21.8 | 30.9 | 20.01 ± 4.29 |
| pting | input-pting | 22.9 ± 0.8 | 21.8 | 26.6 | 20.06 ± 4.25 |
| mattcl-py | input-pting | 23.0 ± 0.8 | 22.0 | 26.4 | 20.14 ± 4.27 |
| chancalan | input-chancalan | 23.5 ± 0.8 | 22.4 | 26.8 | 20.54 ± 4.35 |
| chancalan | input-mattcl | 23.7 ± 0.9 | 22.7 | 29.5 | 20.76 ± 4.42 |
| chancalan | input-lanjian | 24.1 ± 0.7 | 22.8 | 27.2 | 21.11 ± 4.46 |
| chancalan | input-kcen | 24.3 ± 0.8 | 23.4 | 27.4 | 21.28 ± 4.50 |
| chancalan | input-pting | 24.6 ± 1.1 | 23.5 | 33.1 | 21.55 ± 4.62 |
| kcen | input-chancalan | 27.9 ± 0.9 | 26.7 | 30.8 | 24.44 ± 5.17 |
| kcen | input-mattcl | 28.3 ± 0.9 | 27.1 | 31.0 | 24.77 ± 5.25 |
| kcen | input-lanjian | 29.2 ± 0.9 | 27.9 | 31.9 | 25.52 ± 5.40 |
| kcen | input-pting | 29.6 ± 0.8 | 28.5 | 32.6 | 25.87 ± 5.46 |
| kcen | input-kcen | 30.1 ± 5.5 | 27.9 | 67.0 | 26.30 ± 7.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|