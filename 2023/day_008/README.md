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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.9 | 1.00 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.9 | 1.01 ± 0.30 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.1 | 1.01 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 2.0 | 1.03 ± 0.30 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.9 | 1.03 ± 0.30 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.0 | 1.05 ± 0.31 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.05 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.09 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 2.2 | 1.09 ± 0.31 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.12 ± 0.32 |
| mattcl-ts | input-chancalan | 15.0 ± 0.3 | 14.1 | 15.9 | 12.51 ± 2.71 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.1 | 17.0 | 12.62 ± 2.74 |
| mattcl-ts | input-lanjian | 15.2 ± 0.4 | 14.4 | 16.3 | 12.72 ± 2.76 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 14.3 | 16.5 | 12.75 ± 2.77 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.5 | 16.8 | 12.80 ± 2.79 |
| pting | input-chancalan | 22.1 ± 0.7 | 21.0 | 25.3 | 18.48 ± 4.04 |
| mattcl-py | input-chancalan | 22.3 ± 1.0 | 21.3 | 30.0 | 18.61 ± 4.11 |
| mattcl-py | input-mattcl | 22.4 ± 0.8 | 21.3 | 25.5 | 18.69 ± 4.09 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.4 | 26.2 | 18.71 ± 4.09 |
| mattcl-py | input-kcen | 22.7 ± 0.7 | 21.9 | 25.2 | 18.99 ± 4.14 |
| mattcl-py | input-lanjian | 22.8 ± 0.9 | 21.6 | 26.7 | 19.03 ± 4.18 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.8 | 25.7 | 19.10 ± 4.18 |
| pting | input-kcen | 22.9 ± 1.1 | 21.6 | 31.2 | 19.14 ± 4.23 |
| pting | input-pting | 22.9 ± 0.6 | 21.5 | 26.0 | 19.15 ± 4.16 |
| mattcl-py | input-pting | 23.0 ± 0.7 | 22.0 | 26.0 | 19.22 ± 4.19 |
| chancalan | input-chancalan | 23.6 ± 0.8 | 22.6 | 26.6 | 19.71 ± 4.31 |
| chancalan | input-mattcl | 24.1 ± 2.4 | 22.6 | 40.8 | 20.15 ± 4.78 |
| chancalan | input-lanjian | 24.2 ± 0.8 | 22.7 | 27.5 | 20.23 ± 4.42 |
| chancalan | input-kcen | 24.2 ± 0.9 | 23.0 | 27.8 | 20.23 ± 4.43 |
| chancalan | input-pting | 24.8 ± 0.9 | 23.5 | 28.4 | 20.67 ± 4.53 |
| kcen | input-chancalan | 28.0 ± 0.8 | 26.8 | 30.8 | 23.38 ± 5.09 |
| kcen | input-mattcl | 28.3 ± 0.8 | 27.0 | 31.3 | 23.63 ± 5.15 |
| kcen | input-lanjian | 29.2 ± 0.9 | 27.9 | 31.5 | 24.41 ± 5.32 |
| kcen | input-kcen | 29.2 ± 0.9 | 28.0 | 32.9 | 24.42 ± 5.33 |
| kcen | input-pting | 29.5 ± 0.8 | 28.2 | 32.7 | 24.61 ± 5.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|