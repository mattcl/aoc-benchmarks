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
| mattcl | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.7 | 1.00 |
| mattcl | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.02 ± 0.31 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.02 ± 0.31 |
| lanjian | input-chancalan | 1.3 ± 0.3 | 0.9 | 2.0 | 1.03 ± 0.31 |
| mattcl | input-kcen | 1.3 ± 0.2 | 1.0 | 2.0 | 1.03 ± 0.30 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.0 | 1.04 ± 0.31 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.04 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.07 ± 0.32 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.0 | 2.2 | 1.09 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.1 | 1.13 ± 0.33 |
| mattcl-ts | input-chancalan | 14.9 ± 0.4 | 14.0 | 16.1 | 11.77 ± 2.65 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.1 | 16.2 | 11.85 ± 2.67 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.1 | 16.1 | 11.93 ± 2.68 |
| mattcl-ts | input-lanjian | 15.1 ± 0.4 | 13.9 | 17.7 | 11.93 ± 2.69 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.3 | 16.1 | 11.98 ± 2.69 |
| pting | input-chancalan | 22.2 ± 0.7 | 21.3 | 25.2 | 17.58 ± 3.97 |
| mattcl-py | input-chancalan | 22.2 ± 0.8 | 21.3 | 26.0 | 17.58 ± 3.99 |
| mattcl-py | input-mattcl | 22.4 ± 0.7 | 21.1 | 25.1 | 17.73 ± 4.00 |
| pting | input-mattcl | 22.5 ± 0.8 | 21.3 | 26.1 | 17.85 ± 4.05 |
| pting | input-kcen | 22.9 ± 0.6 | 22.0 | 25.2 | 18.14 ± 4.09 |
| mattcl-py | input-lanjian | 22.9 ± 0.8 | 21.8 | 25.4 | 18.16 ± 4.11 |
| mattcl-py | input-kcen | 23.0 ± 0.8 | 21.7 | 26.5 | 18.25 ± 4.14 |
| pting | input-lanjian | 23.1 ± 0.8 | 22.0 | 26.3 | 18.31 ± 4.15 |
| pting | input-pting | 23.2 ± 0.8 | 22.1 | 26.8 | 18.42 ± 4.17 |
| mattcl-py | input-pting | 23.3 ± 0.8 | 21.9 | 26.7 | 18.48 ± 4.19 |
| chancalan | input-chancalan | 23.9 ± 0.9 | 22.7 | 27.2 | 18.94 ± 4.30 |
| chancalan | input-mattcl | 24.3 ± 0.8 | 22.7 | 27.2 | 19.26 ± 4.36 |
| chancalan | input-lanjian | 24.7 ± 0.9 | 23.2 | 27.9 | 19.58 ± 4.44 |
| chancalan | input-kcen | 24.9 ± 0.9 | 23.2 | 28.1 | 19.71 ± 4.47 |
| chancalan | input-pting | 25.3 ± 3.3 | 23.8 | 59.3 | 20.07 ± 5.18 |
| kcen | input-chancalan | 28.0 ± 0.8 | 26.6 | 30.7 | 22.19 ± 5.01 |
| kcen | input-mattcl | 28.4 ± 1.0 | 27.0 | 31.7 | 22.54 ± 5.11 |
| kcen | input-lanjian | 29.2 ± 1.1 | 28.0 | 34.4 | 23.13 ± 5.25 |
| kcen | input-kcen | 29.4 ± 0.8 | 28.3 | 32.0 | 23.30 ± 5.26 |
| kcen | input-pting | 29.9 ± 0.9 | 28.9 | 34.3 | 23.71 ± 5.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15871</pre>|<pre>11283670395017</pre>|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|