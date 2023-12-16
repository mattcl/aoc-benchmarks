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
| mattcl | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.8 | 1.00 ± 0.33 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.8 | 1.8 | 1.02 ± 0.32 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.9 | 1.04 ± 0.34 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.9 | 1.06 ± 0.34 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 2.0 | 1.06 ± 0.35 |
| lanjian | input-chancalan | 1.2 ± 0.3 | 0.8 | 1.8 | 1.07 ± 0.34 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.10 ± 0.36 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.12 ± 0.36 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.15 ± 0.37 |
| mattcl-ts | input-chancalan | 15.1 ± 0.3 | 14.3 | 16.2 | 13.04 ± 3.19 |
| mattcl-ts | input-mattcl | 15.1 ± 0.3 | 14.3 | 16.1 | 13.08 ± 3.20 |
| mattcl-ts | input-lanjian | 15.2 ± 0.4 | 14.5 | 17.2 | 13.16 ± 3.23 |
| mattcl-ts | input-kcen | 15.2 ± 0.4 | 14.4 | 17.8 | 13.18 ± 3.24 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.4 | 16.9 | 13.25 ± 3.25 |
| pting | input-chancalan | 22.2 ± 0.7 | 21.1 | 25.4 | 19.23 ± 4.73 |
| mattcl-py | input-chancalan | 22.4 ± 0.8 | 21.3 | 25.5 | 19.36 ± 4.77 |
| pting | input-mattcl | 22.4 ± 0.7 | 21.1 | 25.6 | 19.37 ± 4.77 |
| mattcl-py | input-mattcl | 22.7 ± 3.4 | 21.2 | 60.1 | 19.67 ± 5.63 |
| pting | input-lanjian | 22.8 ± 0.6 | 21.9 | 25.4 | 19.77 ± 4.85 |
| mattcl-py | input-lanjian | 22.8 ± 0.8 | 21.7 | 25.6 | 19.78 ± 4.87 |
| pting | input-kcen | 22.9 ± 0.7 | 21.7 | 25.5 | 19.80 ± 4.87 |
| mattcl-py | input-kcen | 23.0 ± 0.8 | 21.8 | 25.9 | 19.90 ± 4.90 |
| pting | input-pting | 23.1 ± 0.8 | 21.7 | 26.0 | 20.03 ± 4.93 |
| mattcl-py | input-pting | 23.3 ± 0.8 | 22.0 | 26.6 | 20.19 ± 4.97 |
| chancalan | input-chancalan | 23.8 ± 0.9 | 22.3 | 27.2 | 20.58 ± 5.08 |
| chancalan | input-mattcl | 23.9 ± 0.9 | 22.8 | 26.9 | 20.71 ± 5.11 |
| chancalan | input-lanjian | 24.4 ± 0.7 | 23.2 | 27.3 | 21.09 ± 5.18 |
| chancalan | input-kcen | 24.6 ± 1.0 | 23.3 | 28.4 | 21.29 ± 5.27 |
| chancalan | input-pting | 24.7 ± 0.9 | 23.5 | 27.8 | 21.41 ± 5.28 |
| kcen | input-chancalan | 28.4 ± 1.4 | 26.8 | 37.5 | 24.57 ± 6.11 |
| kcen | input-mattcl | 28.5 ± 0.9 | 27.4 | 31.1 | 24.64 ± 6.05 |
| kcen | input-lanjian | 29.4 ± 1.0 | 27.9 | 33.8 | 25.43 ± 6.26 |
| kcen | input-kcen | 29.6 ± 0.8 | 28.2 | 33.0 | 25.58 ± 6.28 |
| kcen | input-pting | 30.2 ± 4.3 | 28.5 | 68.4 | 26.17 ± 7.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|