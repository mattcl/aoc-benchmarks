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
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.9 | 2.0 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.9 | 1.00 ± 0.30 |
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.02 ± 0.30 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.1 | 1.04 ± 0.31 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 1.9 | 1.04 ± 0.31 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 1.9 | 1.04 ± 0.31 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.30 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.09 ± 0.31 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.10 ± 0.31 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.2 | 1.14 ± 0.33 |
| mattcl-ts | input-chancalan | 14.8 ± 0.4 | 13.6 | 15.8 | 12.04 ± 2.51 |
| mattcl-ts | input-mattcl | 14.9 ± 0.3 | 14.1 | 15.8 | 12.14 ± 2.53 |
| mattcl-ts | input-kcen | 15.0 ± 0.3 | 14.1 | 16.0 | 12.25 ± 2.55 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.0 | 16.9 | 12.25 ± 2.55 |
| mattcl-ts | input-pting | 15.0 ± 0.3 | 14.1 | 16.0 | 12.25 ± 2.55 |
| mattcl-py | input-chancalan | 22.0 ± 0.7 | 20.9 | 25.2 | 17.94 ± 3.76 |
| pting | input-chancalan | 22.1 ± 0.8 | 21.1 | 25.2 | 18.08 ± 3.79 |
| mattcl-py | input-mattcl | 22.2 ± 0.6 | 21.2 | 24.9 | 18.15 ± 3.80 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.3 | 25.3 | 18.28 ± 3.83 |
| mattcl-py | input-lanjian | 22.8 ± 0.7 | 21.8 | 25.7 | 18.59 ± 3.90 |
| pting | input-kcen | 22.8 ± 0.9 | 21.4 | 26.5 | 18.60 ± 3.92 |
| pting | input-lanjian | 22.9 ± 1.0 | 21.4 | 31.3 | 18.67 ± 3.95 |
| mattcl-py | input-kcen | 22.9 ± 0.9 | 21.8 | 26.8 | 18.72 ± 3.94 |
| mattcl-py | input-pting | 23.0 ± 0.8 | 21.5 | 26.5 | 18.78 ± 3.94 |
| pting | input-pting | 23.2 ± 0.8 | 21.6 | 26.7 | 18.91 ± 3.98 |
| chancalan | input-chancalan | 23.4 ± 0.7 | 22.3 | 26.8 | 19.09 ± 4.00 |
| chancalan | input-mattcl | 23.8 ± 0.8 | 22.5 | 26.7 | 19.39 ± 4.07 |
| chancalan | input-lanjian | 24.2 ± 0.8 | 22.8 | 27.0 | 19.78 ± 4.15 |
| chancalan | input-kcen | 24.4 ± 0.9 | 22.9 | 27.3 | 19.92 ± 4.19 |
| chancalan | input-pting | 24.6 ± 1.0 | 23.0 | 28.3 | 20.07 ± 4.23 |
| kcen | input-chancalan | 28.0 ± 0.8 | 27.1 | 31.0 | 22.86 ± 4.78 |
| kcen | input-mattcl | 28.2 ± 0.9 | 26.9 | 31.4 | 23.03 ± 4.83 |
| kcen | input-lanjian | 29.2 ± 0.8 | 28.0 | 32.1 | 23.83 ± 4.98 |
| kcen | input-kcen | 29.3 ± 0.8 | 27.6 | 32.7 | 23.93 ± 5.00 |
| kcen | input-pting | 29.6 ± 1.0 | 28.0 | 33.1 | 24.14 ± 5.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|