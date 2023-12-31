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
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.30 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.30 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.0 | 1.02 ± 0.32 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.9 | 1.8 | 1.03 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.06 ± 0.32 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 1.9 | 1.07 ± 0.32 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 1.9 | 1.09 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.10 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.3 | 1.12 ± 0.34 |
| mattcl-ts | input-chancalan | 15.1 ± 0.4 | 14.1 | 16.4 | 12.71 ± 2.85 |
| mattcl-ts | input-kcen | 15.2 ± 0.4 | 14.3 | 16.4 | 12.83 ± 2.87 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.6 | 17.3 | 12.92 ± 2.90 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.4 | 16.9 | 12.94 ± 2.90 |
| mattcl-ts | input-mattcl | 15.7 ± 5.3 | 14.1 | 67.1 | 13.26 ± 5.33 |
| mattcl-py | input-chancalan | 22.2 ± 0.8 | 21.0 | 25.1 | 18.72 ± 4.22 |
| pting | input-chancalan | 22.2 ± 1.0 | 20.7 | 26.3 | 18.74 ± 4.25 |
| mattcl-py | input-mattcl | 22.4 ± 0.7 | 21.3 | 25.3 | 18.86 ± 4.24 |
| pting | input-mattcl | 22.5 ± 2.3 | 21.4 | 48.0 | 19.00 ± 4.65 |
| mattcl-py | input-lanjian | 22.7 ± 0.7 | 21.6 | 25.8 | 19.10 ± 4.30 |
| mattcl-py | input-kcen | 22.9 ± 0.7 | 21.8 | 25.4 | 19.29 ± 4.33 |
| pting | input-kcen | 22.9 ± 0.8 | 21.6 | 26.5 | 19.30 ± 4.34 |
| mattcl-py | input-pting | 22.9 ± 0.7 | 21.8 | 26.1 | 19.30 ± 4.34 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.7 | 26.1 | 19.34 ± 4.36 |
| pting | input-pting | 23.0 ± 0.7 | 22.1 | 25.7 | 19.37 ± 4.35 |
| chancalan | input-chancalan | 23.5 ± 0.7 | 22.5 | 26.7 | 19.83 ± 4.45 |
| chancalan | input-mattcl | 23.9 ± 0.9 | 22.1 | 26.8 | 20.11 ± 4.55 |
| chancalan | input-lanjian | 24.2 ± 0.7 | 22.9 | 27.5 | 20.43 ± 4.59 |
| chancalan | input-kcen | 24.3 ± 0.8 | 22.8 | 27.7 | 20.48 ± 4.61 |
| chancalan | input-pting | 24.6 ± 0.7 | 23.5 | 27.1 | 20.75 ± 4.66 |
| kcen | input-mattcl | 28.2 ± 0.8 | 27.0 | 31.5 | 23.74 ± 5.33 |
| kcen | input-chancalan | 28.5 ± 4.3 | 26.6 | 69.8 | 24.04 ± 6.48 |
| kcen | input-kcen | 29.4 ± 0.8 | 27.9 | 32.5 | 24.75 ± 5.55 |
| kcen | input-lanjian | 29.5 ± 1.0 | 28.2 | 32.8 | 24.86 ± 5.60 |
| kcen | input-pting | 29.7 ± 1.1 | 28.4 | 36.4 | 25.01 ± 5.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|