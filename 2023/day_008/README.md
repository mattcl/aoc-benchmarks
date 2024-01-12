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
| mattcl | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.6 | 1.00 |
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.02 ± 0.30 |
| mattcl | input-kcen | 1.3 ± 0.2 | 1.0 | 2.0 | 1.05 ± 0.30 |
| lanjian | input-chancalan | 1.4 ± 0.3 | 1.0 | 2.2 | 1.06 ± 0.31 |
| lanjian | input-mattcl | 1.4 ± 0.3 | 1.0 | 2.2 | 1.06 ± 0.31 |
| mattcl | input-lanjian | 1.4 ± 0.3 | 1.0 | 2.1 | 1.06 ± 0.31 |
| mattcl | input-pting | 1.4 ± 0.2 | 1.0 | 2.0 | 1.06 ± 0.30 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 1.0 | 1.9 | 1.08 ± 0.30 |
| lanjian | input-kcen | 1.4 ± 0.2 | 1.0 | 2.1 | 1.10 ± 0.30 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.1 | 2.2 | 1.12 ± 0.32 |
| mattcl-ts | input-chancalan | 14.4 ± 0.4 | 13.6 | 15.4 | 11.24 ± 2.49 |
| mattcl-ts | input-mattcl | 14.6 ± 0.4 | 13.6 | 15.5 | 11.40 ± 2.53 |
| mattcl-ts | input-lanjian | 14.8 ± 0.4 | 13.9 | 15.6 | 11.54 ± 2.56 |
| mattcl-ts | input-kcen | 14.8 ± 0.4 | 13.8 | 15.5 | 11.56 ± 2.56 |
| mattcl-ts | input-pting | 14.9 ± 0.4 | 13.9 | 15.8 | 11.62 ± 2.57 |
| mattcl-py | input-chancalan | 22.1 ± 0.8 | 21.1 | 25.6 | 17.26 ± 3.85 |
| mattcl-py | input-mattcl | 22.3 ± 0.7 | 21.2 | 25.5 | 17.40 ± 3.88 |
| pting | input-chancalan | 22.3 ± 1.5 | 20.9 | 34.0 | 17.40 ± 4.00 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.5 | 25.3 | 17.47 ± 3.89 |
| pting | input-lanjian | 22.6 ± 0.7 | 21.5 | 25.6 | 17.68 ± 3.93 |
| mattcl-py | input-lanjian | 22.6 ± 0.7 | 21.7 | 25.5 | 17.69 ± 3.93 |
| pting | input-kcen | 22.7 ± 0.7 | 21.8 | 25.1 | 17.73 ± 3.95 |
| mattcl-py | input-kcen | 22.8 ± 0.8 | 21.8 | 25.6 | 17.84 ± 3.98 |
| mattcl-py | input-pting | 22.9 ± 0.7 | 22.1 | 25.7 | 17.88 ± 3.97 |
| pting | input-pting | 23.4 ± 3.8 | 21.8 | 65.7 | 18.28 ± 5.02 |
| chancalan | input-chancalan | 23.4 ± 0.9 | 22.0 | 26.4 | 18.31 ± 4.09 |
| chancalan | input-mattcl | 23.5 ± 0.6 | 22.7 | 26.2 | 18.40 ± 4.08 |
| chancalan | input-kcen | 24.1 ± 0.7 | 23.3 | 27.5 | 18.81 ± 4.18 |
| chancalan | input-lanjian | 24.1 ± 0.9 | 23.0 | 27.3 | 18.85 ± 4.21 |
| chancalan | input-pting | 24.5 ± 0.8 | 23.4 | 27.1 | 19.12 ± 4.26 |
| kcen | input-chancalan | 27.8 ± 1.0 | 26.8 | 31.4 | 21.70 ± 4.84 |
| kcen | input-mattcl | 28.1 ± 0.8 | 26.8 | 31.8 | 21.93 ± 4.87 |
| kcen | input-kcen | 29.1 ± 0.7 | 28.0 | 31.5 | 22.73 ± 5.03 |
| kcen | input-lanjian | 29.2 ± 1.0 | 28.0 | 31.9 | 22.80 ± 5.08 |
| kcen | input-pting | 29.9 ± 4.8 | 28.4 | 76.8 | 23.36 ± 6.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|