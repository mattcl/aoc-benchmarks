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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.9 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.9 | 2.0 | 1.00 ± 0.28 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.9 | 2.1 | 1.02 ± 0.28 |
| mattcl | input-pting | 1.3 ± 0.2 | 1.0 | 2.0 | 1.05 ± 0.29 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 1.0 | 2.1 | 1.06 ± 0.29 |
| mattcl | input-kcen | 1.3 ± 0.3 | 1.0 | 2.0 | 1.08 ± 0.31 |
| lanjian | input-pting | 1.4 ± 0.3 | 1.0 | 2.1 | 1.12 ± 0.32 |
| lanjian | input-kcen | 1.7 ± 4.1 | 1.0 | 59.5 | 1.35 ± 3.33 |
| mattcl-ts | input-mattcl | 14.7 ± 0.4 | 13.2 | 15.7 | 11.88 ± 2.46 |
| mattcl-ts | input-lanjian | 14.9 ± 0.3 | 13.9 | 15.6 | 12.05 ± 2.49 |
| mattcl-ts | input-kcen | 15.0 ± 0.3 | 14.0 | 16.1 | 12.06 ± 2.49 |
| mattcl-ts | input-pting | 15.0 ± 0.3 | 14.1 | 16.1 | 12.12 ± 2.50 |
| mattcl-py | input-mattcl | 22.4 ± 0.8 | 21.3 | 25.6 | 18.07 ± 3.76 |
| pting | input-mattcl | 22.5 ± 0.8 | 21.6 | 26.5 | 18.17 ± 3.79 |
| mattcl-py | input-lanjian | 22.7 ± 0.8 | 21.6 | 25.8 | 18.33 ± 3.82 |
| mattcl-py | input-kcen | 23.0 ± 0.8 | 21.9 | 26.1 | 18.52 ± 3.86 |
| pting | input-kcen | 23.0 ± 1.8 | 21.8 | 40.7 | 18.56 ± 4.07 |
| mattcl-py | input-pting | 23.0 ± 0.6 | 22.2 | 26.4 | 18.58 ± 3.84 |
| pting | input-lanjian | 23.1 ± 3.3 | 22.1 | 60.1 | 18.63 ± 4.66 |
| pting | input-pting | 23.2 ± 0.7 | 22.3 | 26.1 | 18.73 ± 3.89 |
| kcen | input-mattcl | 28.2 ± 0.6 | 27.3 | 31.3 | 22.77 ± 4.70 |
| kcen | input-lanjian | 29.2 ± 0.7 | 28.2 | 31.4 | 23.54 ± 4.86 |
| kcen | input-kcen | 29.7 ± 2.6 | 28.1 | 53.1 | 23.91 ± 5.34 |
| kcen | input-pting | 29.7 ± 0.9 | 28.8 | 32.6 | 23.98 ± 4.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|