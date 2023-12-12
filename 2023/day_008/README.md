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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 1.8 | 1.05 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 2.0 | 1.06 ± 0.31 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.9 | 1.8 | 1.07 ± 0.30 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 1.9 | 1.10 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.11 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.15 ± 0.33 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.1 | 1.20 ± 0.35 |
| mattcl-ts | input-mattcl | 15.0 ± 0.3 | 14.1 | 16.3 | 13.13 ± 2.69 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.2 | 16.3 | 13.15 ± 2.69 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 13.9 | 16.2 | 13.16 ± 2.70 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.0 | 16.3 | 13.20 ± 2.70 |
| pting | input-mattcl | 22.3 ± 0.6 | 21.5 | 24.7 | 19.47 ± 4.00 |
| mattcl-py | input-mattcl | 22.3 ± 0.8 | 21.4 | 25.9 | 19.48 ± 4.03 |
| pting | input-kcen | 22.6 ± 0.7 | 21.5 | 26.0 | 19.76 ± 4.08 |
| mattcl-py | input-lanjian | 22.8 ± 0.8 | 21.7 | 26.4 | 19.88 ± 4.11 |
| pting | input-lanjian | 22.8 ± 0.7 | 21.7 | 26.1 | 19.93 ± 4.11 |
| mattcl-py | input-kcen | 22.9 ± 1.1 | 21.8 | 26.8 | 19.97 ± 4.17 |
| mattcl-py | input-pting | 23.0 ± 0.8 | 22.1 | 26.0 | 20.09 ± 4.15 |
| pting | input-pting | 23.1 ± 0.7 | 22.2 | 25.7 | 20.14 ± 4.15 |
| kcen | input-mattcl | 28.2 ± 0.8 | 26.8 | 31.6 | 24.61 ± 5.06 |
| kcen | input-kcen | 29.1 ± 0.7 | 27.8 | 31.5 | 25.37 ± 5.21 |
| kcen | input-lanjian | 29.2 ± 0.9 | 28.0 | 32.4 | 25.44 ± 5.24 |
| kcen | input-pting | 29.4 ± 0.8 | 28.3 | 32.9 | 25.70 ± 5.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|