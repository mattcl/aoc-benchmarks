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
| mattcl | input-mattcl | 1.1 ± 0.3 | 0.7 | 3.2 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.8 | 1.9 | 1.04 ± 0.35 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.9 | 1.05 ± 0.36 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.0 | 1.05 ± 0.36 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.07 ± 0.37 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.8 | 2.0 | 1.09 ± 0.37 |
| lanjian | input-pting | 1.2 ± 0.3 | 0.8 | 2.0 | 1.12 ± 0.38 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.14 ± 0.39 |
| mattcl-ts | input-mattcl | 14.3 ± 0.4 | 13.5 | 15.9 | 13.00 ± 3.47 |
| mattcl-ts | input-kcen | 14.4 ± 0.4 | 13.3 | 15.8 | 13.07 ± 3.49 |
| mattcl-ts | input-lanjian | 14.4 ± 0.4 | 13.4 | 15.6 | 13.11 ± 3.50 |
| mattcl-ts | input-pting | 14.6 ± 0.4 | 13.3 | 15.8 | 13.23 ± 3.54 |
| mattcl-py | input-mattcl | 22.1 ± 0.5 | 21.2 | 24.6 | 20.04 ± 5.34 |
| pting | input-mattcl | 22.1 ± 0.7 | 21.2 | 25.6 | 20.09 ± 5.37 |
| pting | input-kcen | 22.7 ± 0.9 | 21.2 | 27.8 | 20.57 ± 5.52 |
| pting | input-lanjian | 22.7 ± 0.6 | 21.8 | 25.6 | 20.58 ± 5.49 |
| mattcl-py | input-lanjian | 22.7 ± 0.8 | 21.5 | 25.9 | 20.58 ± 5.52 |
| pting | input-pting | 22.9 ± 0.7 | 21.7 | 26.9 | 20.81 ± 5.57 |
| mattcl-py | input-kcen | 23.0 ± 0.9 | 21.8 | 26.3 | 20.84 ± 5.60 |
| mattcl-py | input-pting | 23.0 ± 0.9 | 21.7 | 26.4 | 20.87 ± 5.60 |
| kcen | input-mattcl | 28.2 ± 0.8 | 26.9 | 30.7 | 25.64 ± 6.85 |
| kcen | input-lanjian | 29.1 ± 0.9 | 27.7 | 32.1 | 26.45 ± 7.07 |
| kcen | input-kcen | 29.3 ± 1.0 | 27.9 | 32.7 | 26.58 ± 7.12 |
| kcen | input-pting | 29.5 ± 0.8 | 28.1 | 32.4 | 26.77 ± 7.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|