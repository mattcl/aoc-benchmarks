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
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.8 | 1.03 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.8 | 1.03 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.0 | 1.04 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 1.9 | 1.04 ± 0.31 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.0 | 1.04 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.07 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.08 ± 0.32 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.9 | 2.1 | 1.13 ± 0.32 |
| mattcl | input-pting | 1.4 ± 3.3 | 0.8 | 48.0 | 1.20 ± 2.84 |
| mattcl-ts | input-chancalan | 15.0 ± 0.3 | 14.1 | 16.0 | 12.77 ± 2.68 |
| mattcl-ts | input-mattcl | 15.1 ± 0.3 | 14.0 | 15.9 | 12.82 ± 2.69 |
| mattcl-ts | input-lanjian | 15.2 ± 0.4 | 14.4 | 17.0 | 12.95 ± 2.72 |
| mattcl-ts | input-kcen | 15.2 ± 0.4 | 14.4 | 16.8 | 12.97 ± 2.72 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.4 | 17.1 | 13.04 ± 2.74 |
| mattcl-py | input-chancalan | 22.2 ± 0.7 | 20.8 | 25.4 | 18.89 ± 3.99 |
| pting | input-chancalan | 22.2 ± 0.8 | 20.8 | 25.9 | 18.91 ± 4.01 |
| pting | input-mattcl | 22.4 ± 1.0 | 20.9 | 25.7 | 19.11 ± 4.07 |
| mattcl-py | input-kcen | 22.8 ± 0.6 | 21.8 | 26.1 | 19.39 ± 4.08 |
| pting | input-kcen | 22.8 ± 0.7 | 21.8 | 25.9 | 19.41 ± 4.10 |
| mattcl-py | input-lanjian | 22.9 ± 0.8 | 21.5 | 26.2 | 19.48 ± 4.13 |
| mattcl-py | input-mattcl | 22.9 ± 4.6 | 21.3 | 74.4 | 19.51 ± 5.65 |
| pting | input-lanjian | 22.9 ± 0.9 | 21.9 | 26.2 | 19.53 ± 4.15 |
| pting | input-pting | 23.0 ± 0.8 | 21.7 | 26.7 | 19.61 ± 4.15 |
| mattcl-py | input-pting | 23.2 ± 0.8 | 22.1 | 27.1 | 19.79 ± 4.19 |
| chancalan | input-chancalan | 23.6 ± 0.7 | 22.6 | 27.2 | 20.06 ± 4.23 |
| chancalan | input-mattcl | 23.6 ± 0.6 | 22.7 | 26.8 | 20.09 ± 4.22 |
| chancalan | input-kcen | 24.4 ± 0.7 | 23.1 | 27.6 | 20.75 ± 4.38 |
| chancalan | input-lanjian | 24.4 ± 0.8 | 23.2 | 27.0 | 20.78 ± 4.39 |
| chancalan | input-pting | 24.6 ± 0.8 | 23.3 | 28.2 | 20.94 ± 4.42 |
| kcen | input-chancalan | 28.0 ± 0.9 | 26.8 | 31.2 | 23.88 ± 5.04 |
| kcen | input-mattcl | 28.2 ± 0.8 | 26.9 | 32.3 | 24.02 ± 5.06 |
| kcen | input-lanjian | 29.3 ± 1.0 | 27.9 | 32.5 | 24.94 ± 5.27 |
| kcen | input-kcen | 29.3 ± 0.8 | 28.2 | 32.8 | 24.95 ± 5.26 |
| kcen | input-pting | 29.8 ± 1.0 | 28.5 | 33.2 | 25.39 ± 5.37 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|