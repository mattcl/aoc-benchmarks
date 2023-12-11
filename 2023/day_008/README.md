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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.4 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.9 | 2.0 | 1.02 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.9 | 2.1 | 1.03 ± 0.33 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 1.9 | 1.04 ± 0.33 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 1.9 | 1.06 ± 0.33 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.0 | 1.10 ± 0.35 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.0 | 1.11 ± 0.34 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.2 | 1.15 ± 0.35 |
| mattcl-ts | input-mattcl | 15.2 ± 0.3 | 14.1 | 16.0 | 12.59 ± 2.99 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.5 | 16.4 | 12.70 ± 3.02 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.6 | 17.1 | 12.75 ± 3.04 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 14.5 | 16.3 | 12.75 ± 3.03 |
| mattcl-py | input-mattcl | 22.4 ± 0.9 | 21.2 | 26.3 | 18.64 ± 4.47 |
| pting | input-mattcl | 22.4 ± 0.8 | 21.1 | 26.2 | 18.65 ± 4.46 |
| mattcl-py | input-kcen | 22.9 ± 0.7 | 21.8 | 25.9 | 19.04 ± 4.55 |
| pting | input-kcen | 22.9 ± 0.7 | 21.9 | 25.8 | 19.05 ± 4.55 |
| pting | input-lanjian | 23.0 ± 0.6 | 22.0 | 25.1 | 19.07 ± 4.55 |
| mattcl-py | input-lanjian | 23.0 ± 0.9 | 21.7 | 25.9 | 19.12 ± 4.59 |
| pting | input-pting | 23.2 ± 0.8 | 22.0 | 26.5 | 19.29 ± 4.62 |
| mattcl-py | input-pting | 23.3 ± 1.1 | 21.8 | 30.9 | 19.37 ± 4.67 |
| kcen | input-mattcl | 28.5 ± 0.8 | 27.2 | 31.4 | 23.66 ± 5.64 |
| kcen | input-lanjian | 29.3 ± 0.7 | 28.0 | 32.6 | 24.38 ± 5.81 |
| kcen | input-kcen | 29.5 ± 0.8 | 28.6 | 32.0 | 24.48 ± 5.83 |
| kcen | input-pting | 29.7 ± 0.9 | 28.4 | 33.0 | 24.72 ± 5.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|