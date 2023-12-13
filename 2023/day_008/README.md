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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.9 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 2.0 | 1.03 ± 0.29 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.9 | 1.05 ± 0.33 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.05 ± 0.30 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 2.1 | 1.08 ± 0.30 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 1.9 | 1.09 ± 0.32 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.10 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.2 | 1.15 ± 0.33 |
| mattcl-ts | input-mattcl | 15.2 ± 0.3 | 14.3 | 16.3 | 12.55 ± 2.65 |
| mattcl-ts | input-kcen | 15.2 ± 0.4 | 14.5 | 17.0 | 12.62 ± 2.66 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.4 | 17.6 | 12.66 ± 2.67 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.6 | 17.1 | 12.70 ± 2.68 |
| mattcl-py | input-mattcl | 22.3 ± 0.6 | 21.5 | 25.7 | 18.47 ± 3.90 |
| pting | input-mattcl | 22.4 ± 0.6 | 21.4 | 25.5 | 18.55 ± 3.92 |
| mattcl-py | input-lanjian | 22.8 ± 0.8 | 21.6 | 26.1 | 18.88 ± 4.01 |
| pting | input-lanjian | 22.9 ± 0.8 | 21.7 | 25.5 | 18.98 ± 4.03 |
| pting | input-kcen | 22.9 ± 0.7 | 21.8 | 25.5 | 18.98 ± 4.02 |
| mattcl-py | input-kcen | 23.0 ± 0.7 | 22.0 | 25.7 | 19.08 ± 4.05 |
| pting | input-pting | 23.4 ± 1.0 | 21.9 | 26.7 | 19.37 ± 4.14 |
| mattcl-py | input-pting | 23.4 ± 0.7 | 22.3 | 26.1 | 19.40 ± 4.11 |
| kcen | input-mattcl | 28.3 ± 0.8 | 27.0 | 31.3 | 23.46 ± 4.97 |
| kcen | input-lanjian | 29.3 ± 1.0 | 28.0 | 33.1 | 24.22 ± 5.14 |
| kcen | input-kcen | 29.6 ± 0.9 | 28.2 | 32.4 | 24.48 ± 5.19 |
| kcen | input-pting | 29.8 ± 0.8 | 28.8 | 33.4 | 24.70 ± 5.22 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|