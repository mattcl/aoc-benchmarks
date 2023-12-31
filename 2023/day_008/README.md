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
| mattcl | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.0 | 1.00 |
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.02 ± 0.29 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.1 | 1.03 ± 0.29 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.1 | 1.04 ± 0.29 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 1.0 | 2.1 | 1.04 ± 0.29 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.05 ± 0.30 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.29 |
| lanjian | input-lanjian | 1.4 ± 0.3 | 1.0 | 2.1 | 1.07 ± 0.31 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.0 | 2.3 | 1.08 ± 0.30 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.2 | 1.12 ± 0.31 |
| mattcl-ts | input-chancalan | 15.1 ± 0.4 | 14.0 | 16.3 | 11.84 ± 2.38 |
| mattcl-ts | input-mattcl | 15.2 ± 0.4 | 14.3 | 16.4 | 11.95 ± 2.40 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.4 | 17.0 | 12.00 ± 2.41 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 14.4 | 16.6 | 12.04 ± 2.42 |
| mattcl-ts | input-pting | 15.4 ± 0.3 | 14.5 | 16.2 | 12.09 ± 2.42 |
| pting | input-chancalan | 22.3 ± 0.8 | 21.4 | 25.6 | 17.51 ± 3.54 |
| mattcl-py | input-mattcl | 22.5 ± 0.7 | 21.4 | 25.3 | 17.68 ± 3.57 |
| pting | input-mattcl | 22.6 ± 0.8 | 21.3 | 26.1 | 17.75 ± 3.59 |
| mattcl-py | input-chancalan | 22.6 ± 3.2 | 20.7 | 49.5 | 17.77 ± 4.33 |
| mattcl-py | input-lanjian | 22.8 ± 0.6 | 21.6 | 25.4 | 17.88 ± 3.59 |
| pting | input-kcen | 23.0 ± 0.7 | 21.9 | 25.4 | 18.04 ± 3.64 |
| pting | input-lanjian | 23.0 ± 0.9 | 21.9 | 26.8 | 18.05 ± 3.67 |
| mattcl-py | input-kcen | 23.0 ± 0.7 | 22.1 | 26.0 | 18.07 ± 3.64 |
| mattcl-py | input-pting | 23.3 ± 0.8 | 21.8 | 26.5 | 18.26 ± 3.69 |
| chancalan | input-chancalan | 23.7 ± 0.9 | 22.7 | 27.9 | 18.63 ± 3.77 |
| pting | input-pting | 23.7 ± 4.2 | 22.0 | 66.4 | 18.64 ± 4.95 |
| chancalan | input-mattcl | 23.9 ± 0.8 | 22.7 | 26.9 | 18.78 ± 3.80 |
| chancalan | input-lanjian | 24.3 ± 0.6 | 23.3 | 26.8 | 19.08 ± 3.83 |
| chancalan | input-kcen | 24.5 ± 0.7 | 23.4 | 27.1 | 19.23 ± 3.87 |
| chancalan | input-pting | 24.8 ± 0.7 | 23.7 | 27.7 | 19.48 ± 3.92 |
| kcen | input-chancalan | 28.2 ± 0.8 | 27.0 | 30.9 | 22.13 ± 4.45 |
| kcen | input-mattcl | 28.5 ± 0.8 | 27.0 | 31.3 | 22.37 ± 4.50 |
| kcen | input-kcen | 29.6 ± 0.9 | 28.3 | 32.9 | 23.20 ± 4.67 |
| kcen | input-lanjian | 29.6 ± 1.0 | 27.8 | 32.6 | 23.20 ± 4.69 |
| kcen | input-pting | 29.8 ± 1.0 | 28.6 | 32.9 | 23.39 ± 4.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|