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
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.8 | 1.8 | 1.00 ± 0.31 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.0 | 1.02 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 2.0 | 1.03 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.9 | 2.0 | 1.06 ± 0.33 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.34 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.09 ± 0.34 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.13 ± 0.34 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.2 | 1.15 ± 0.36 |
| mattcl | input-lanjian | 1.4 ± 3.8 | 0.8 | 55.3 | 1.20 ± 3.27 |
| mattcl-ts | input-chancalan | 15.0 ± 0.3 | 14.3 | 16.4 | 12.77 ± 2.96 |
| mattcl-ts | input-mattcl | 15.2 ± 0.4 | 14.1 | 17.3 | 12.87 ± 2.99 |
| mattcl-ts | input-lanjian | 15.2 ± 0.4 | 14.4 | 16.6 | 12.92 ± 3.00 |
| mattcl-ts | input-kcen | 15.2 ± 0.4 | 14.4 | 16.3 | 12.92 ± 3.00 |
| mattcl-ts | input-pting | 15.5 ± 3.1 | 14.5 | 57.0 | 13.15 ± 4.00 |
| mattcl-py | input-chancalan | 22.3 ± 0.7 | 21.1 | 25.2 | 18.89 ± 4.40 |
| mattcl-py | input-mattcl | 22.3 ± 0.7 | 21.3 | 25.4 | 18.91 ± 4.40 |
| pting | input-chancalan | 22.4 ± 0.9 | 21.2 | 26.0 | 18.98 ± 4.45 |
| mattcl-py | input-lanjian | 22.8 ± 0.6 | 21.8 | 25.3 | 19.34 ± 4.49 |
| pting | input-kcen | 22.9 ± 0.8 | 21.5 | 26.2 | 19.40 ± 4.53 |
| pting | input-mattcl | 23.0 ± 3.3 | 21.3 | 57.9 | 19.50 ± 5.29 |
| mattcl-py | input-kcen | 23.0 ± 1.1 | 21.6 | 28.8 | 19.53 ± 4.60 |
| pting | input-lanjian | 23.0 ± 0.9 | 21.8 | 26.6 | 19.54 ± 4.57 |
| pting | input-pting | 23.2 ± 0.7 | 22.0 | 26.5 | 19.67 ± 4.58 |
| chancalan | input-chancalan | 23.5 ± 0.7 | 22.6 | 26.4 | 19.98 ± 4.65 |
| mattcl-py | input-pting | 23.8 ± 4.5 | 22.0 | 65.6 | 20.16 ± 6.03 |
| chancalan | input-mattcl | 23.8 ± 0.8 | 22.6 | 26.5 | 20.20 ± 4.71 |
| chancalan | input-kcen | 24.4 ± 0.8 | 23.3 | 27.5 | 20.74 ± 4.83 |
| chancalan | input-lanjian | 24.5 ± 0.9 | 23.1 | 27.6 | 20.80 ± 4.86 |
| chancalan | input-pting | 24.5 ± 0.7 | 23.1 | 27.4 | 20.82 ± 4.84 |
| kcen | input-chancalan | 28.1 ± 0.7 | 26.9 | 30.9 | 23.82 ± 5.52 |
| kcen | input-mattcl | 28.4 ± 0.9 | 27.0 | 31.2 | 24.14 ± 5.62 |
| kcen | input-lanjian | 29.4 ± 0.8 | 28.0 | 32.0 | 24.94 ± 5.80 |
| kcen | input-kcen | 29.4 ± 0.9 | 28.0 | 32.7 | 24.97 ± 5.81 |
| kcen | input-pting | 29.8 ± 0.9 | 28.2 | 32.7 | 25.30 ± 5.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|