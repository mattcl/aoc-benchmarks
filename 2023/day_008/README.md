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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.9 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.02 ± 0.31 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.9 | 2.0 | 1.03 ± 0.29 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.9 | 2.1 | 1.04 ± 0.29 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 1.9 | 1.05 ± 0.30 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.06 ± 0.30 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.07 ± 0.31 |
| lanjian | input-pting | 1.4 ± 0.3 | 0.9 | 2.3 | 1.09 ± 0.30 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.3 | 1.11 ± 0.31 |
| mattcl | input-chancalan | 1.6 ± 5.8 | 0.9 | 83.5 | 1.32 ± 4.70 |
| mattcl-ts | input-chancalan | 14.8 ± 0.4 | 13.9 | 16.3 | 11.96 ± 2.49 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 13.9 | 16.3 | 12.07 ± 2.50 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.2 | 15.9 | 12.16 ± 2.52 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.3 | 16.0 | 12.17 ± 2.52 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.2 | 16.4 | 12.17 ± 2.53 |
| pting | input-chancalan | 22.0 ± 0.7 | 21.0 | 24.8 | 17.72 ± 3.70 |
| pting | input-mattcl | 22.2 ± 0.7 | 21.1 | 24.8 | 17.85 ± 3.72 |
| mattcl-py | input-chancalan | 22.2 ± 3.2 | 20.8 | 58.0 | 17.91 ± 4.51 |
| mattcl-py | input-mattcl | 22.2 ± 0.8 | 21.0 | 25.4 | 17.93 ± 3.75 |
| mattcl-py | input-lanjian | 22.5 ± 0.7 | 21.7 | 25.6 | 18.13 ± 3.79 |
| mattcl-py | input-kcen | 22.5 ± 0.6 | 21.7 | 26.0 | 18.15 ± 3.78 |
| pting | input-kcen | 22.6 ± 0.8 | 21.7 | 25.7 | 18.25 ± 3.82 |
| pting | input-lanjian | 22.7 ± 0.8 | 21.8 | 25.8 | 18.31 ± 3.83 |
| mattcl-py | input-pting | 22.9 ± 0.8 | 21.7 | 26.0 | 18.48 ± 3.87 |
| chancalan | input-chancalan | 23.3 ± 0.7 | 22.3 | 26.2 | 18.77 ± 3.91 |
| pting | input-pting | 23.4 ± 4.0 | 21.8 | 57.0 | 18.86 ± 5.05 |
| chancalan | input-mattcl | 23.5 ± 0.7 | 22.3 | 26.8 | 18.96 ± 3.96 |
| chancalan | input-kcen | 24.0 ± 0.8 | 22.9 | 27.0 | 19.36 ± 4.04 |
| chancalan | input-lanjian | 24.0 ± 0.8 | 23.1 | 27.5 | 19.38 ± 4.05 |
| chancalan | input-pting | 24.4 ± 0.9 | 23.3 | 30.1 | 19.69 ± 4.13 |
| kcen | input-chancalan | 27.7 ± 0.9 | 26.6 | 30.7 | 22.31 ± 4.65 |
| kcen | input-mattcl | 27.9 ± 0.9 | 26.9 | 30.6 | 22.49 ± 4.69 |
| kcen | input-lanjian | 28.9 ± 0.9 | 27.6 | 32.8 | 23.33 ± 4.86 |
| kcen | input-kcen | 29.1 ± 0.9 | 28.1 | 31.6 | 23.42 ± 4.88 |
| kcen | input-pting | 29.4 ± 0.9 | 28.2 | 32.1 | 23.73 ± 4.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|