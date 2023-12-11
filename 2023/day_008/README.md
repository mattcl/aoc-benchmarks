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
| mattcl | input-mattcl | 1.1 ± 0.3 | 0.8 | 1.7 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.9 | 1.07 ± 0.33 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.8 | 1.07 ± 0.34 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.9 | 1.08 ± 0.33 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 1.9 | 1.10 ± 0.34 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.9 | 1.10 ± 0.34 |
| lanjian | input-pting | 1.2 ± 0.3 | 0.8 | 2.0 | 1.13 ± 0.35 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.0 | 1.15 ± 0.35 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 14.4 | 16.7 | 13.65 ± 3.13 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.3 | 16.4 | 13.67 ± 3.13 |
| mattcl-ts | input-lanjian | 15.2 ± 0.3 | 14.3 | 16.3 | 13.68 ± 3.13 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.3 | 16.3 | 13.81 ± 3.17 |
| mattcl-py | input-mattcl | 22.2 ± 0.7 | 21.1 | 25.2 | 20.07 ± 4.62 |
| pting | input-mattcl | 22.7 ± 3.0 | 21.4 | 50.1 | 20.48 ± 5.37 |
| pting | input-kcen | 22.7 ± 0.7 | 21.8 | 26.1 | 20.52 ± 4.72 |
| mattcl-py | input-lanjian | 22.8 ± 1.1 | 21.5 | 32.7 | 20.56 ± 4.80 |
| mattcl-py | input-kcen | 22.8 ± 0.8 | 21.4 | 26.1 | 20.56 ± 4.74 |
| pting | input-lanjian | 22.8 ± 0.7 | 21.7 | 25.6 | 20.56 ± 4.74 |
| pting | input-pting | 23.2 ± 0.8 | 21.9 | 25.7 | 20.91 ± 4.83 |
| mattcl-py | input-pting | 23.2 ± 1.0 | 22.2 | 31.5 | 20.96 ± 4.87 |
| kcen | input-mattcl | 28.3 ± 0.9 | 26.9 | 31.2 | 25.56 ± 5.88 |
| kcen | input-lanjian | 29.0 ± 0.9 | 27.7 | 34.1 | 26.20 ± 6.03 |
| kcen | input-kcen | 29.3 ± 0.9 | 28.0 | 32.5 | 26.43 ± 6.08 |
| kcen | input-pting | 29.7 ± 1.0 | 28.3 | 33.2 | 26.77 ± 6.16 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|