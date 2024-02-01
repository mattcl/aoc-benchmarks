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
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.0 | 1.05 ± 0.32 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.9 | 2.3 | 1.06 ± 0.31 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.8 | 2.1 | 1.07 ± 0.33 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.8 | 1.9 | 1.07 ± 0.32 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 1.9 | 1.07 ± 0.33 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.10 ± 0.32 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 1.9 | 1.12 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 2.1 | 1.13 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.3 | 1.17 ± 0.35 |
| mattcl-ts | input-chancalan | 14.8 ± 0.4 | 13.9 | 16.4 | 12.65 ± 2.76 |
| mattcl-ts | input-mattcl | 14.8 ± 0.3 | 13.8 | 15.6 | 12.67 ± 2.76 |
| mattcl-ts | input-lanjian | 14.9 ± 0.3 | 14.0 | 16.1 | 12.75 ± 2.78 |
| mattcl-ts | input-pting | 15.0 ± 0.3 | 14.1 | 16.0 | 12.78 ± 2.78 |
| mattcl-ts | input-kcen | 15.0 ± 0.3 | 14.0 | 16.6 | 12.80 ± 2.79 |
| pting | input-chancalan | 22.2 ± 0.9 | 21.1 | 25.1 | 18.97 ± 4.20 |
| mattcl-py | input-chancalan | 22.2 ± 0.9 | 21.1 | 25.3 | 18.99 ± 4.19 |
| pting | input-mattcl | 22.4 ± 0.8 | 21.5 | 25.7 | 19.08 ± 4.19 |
| mattcl-py | input-mattcl | 22.4 ± 0.8 | 21.2 | 26.0 | 19.15 ± 4.22 |
| mattcl-py | input-lanjian | 22.5 ± 0.6 | 21.7 | 24.9 | 19.21 ± 4.20 |
| pting | input-kcen | 22.8 ± 0.9 | 21.7 | 30.2 | 19.45 ± 4.29 |
| mattcl-py | input-kcen | 22.9 ± 0.7 | 22.0 | 25.9 | 19.51 ± 4.27 |
| pting | input-lanjian | 22.9 ± 0.7 | 21.8 | 25.7 | 19.56 ± 4.29 |
| pting | input-pting | 23.1 ± 0.9 | 22.0 | 29.2 | 19.73 ± 4.35 |
| mattcl-py | input-pting | 23.2 ± 0.8 | 22.1 | 26.5 | 19.80 ± 4.35 |
| chancalan | input-chancalan | 23.3 ± 0.7 | 22.1 | 26.0 | 19.92 ± 4.36 |
| chancalan | input-mattcl | 23.7 ± 0.9 | 22.7 | 26.9 | 20.26 ± 4.47 |
| chancalan | input-lanjian | 24.4 ± 1.3 | 22.9 | 35.7 | 20.79 ± 4.65 |
| chancalan | input-kcen | 24.5 ± 1.0 | 23.3 | 27.7 | 20.88 ± 4.61 |
| chancalan | input-pting | 24.5 ± 0.9 | 23.2 | 27.9 | 20.93 ± 4.61 |
| kcen | input-chancalan | 27.8 ± 0.9 | 26.5 | 31.3 | 23.72 ± 5.21 |
| kcen | input-mattcl | 28.1 ± 0.7 | 27.1 | 30.7 | 24.00 ± 5.24 |
| kcen | input-lanjian | 29.4 ± 1.2 | 28.1 | 38.7 | 25.05 ± 5.53 |
| kcen | input-kcen | 29.4 ± 0.8 | 27.6 | 32.1 | 25.05 ± 5.48 |
| kcen | input-pting | 29.6 ± 1.0 | 28.4 | 33.9 | 25.30 ± 5.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|