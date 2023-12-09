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
| mattcl | input-mattcl | 1.1 ± 0.3 | 0.8 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.8 | 1.8 | 1.02 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.8 | 1.03 ± 0.31 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.8 | 2.0 | 1.09 ± 0.35 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.9 | 1.10 ± 0.36 |
| lanjian | input-pting | 1.3 ± 0.4 | 0.9 | 5.1 | 1.16 ± 0.46 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.19 ± 0.38 |
| mattcl | input-pting | 1.6 ± 5.5 | 0.8 | 78.9 | 1.38 ± 4.88 |
| mattcl-ts | input-mattcl | 14.8 ± 0.4 | 13.8 | 17.1 | 13.04 ± 3.14 |
| mattcl-ts | input-kcen | 14.8 ± 0.4 | 13.8 | 16.8 | 13.12 ± 3.15 |
| mattcl-ts | input-lanjian | 14.9 ± 0.4 | 14.0 | 17.0 | 13.16 ± 3.16 |
| mattcl-ts | input-pting | 14.9 ± 0.3 | 13.9 | 16.5 | 13.21 ± 3.17 |
| mattcl-py | input-mattcl | 22.3 ± 0.7 | 21.0 | 25.5 | 19.75 ± 4.76 |
| pting | input-mattcl | 22.5 ± 0.8 | 21.3 | 25.8 | 19.85 ± 4.79 |
| mattcl-py | input-lanjian | 22.8 ± 0.8 | 21.6 | 25.8 | 20.16 ± 4.87 |
| mattcl-py | input-kcen | 22.9 ± 0.6 | 22.0 | 24.9 | 20.21 ± 4.86 |
| pting | input-kcen | 22.9 ± 0.8 | 21.6 | 26.0 | 20.22 ± 4.89 |
| pting | input-lanjian | 23.0 ± 1.0 | 21.9 | 28.1 | 20.33 ± 4.93 |
| pting | input-pting | 23.0 ± 0.7 | 22.0 | 25.7 | 20.36 ± 4.90 |
| mattcl-py | input-pting | 23.2 ± 1.1 | 21.6 | 31.1 | 20.47 ± 4.98 |
| kcen | input-mattcl | 28.5 ± 1.7 | 27.2 | 43.2 | 25.19 ± 6.20 |
| kcen | input-lanjian | 29.1 ± 0.8 | 27.9 | 32.2 | 25.74 ± 6.19 |
| kcen | input-kcen | 29.2 ± 0.9 | 27.7 | 32.1 | 25.80 ± 6.22 |
| kcen | input-pting | 29.6 ± 0.9 | 28.3 | 33.4 | 26.15 ± 6.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|