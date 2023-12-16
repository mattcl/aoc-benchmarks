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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.8 | 1.00 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.8 | 1.8 | 1.04 ± 0.33 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.8 | 1.04 ± 0.33 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.9 | 1.07 ± 0.33 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.8 | 1.9 | 1.08 ± 0.34 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.8 | 1.8 | 1.10 ± 0.34 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.11 ± 0.36 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.8 | 2.0 | 1.15 ± 0.35 |
| lanjian | input-pting | 1.2 ± 0.3 | 0.9 | 2.1 | 1.15 ± 0.36 |
| lanjian | input-kcen | 1.2 ± 0.3 | 0.9 | 2.1 | 1.17 ± 0.36 |
| mattcl-ts | input-chancalan | 14.7 ± 0.3 | 13.9 | 15.7 | 13.91 ± 3.22 |
| mattcl-ts | input-mattcl | 14.9 ± 0.3 | 13.8 | 16.0 | 14.05 ± 3.25 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.1 | 16.1 | 14.12 ± 3.26 |
| mattcl-ts | input-kcen | 15.0 ± 0.3 | 14.2 | 16.1 | 14.15 ± 3.27 |
| mattcl-ts | input-pting | 15.0 ± 0.3 | 14.1 | 16.4 | 14.20 ± 3.28 |
| mattcl-py | input-chancalan | 21.9 ± 0.7 | 21.1 | 25.4 | 20.62 ± 4.79 |
| pting | input-chancalan | 21.9 ± 0.8 | 20.8 | 24.9 | 20.66 ± 4.82 |
| mattcl-py | input-mattcl | 22.1 ± 0.7 | 21.1 | 25.2 | 20.83 ± 4.84 |
| pting | input-mattcl | 22.2 ± 0.8 | 21.4 | 26.0 | 20.99 ± 4.90 |
| mattcl-py | input-kcen | 22.5 ± 0.7 | 21.6 | 25.5 | 21.25 ± 4.94 |
| mattcl-py | input-lanjian | 22.5 ± 0.8 | 21.5 | 26.1 | 21.26 ± 4.96 |
| pting | input-lanjian | 22.6 ± 0.7 | 21.6 | 25.3 | 21.29 ± 4.95 |
| pting | input-kcen | 22.6 ± 0.7 | 21.5 | 26.9 | 21.31 ± 4.96 |
| mattcl-py | input-pting | 22.8 ± 0.7 | 21.7 | 26.2 | 21.48 ± 5.00 |
| pting | input-pting | 23.1 ± 0.9 | 21.8 | 26.3 | 21.75 ± 5.09 |
| chancalan | input-chancalan | 23.2 ± 0.6 | 22.4 | 25.9 | 21.93 ± 5.08 |
| chancalan | input-mattcl | 23.5 ± 0.6 | 22.4 | 26.1 | 22.17 ± 5.14 |
| chancalan | input-lanjian | 24.0 ± 0.8 | 22.8 | 27.2 | 22.60 ± 5.25 |
| chancalan | input-kcen | 24.2 ± 1.0 | 23.1 | 26.9 | 22.79 ± 5.33 |
| chancalan | input-pting | 24.8 ± 4.2 | 23.3 | 69.4 | 23.44 ± 6.69 |
| kcen | input-chancalan | 27.8 ± 1.0 | 26.5 | 31.2 | 26.22 ± 6.10 |
| kcen | input-mattcl | 27.9 ± 0.9 | 26.8 | 30.9 | 26.36 ± 6.13 |
| kcen | input-lanjian | 28.8 ± 0.8 | 27.6 | 31.7 | 27.17 ± 6.30 |
| kcen | input-kcen | 29.0 ± 1.0 | 27.9 | 32.1 | 27.40 ± 6.38 |
| kcen | input-pting | 29.5 ± 1.0 | 28.3 | 33.6 | 27.83 ± 6.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|