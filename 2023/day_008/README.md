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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.00 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.9 | 1.9 | 1.05 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 1.9 | 1.05 ± 0.29 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.9 | 1.05 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.06 ± 0.32 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.9 | 1.8 | 1.08 ± 0.31 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 1.9 | 1.08 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 2.0 | 1.09 ± 0.30 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.10 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.1 | 1.17 ± 0.33 |
| mattcl-ts | input-chancalan | 14.5 ± 0.3 | 13.7 | 15.5 | 12.56 ± 2.66 |
| mattcl-ts | input-mattcl | 14.7 ± 0.4 | 13.8 | 15.6 | 12.75 ± 2.70 |
| mattcl-ts | input-kcen | 14.9 ± 0.4 | 14.0 | 15.8 | 12.86 ± 2.72 |
| mattcl-ts | input-pting | 14.9 ± 0.3 | 13.8 | 16.2 | 12.90 ± 2.72 |
| mattcl-ts | input-lanjian | 15.0 ± 2.1 | 13.8 | 43.5 | 12.97 ± 3.27 |
| pting | input-chancalan | 22.0 ± 1.2 | 21.1 | 33.3 | 19.00 ± 4.12 |
| mattcl-py | input-chancalan | 22.0 ± 1.0 | 20.9 | 29.6 | 19.05 ± 4.10 |
| mattcl-py | input-mattcl | 22.2 ± 0.8 | 21.1 | 25.4 | 19.19 ± 4.09 |
| pting | input-mattcl | 22.4 ± 1.0 | 21.1 | 25.5 | 19.35 ± 4.16 |
| pting | input-lanjian | 22.5 ± 0.6 | 21.4 | 25.8 | 19.45 ± 4.12 |
| pting | input-kcen | 22.6 ± 0.8 | 21.6 | 25.8 | 19.53 ± 4.16 |
| pting | input-pting | 22.6 ± 0.6 | 21.8 | 25.5 | 19.56 ± 4.15 |
| mattcl-py | input-kcen | 22.7 ± 0.8 | 21.8 | 26.4 | 19.62 ± 4.18 |
| mattcl-py | input-pting | 22.8 ± 0.7 | 21.9 | 25.6 | 19.70 ± 4.19 |
| mattcl-py | input-lanjian | 22.9 ± 3.9 | 21.6 | 65.5 | 19.80 ± 5.37 |
| chancalan | input-chancalan | 23.2 ± 0.7 | 22.1 | 25.9 | 20.02 ± 4.25 |
| chancalan | input-mattcl | 23.5 ± 0.8 | 22.6 | 27.0 | 20.29 ± 4.31 |
| chancalan | input-kcen | 23.9 ± 0.8 | 23.1 | 27.6 | 20.68 ± 4.40 |
| chancalan | input-lanjian | 24.0 ± 0.8 | 22.8 | 26.5 | 20.71 ± 4.40 |
| chancalan | input-pting | 24.4 ± 0.9 | 23.2 | 27.4 | 21.07 ± 4.49 |
| kcen | input-chancalan | 27.5 ± 0.7 | 26.5 | 30.4 | 23.77 ± 5.03 |
| kcen | input-mattcl | 27.8 ± 0.7 | 26.6 | 30.4 | 24.04 ± 5.08 |
| kcen | input-kcen | 28.8 ± 0.8 | 27.8 | 32.4 | 24.91 ± 5.28 |
| kcen | input-lanjian | 28.9 ± 0.9 | 27.8 | 31.8 | 24.97 ± 5.30 |
| kcen | input-pting | 29.5 ± 1.0 | 28.3 | 32.1 | 25.49 ± 5.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|