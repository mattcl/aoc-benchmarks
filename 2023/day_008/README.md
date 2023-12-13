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

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.9 | 2.0 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 2.0 | 1.01 ± 0.29 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 2.6 | 1.02 ± 0.31 |
| lanjian | input-pting | 1.3 ± 0.3 | 1.0 | 2.1 | 1.09 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.10 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.2 | 1.15 ± 0.33 |
| mattcl | input-pting | 1.5 ± 3.0 | 0.9 | 43.2 | 1.21 ± 2.48 |
| mattcl | input-kcen | 1.5 ± 3.5 | 0.9 | 50.9 | 1.26 ± 2.92 |
| mattcl-ts | input-mattcl | 14.9 ± 0.3 | 14.0 | 15.8 | 12.36 ± 2.63 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.2 | 16.0 | 12.43 ± 2.64 |
| mattcl-ts | input-kcen | 15.0 ± 0.3 | 14.2 | 15.8 | 12.43 ± 2.64 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.2 | 16.1 | 12.48 ± 2.65 |
| mattcl-py | input-mattcl | 22.4 ± 0.7 | 21.3 | 25.6 | 18.54 ± 3.97 |
| pting | input-mattcl | 22.5 ± 0.8 | 21.4 | 26.1 | 18.58 ± 3.98 |
| mattcl-py | input-lanjian | 22.8 ± 0.7 | 21.8 | 26.1 | 18.82 ± 4.03 |
| pting | input-kcen | 22.9 ± 0.8 | 21.8 | 26.3 | 18.93 ± 4.06 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.6 | 26.4 | 18.98 ± 4.07 |
| mattcl-py | input-kcen | 23.0 ± 0.7 | 21.8 | 25.5 | 19.03 ± 4.07 |
| pting | input-pting | 23.1 ± 0.7 | 21.7 | 26.0 | 19.08 ± 4.08 |
| mattcl-py | input-pting | 24.1 ± 5.3 | 22.1 | 58.9 | 19.92 ± 6.09 |
| kcen | input-mattcl | 28.4 ± 0.9 | 26.8 | 31.0 | 23.48 ± 5.02 |
| kcen | input-lanjian | 29.2 ± 0.7 | 28.1 | 31.9 | 24.13 ± 5.14 |
| kcen | input-kcen | 29.2 ± 0.8 | 27.9 | 32.5 | 24.17 ± 5.16 |
| kcen | input-pting | 29.6 ± 0.8 | 28.0 | 32.8 | 24.45 ± 5.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|