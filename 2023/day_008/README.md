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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.8 | 1.03 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 2.0 | 1.05 ± 0.31 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.8 | 1.07 ± 0.32 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.9 | 1.08 ± 0.33 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.9 | 1.9 | 1.09 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 2.0 | 1.10 ± 0.33 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.9 | 1.11 ± 0.34 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.18 ± 0.34 |
| lanjian | input-pting | 1.5 ± 4.4 | 0.9 | 63.9 | 1.35 ± 3.95 |
| mattcl-ts | input-chancalan | 14.7 ± 0.4 | 13.8 | 15.6 | 13.00 ± 2.81 |
| mattcl-ts | input-mattcl | 14.8 ± 0.3 | 13.8 | 15.5 | 13.10 ± 2.83 |
| mattcl-ts | input-kcen | 14.9 ± 0.3 | 13.8 | 16.0 | 13.20 ± 2.85 |
| mattcl-ts | input-lanjian | 14.9 ± 0.3 | 13.9 | 16.1 | 13.21 ± 2.85 |
| mattcl-ts | input-pting | 14.9 ± 0.4 | 13.7 | 16.1 | 13.22 ± 2.86 |
| mattcl-py | input-chancalan | 22.1 ± 0.6 | 21.1 | 24.7 | 19.63 ± 4.25 |
| mattcl-py | input-mattcl | 22.2 ± 0.6 | 21.4 | 24.9 | 19.66 ± 4.26 |
| pting | input-mattcl | 22.3 ± 0.6 | 21.4 | 25.6 | 19.78 ± 4.29 |
| pting | input-chancalan | 22.3 ± 0.9 | 21.3 | 26.1 | 19.80 ± 4.32 |
| pting | input-lanjian | 22.8 ± 0.8 | 21.6 | 26.0 | 20.20 ± 4.40 |
| mattcl-py | input-lanjian | 22.8 ± 0.8 | 21.4 | 25.7 | 20.26 ± 4.42 |
| mattcl-py | input-pting | 23.0 ± 0.9 | 22.0 | 26.4 | 20.42 ± 4.46 |
| pting | input-pting | 23.0 ± 0.9 | 21.6 | 26.4 | 20.43 ± 4.46 |
| mattcl-py | input-kcen | 23.1 ± 0.9 | 21.8 | 26.2 | 20.46 ± 4.48 |
| pting | input-kcen | 23.2 ± 3.3 | 21.6 | 59.4 | 20.60 ± 5.32 |
| chancalan | input-chancalan | 24.0 ± 2.6 | 22.6 | 51.1 | 21.32 ± 5.13 |
| chancalan | input-mattcl | 24.2 ± 0.9 | 22.8 | 27.2 | 21.44 ± 4.68 |
| chancalan | input-lanjian | 24.6 ± 0.8 | 23.5 | 27.3 | 21.84 ± 4.75 |
| chancalan | input-kcen | 24.8 ± 0.8 | 23.5 | 27.7 | 21.96 ± 4.78 |
| chancalan | input-pting | 24.9 ± 0.9 | 23.8 | 28.7 | 22.05 ± 4.81 |
| kcen | input-chancalan | 28.1 ± 0.9 | 26.9 | 30.9 | 24.91 ± 5.41 |
| kcen | input-mattcl | 28.2 ± 0.8 | 27.2 | 30.9 | 25.03 ± 5.43 |
| kcen | input-lanjian | 29.3 ± 1.0 | 27.8 | 32.8 | 25.95 ± 5.65 |
| kcen | input-kcen | 29.4 ± 1.1 | 27.7 | 33.3 | 26.08 ± 5.69 |
| kcen | input-pting | 29.6 ± 0.9 | 28.0 | 32.7 | 26.28 ± 5.71 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|