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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 1.9 | 1.04 ± 0.30 |
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 2.0 | 1.05 ± 0.31 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.8 | 1.9 | 1.06 ± 0.30 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.9 | 1.8 | 1.06 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.9 | 2.0 | 1.08 ± 0.32 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 2.0 | 1.10 ± 0.31 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.8 | 2.0 | 1.10 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.9 | 2.1 | 1.15 ± 0.31 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.9 | 2.0 | 1.17 ± 0.32 |
| mattcl-ts | input-chancalan | 14.9 ± 0.3 | 14.1 | 16.0 | 12.97 ± 2.67 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.0 | 15.8 | 13.06 ± 2.69 |
| mattcl-ts | input-kcen | 15.0 ± 0.3 | 14.2 | 16.2 | 13.11 ± 2.69 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.3 | 15.9 | 13.14 ± 2.70 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.0 | 16.5 | 13.17 ± 2.70 |
| pting | input-chancalan | 22.0 ± 0.6 | 21.1 | 25.1 | 19.23 ± 3.97 |
| mattcl-py | input-chancalan | 22.0 ± 0.9 | 20.9 | 25.5 | 19.25 ± 4.01 |
| pting | input-mattcl | 22.3 ± 0.8 | 21.4 | 25.9 | 19.50 ± 4.04 |
| mattcl-py | input-mattcl | 22.4 ± 0.8 | 21.4 | 25.2 | 19.52 ± 4.05 |
| mattcl-py | input-lanjian | 22.7 ± 0.8 | 21.7 | 26.1 | 19.78 ± 4.10 |
| pting | input-kcen | 22.8 ± 0.8 | 21.9 | 26.0 | 19.90 ± 4.13 |
| pting | input-lanjian | 22.8 ± 0.8 | 21.9 | 25.6 | 19.93 ± 4.13 |
| mattcl-py | input-kcen | 22.8 ± 0.8 | 22.0 | 26.5 | 19.94 ± 4.13 |
| mattcl-py | input-pting | 23.1 ± 0.8 | 22.0 | 26.3 | 20.13 ± 4.18 |
| pting | input-pting | 23.1 ± 0.8 | 21.8 | 25.7 | 20.14 ± 4.18 |
| chancalan | input-chancalan | 23.5 ± 1.1 | 22.3 | 33.7 | 20.50 ± 4.31 |
| chancalan | input-mattcl | 23.7 ± 0.7 | 22.7 | 26.9 | 20.67 ± 4.27 |
| chancalan | input-lanjian | 24.2 ± 0.8 | 23.3 | 27.3 | 21.14 ± 4.38 |
| chancalan | input-kcen | 24.4 ± 0.9 | 23.3 | 27.4 | 21.33 ± 4.44 |
| chancalan | input-pting | 24.8 ± 2.6 | 23.5 | 52.5 | 21.66 ± 4.99 |
| kcen | input-chancalan | 28.0 ± 1.0 | 26.8 | 31.2 | 24.44 ± 5.07 |
| kcen | input-mattcl | 28.2 ± 0.6 | 27.4 | 30.8 | 24.59 ± 5.05 |
| kcen | input-kcen | 29.1 ± 0.7 | 28.0 | 32.0 | 25.44 ± 5.23 |
| kcen | input-lanjian | 29.2 ± 0.9 | 27.8 | 32.3 | 25.49 ± 5.27 |
| kcen | input-pting | 30.3 ± 5.5 | 28.4 | 83.4 | 26.46 ± 7.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|