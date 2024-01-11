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
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.9 | 1.05 ± 0.32 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.0 | 1.05 ± 0.32 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.9 | 1.9 | 1.05 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.9 | 1.06 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.1 | 1.07 ± 0.33 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.08 ± 0.33 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 1.9 | 1.09 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.12 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.15 ± 0.34 |
| mattcl-ts | input-chancalan | 14.9 ± 0.3 | 14.0 | 15.7 | 13.00 ± 2.74 |
| mattcl-ts | input-mattcl | 15.1 ± 0.3 | 14.2 | 16.1 | 13.15 ± 2.78 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 14.2 | 16.3 | 13.20 ± 2.79 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.2 | 16.2 | 13.20 ± 2.79 |
| mattcl-ts | input-pting | 15.2 ± 0.3 | 14.5 | 16.1 | 13.24 ± 2.80 |
| pting | input-chancalan | 22.0 ± 1.0 | 20.4 | 25.5 | 19.21 ± 4.13 |
| mattcl-py | input-chancalan | 22.1 ± 0.9 | 21.0 | 25.5 | 19.30 ± 4.13 |
| mattcl-py | input-mattcl | 22.2 ± 0.7 | 21.0 | 25.2 | 19.35 ± 4.11 |
| pting | input-mattcl | 22.2 ± 0.8 | 21.2 | 25.6 | 19.39 ± 4.13 |
| mattcl-py | input-lanjian | 22.5 ± 0.7 | 21.3 | 25.3 | 19.62 ± 4.17 |
| pting | input-kcen | 22.7 ± 0.8 | 21.3 | 25.7 | 19.79 ± 4.22 |
| pting | input-lanjian | 22.7 ± 0.9 | 21.5 | 26.1 | 19.80 ± 4.23 |
| mattcl-py | input-kcen | 22.8 ± 0.9 | 21.5 | 29.0 | 19.91 ± 4.26 |
| pting | input-pting | 23.0 ± 0.9 | 21.6 | 26.3 | 20.01 ± 4.27 |
| mattcl-py | input-pting | 23.0 ± 0.9 | 21.9 | 26.2 | 20.04 ± 4.28 |
| chancalan | input-chancalan | 23.5 ± 0.7 | 22.7 | 26.2 | 20.45 ± 4.33 |
| chancalan | input-mattcl | 23.7 ± 0.8 | 22.4 | 26.6 | 20.67 ± 4.40 |
| chancalan | input-lanjian | 24.2 ± 0.9 | 22.7 | 26.8 | 21.07 ± 4.49 |
| chancalan | input-kcen | 24.2 ± 0.8 | 22.6 | 27.2 | 21.12 ± 4.50 |
| chancalan | input-pting | 24.4 ± 0.9 | 23.2 | 27.7 | 21.28 ± 4.53 |
| kcen | input-chancalan | 28.1 ± 1.1 | 26.4 | 31.3 | 24.47 ± 5.22 |
| kcen | input-mattcl | 28.6 ± 3.9 | 26.8 | 67.6 | 24.90 ± 6.26 |
| kcen | input-lanjian | 28.9 ± 0.8 | 27.6 | 31.6 | 25.23 ± 5.34 |
| kcen | input-kcen | 29.2 ± 1.0 | 27.7 | 32.2 | 25.44 ± 5.41 |
| kcen | input-pting | 29.7 ± 0.8 | 28.6 | 32.5 | 25.90 ± 5.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|