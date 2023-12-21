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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.7 | 1.00 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.8 | 1.01 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.9 | 1.03 ± 0.32 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.9 | 1.05 ± 0.33 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.8 | 2.0 | 1.05 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 1.9 | 1.05 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.9 | 1.8 | 1.07 ± 0.32 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.9 | 1.07 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.14 ± 0.34 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.15 ± 0.34 |
| mattcl-ts | input-chancalan | 15.0 ± 0.4 | 14.3 | 16.5 | 13.10 ± 2.82 |
| mattcl-ts | input-lanjian | 15.2 ± 0.4 | 14.1 | 16.7 | 13.28 ± 2.86 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 14.5 | 16.6 | 13.30 ± 2.87 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.3 | 16.9 | 13.33 ± 2.88 |
| mattcl-ts | input-mattcl | 15.4 ± 3.9 | 14.0 | 69.4 | 13.44 ± 4.44 |
| pting | input-chancalan | 22.2 ± 0.7 | 20.9 | 26.1 | 19.34 ± 4.19 |
| mattcl-py | input-mattcl | 22.4 ± 0.9 | 21.3 | 29.6 | 19.54 ± 4.26 |
| pting | input-mattcl | 22.6 ± 1.1 | 21.0 | 30.3 | 19.67 ± 4.31 |
| mattcl-py | input-chancalan | 22.6 ± 2.4 | 21.1 | 42.4 | 19.67 ± 4.70 |
| mattcl-py | input-lanjian | 22.7 ± 0.8 | 21.5 | 25.7 | 19.77 ± 4.29 |
| pting | input-kcen | 22.9 ± 0.8 | 21.8 | 26.6 | 20.01 ± 4.35 |
| pting | input-lanjian | 23.0 ± 0.9 | 21.8 | 25.8 | 20.02 ± 4.35 |
| mattcl-py | input-kcen | 23.0 ± 0.8 | 21.9 | 25.8 | 20.09 ± 4.36 |
| mattcl-py | input-pting | 23.1 ± 0.8 | 21.9 | 26.4 | 20.17 ± 4.37 |
| chancalan | input-chancalan | 23.6 ± 0.7 | 22.7 | 26.0 | 20.57 ± 4.45 |
| pting | input-pting | 23.8 ± 4.4 | 21.9 | 65.7 | 20.74 ± 5.89 |
| chancalan | input-mattcl | 23.9 ± 0.9 | 22.7 | 26.9 | 20.81 ± 4.53 |
| chancalan | input-lanjian | 24.4 ± 0.9 | 23.2 | 29.3 | 21.25 ± 4.61 |
| chancalan | input-kcen | 24.5 ± 0.9 | 23.0 | 28.8 | 21.34 ± 4.64 |
| chancalan | input-pting | 24.5 ± 0.6 | 23.4 | 26.9 | 21.37 ± 4.61 |
| kcen | input-chancalan | 28.2 ± 1.0 | 26.6 | 31.0 | 24.56 ± 5.33 |
| kcen | input-mattcl | 28.5 ± 0.9 | 27.1 | 31.2 | 24.81 ± 5.37 |
| kcen | input-lanjian | 29.3 ± 0.8 | 28.1 | 31.8 | 25.56 ± 5.52 |
| kcen | input-kcen | 29.6 ± 1.0 | 28.1 | 33.0 | 25.84 ± 5.60 |
| kcen | input-pting | 29.8 ± 0.8 | 28.6 | 32.7 | 25.97 ± 5.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|