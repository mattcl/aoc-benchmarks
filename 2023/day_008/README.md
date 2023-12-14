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
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.8 | 1.8 | 1.02 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.9 | 1.03 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 2.0 | 1.03 ± 0.30 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.9 | 1.9 | 1.05 ± 0.31 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.9 | 1.8 | 1.07 ± 0.32 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.9 | 1.9 | 1.07 ± 0.31 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.11 ± 0.33 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.11 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.13 ± 0.33 |
| mattcl-ts | input-mattcl | 14.9 ± 0.3 | 13.9 | 15.6 | 12.71 ± 2.83 |
| mattcl-ts | input-chancalan | 15.0 ± 2.2 | 14.0 | 44.9 | 12.78 ± 3.40 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.2 | 16.0 | 12.79 ± 2.85 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.2 | 16.2 | 12.84 ± 2.86 |
| mattcl-ts | input-pting | 15.2 ± 0.4 | 14.4 | 17.9 | 12.90 ± 2.88 |
| mattcl-py | input-chancalan | 21.9 ± 0.7 | 21.1 | 24.7 | 18.69 ± 4.18 |
| pting | input-chancalan | 22.2 ± 0.7 | 21.1 | 24.8 | 18.88 ± 4.23 |
| pting | input-mattcl | 22.3 ± 0.6 | 21.1 | 24.6 | 18.95 ± 4.23 |
| mattcl-py | input-mattcl | 22.4 ± 0.9 | 21.5 | 25.5 | 19.08 ± 4.30 |
| pting | input-kcen | 22.6 ± 0.7 | 21.8 | 26.2 | 19.27 ± 4.31 |
| mattcl-py | input-kcen | 22.7 ± 0.9 | 21.7 | 26.0 | 19.32 ± 4.35 |
| mattcl-py | input-lanjian | 22.8 ± 2.1 | 21.5 | 44.8 | 19.39 ± 4.65 |
| pting | input-lanjian | 22.8 ± 0.8 | 21.5 | 25.9 | 19.45 ± 4.37 |
| mattcl-py | input-pting | 22.9 ± 0.8 | 21.8 | 26.9 | 19.49 ± 4.37 |
| pting | input-pting | 23.0 ± 0.8 | 22.1 | 26.4 | 19.62 ± 4.41 |
| chancalan | input-chancalan | 23.5 ± 0.9 | 22.3 | 27.6 | 20.04 ± 4.51 |
| chancalan | input-mattcl | 23.7 ± 0.9 | 22.7 | 26.8 | 20.22 ± 4.55 |
| chancalan | input-lanjian | 24.3 ± 0.9 | 23.0 | 27.1 | 20.66 ± 4.65 |
| chancalan | input-kcen | 24.3 ± 0.9 | 23.0 | 27.6 | 20.72 ± 4.65 |
| chancalan | input-pting | 24.5 ± 0.8 | 23.4 | 27.9 | 20.85 ± 4.67 |
| kcen | input-chancalan | 27.9 ± 0.9 | 26.7 | 30.9 | 23.77 ± 5.33 |
| kcen | input-mattcl | 28.1 ± 0.7 | 27.1 | 30.6 | 23.95 ± 5.34 |
| kcen | input-lanjian | 28.9 ± 0.7 | 27.8 | 32.0 | 24.59 ± 5.49 |
| kcen | input-kcen | 29.2 ± 0.8 | 28.0 | 31.8 | 24.91 ± 5.56 |
| kcen | input-pting | 29.6 ± 0.8 | 28.5 | 33.3 | 25.23 ± 5.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|