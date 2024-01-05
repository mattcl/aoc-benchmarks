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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.8 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.31 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.9 | 1.9 | 1.06 ± 0.32 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 2.0 | 1.06 ± 0.33 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.9 | 1.06 ± 0.34 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.9 | 1.07 ± 0.33 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.9 | 1.07 ± 0.33 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.8 | 1.9 | 1.08 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.13 ± 0.34 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.3 | 1.13 ± 0.34 |
| mattcl-ts | input-chancalan | 14.8 ± 0.4 | 13.8 | 15.8 | 12.73 ± 2.91 |
| mattcl-ts | input-mattcl | 14.9 ± 0.3 | 14.0 | 15.7 | 12.84 ± 2.93 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.0 | 16.4 | 12.94 ± 2.95 |
| mattcl-ts | input-pting | 15.0 ± 0.3 | 14.3 | 16.2 | 12.96 ± 2.95 |
| mattcl-ts | input-kcen | 15.5 ± 4.7 | 14.1 | 68.3 | 13.37 ± 5.09 |
| pting | input-chancalan | 21.9 ± 0.7 | 21.1 | 24.6 | 18.87 ± 4.33 |
| mattcl-py | input-chancalan | 21.9 ± 0.8 | 21.1 | 25.3 | 18.91 ± 4.34 |
| mattcl-py | input-mattcl | 22.1 ± 0.6 | 21.2 | 24.8 | 19.07 ± 4.36 |
| pting | input-mattcl | 22.3 ± 0.9 | 21.2 | 25.6 | 19.24 ± 4.44 |
| pting | input-kcen | 22.4 ± 0.7 | 21.5 | 25.7 | 19.33 ± 4.43 |
| mattcl-py | input-lanjian | 22.6 ± 0.8 | 21.6 | 25.5 | 19.43 ± 4.46 |
| pting | input-lanjian | 22.6 ± 0.8 | 21.5 | 25.6 | 19.48 ± 4.48 |
| mattcl-py | input-pting | 22.9 ± 0.8 | 21.9 | 25.5 | 19.69 ± 4.52 |
| pting | input-pting | 22.9 ± 0.7 | 21.9 | 27.5 | 19.71 ± 4.52 |
| mattcl-py | input-kcen | 23.0 ± 3.3 | 21.4 | 59.5 | 19.82 ± 5.34 |
| chancalan | input-chancalan | 23.4 ± 0.9 | 22.4 | 26.5 | 20.14 ± 4.64 |
| chancalan | input-mattcl | 23.6 ± 0.8 | 22.4 | 26.5 | 20.36 ± 4.68 |
| chancalan | input-lanjian | 23.9 ± 0.7 | 22.7 | 26.9 | 20.63 ± 4.72 |
| chancalan | input-kcen | 24.1 ± 0.9 | 22.9 | 27.3 | 20.76 ± 4.78 |
| chancalan | input-pting | 24.5 ± 0.9 | 23.5 | 27.4 | 21.08 ± 4.85 |
| kcen | input-chancalan | 27.6 ± 0.7 | 26.5 | 30.4 | 23.76 ± 5.43 |
| kcen | input-mattcl | 28.1 ± 1.0 | 26.9 | 31.4 | 24.18 ± 5.56 |
| kcen | input-kcen | 28.9 ± 0.7 | 27.8 | 31.7 | 24.91 ± 5.69 |
| kcen | input-lanjian | 29.0 ± 0.9 | 27.5 | 31.3 | 25.02 ± 5.73 |
| kcen | input-pting | 29.4 ± 1.2 | 28.4 | 36.9 | 25.34 ± 5.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|