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
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.30 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.0 | 1.02 ± 0.32 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.8 | 1.03 ± 0.33 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.03 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 1.9 | 1.05 ± 0.32 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.9 | 2.1 | 1.05 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.06 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.08 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.9 | 2.1 | 1.11 ± 0.32 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.0 | 16.2 | 12.81 ± 2.87 |
| mattcl-ts | input-chancalan | 15.1 ± 0.4 | 14.2 | 16.5 | 12.82 ± 2.88 |
| mattcl-ts | input-lanjian | 15.2 ± 0.4 | 14.3 | 16.6 | 12.91 ± 2.89 |
| mattcl-ts | input-kcen | 15.2 ± 0.4 | 14.4 | 16.5 | 12.94 ± 2.90 |
| mattcl-ts | input-pting | 15.2 ± 0.4 | 14.4 | 16.5 | 12.95 ± 2.90 |
| pting | input-chancalan | 22.2 ± 0.7 | 21.2 | 25.1 | 18.88 ± 4.25 |
| mattcl-py | input-chancalan | 22.2 ± 1.1 | 21.2 | 32.3 | 18.92 ± 4.32 |
| mattcl-py | input-mattcl | 22.3 ± 0.6 | 20.9 | 25.4 | 18.93 ± 4.25 |
| pting | input-mattcl | 22.5 ± 0.8 | 21.1 | 25.2 | 19.09 ± 4.31 |
| pting | input-kcen | 22.9 ± 0.7 | 21.7 | 25.8 | 19.43 ± 4.37 |
| mattcl-py | input-kcen | 22.9 ± 0.7 | 21.8 | 26.1 | 19.45 ± 4.38 |
| pting | input-lanjian | 23.0 ± 1.3 | 21.4 | 34.2 | 19.53 ± 4.49 |
| mattcl-py | input-pting | 23.1 ± 0.6 | 22.0 | 26.2 | 19.66 ± 4.41 |
| pting | input-pting | 23.3 ± 0.7 | 22.2 | 25.7 | 19.82 ± 4.46 |
| mattcl-py | input-lanjian | 23.5 ± 4.9 | 21.6 | 71.5 | 19.95 ± 6.11 |
| chancalan | input-chancalan | 23.5 ± 0.7 | 22.5 | 26.6 | 20.00 ± 4.49 |
| chancalan | input-mattcl | 23.9 ± 1.0 | 22.8 | 28.3 | 20.34 ± 4.62 |
| chancalan | input-lanjian | 24.3 ± 1.3 | 22.8 | 34.8 | 20.69 ± 4.73 |
| chancalan | input-kcen | 24.6 ± 1.1 | 23.3 | 30.6 | 20.90 ± 4.75 |
| chancalan | input-pting | 24.8 ± 1.0 | 23.6 | 28.8 | 21.08 ± 4.77 |
| kcen | input-chancalan | 27.9 ± 0.7 | 26.8 | 31.0 | 23.75 ± 5.32 |
| kcen | input-mattcl | 28.2 ± 0.9 | 27.0 | 31.2 | 24.01 ± 5.40 |
| kcen | input-lanjian | 29.3 ± 0.8 | 27.7 | 32.0 | 24.93 ± 5.60 |
| kcen | input-kcen | 29.5 ± 1.0 | 28.2 | 33.0 | 25.06 ± 5.64 |
| kcen | input-pting | 29.8 ± 1.0 | 28.6 | 33.4 | 25.37 ± 5.71 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|