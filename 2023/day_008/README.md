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
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.0 | 1.02 ± 0.32 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.0 | 1.04 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.05 ± 0.33 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.9 | 1.8 | 1.05 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.9 | 1.06 ± 0.33 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.8 | 1.07 ± 0.32 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 1.9 | 1.08 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.11 ± 0.34 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.2 | 1.16 ± 0.35 |
| mattcl-ts | input-chancalan | 15.0 ± 0.4 | 14.1 | 16.1 | 12.84 ± 2.92 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.1 | 16.5 | 12.95 ± 2.94 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.5 | 16.5 | 13.09 ± 2.98 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 14.4 | 16.6 | 13.10 ± 2.98 |
| mattcl-ts | input-lanjian | 16.1 ± 5.8 | 13.9 | 59.4 | 13.82 ± 5.85 |
| pting | input-chancalan | 22.0 ± 0.7 | 21.0 | 24.5 | 18.92 ± 4.31 |
| mattcl-py | input-chancalan | 22.2 ± 0.8 | 21.0 | 25.6 | 19.03 ± 4.36 |
| pting | input-mattcl | 22.2 ± 0.7 | 20.8 | 25.5 | 19.06 ± 4.35 |
| pting | input-kcen | 22.6 ± 0.7 | 21.5 | 25.4 | 19.40 ± 4.42 |
| mattcl-py | input-lanjian | 22.8 ± 0.7 | 21.6 | 25.7 | 19.56 ± 4.46 |
| mattcl-py | input-kcen | 22.8 ± 0.8 | 21.8 | 25.9 | 19.59 ± 4.48 |
| pting | input-lanjian | 22.8 ± 0.8 | 21.8 | 25.9 | 19.61 ± 4.48 |
| pting | input-pting | 23.0 ± 0.6 | 21.9 | 26.9 | 19.74 ± 4.49 |
| mattcl-py | input-pting | 23.0 ± 0.7 | 22.0 | 26.3 | 19.76 ± 4.50 |
| mattcl-py | input-mattcl | 23.0 ± 4.6 | 21.0 | 60.4 | 19.76 ± 5.97 |
| chancalan | input-chancalan | 23.4 ± 0.8 | 22.3 | 26.7 | 20.10 ± 4.60 |
| chancalan | input-mattcl | 23.8 ± 0.9 | 22.3 | 27.3 | 20.46 ± 4.68 |
| chancalan | input-kcen | 24.3 ± 0.8 | 23.1 | 27.0 | 20.82 ± 4.75 |
| chancalan | input-lanjian | 24.3 ± 0.7 | 23.3 | 27.9 | 20.86 ± 4.75 |
| chancalan | input-pting | 24.6 ± 0.9 | 23.5 | 30.5 | 21.14 ± 4.84 |
| kcen | input-mattcl | 28.2 ± 0.7 | 27.1 | 30.4 | 24.22 ± 5.51 |
| kcen | input-chancalan | 28.4 ± 2.1 | 26.8 | 47.1 | 24.35 ± 5.78 |
| kcen | input-lanjian | 29.0 ± 0.8 | 27.3 | 32.3 | 24.89 ± 5.66 |
| kcen | input-kcen | 29.4 ± 1.0 | 27.9 | 33.5 | 25.27 ± 5.77 |
| kcen | input-pting | 29.6 ± 0.8 | 28.4 | 32.0 | 25.39 ± 5.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|