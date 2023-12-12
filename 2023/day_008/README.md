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
| lanjian | input-lanjian | 1.3 ± 0.2 | 1.0 | 2.2 | 1.02 ± 0.27 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.9 | 2.0 | 1.04 ± 0.30 |
| mattcl | input-pting | 1.3 ± 0.3 | 0.9 | 2.1 | 1.04 ± 0.30 |
| lanjian | input-pting | 1.3 ± 0.2 | 1.0 | 2.2 | 1.07 ± 0.29 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.1 | 1.07 ± 0.31 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.2 | 1.15 ± 0.33 |
| mattcl | input-lanjian | 1.4 ± 2.8 | 0.9 | 40.7 | 1.17 ± 2.29 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 13.9 | 16.6 | 12.28 ± 2.53 |
| mattcl-ts | input-pting | 15.1 ± 0.4 | 14.3 | 19.5 | 12.33 ± 2.55 |
| mattcl-ts | input-lanjian | 15.6 ± 4.0 | 14.3 | 60.8 | 12.71 ± 4.15 |
| mattcl-ts | input-mattcl | 17.3 ± 8.3 | 14.2 | 52.1 | 14.11 ± 7.36 |
| mattcl-py | input-mattcl | 22.4 ± 0.7 | 21.5 | 26.6 | 18.25 ± 3.77 |
| pting | input-mattcl | 22.8 ± 1.3 | 21.4 | 32.7 | 18.52 ± 3.93 |
| mattcl-py | input-kcen | 23.0 ± 0.8 | 21.9 | 26.5 | 18.71 ± 3.88 |
| pting | input-pting | 23.2 ± 0.9 | 21.9 | 26.6 | 18.91 ± 3.94 |
| mattcl-py | input-pting | 23.3 ± 0.8 | 21.8 | 26.8 | 19.00 ± 3.94 |
| pting | input-kcen | 23.4 ± 2.4 | 21.6 | 49.1 | 19.01 ± 4.36 |
| pting | input-lanjian | 23.6 ± 0.7 | 22.6 | 27.9 | 19.25 ± 3.98 |
| mattcl-py | input-lanjian | 23.7 ± 2.9 | 22.1 | 55.6 | 19.27 ± 4.61 |
| kcen | input-mattcl | 29.0 ± 0.7 | 27.6 | 31.5 | 23.58 ± 4.86 |
| kcen | input-kcen | 29.5 ± 1.0 | 28.1 | 33.6 | 24.02 ± 4.98 |
| kcen | input-lanjian | 29.5 ± 1.0 | 28.0 | 33.0 | 24.03 ± 4.98 |
| kcen | input-pting | 30.2 ± 2.0 | 28.2 | 46.3 | 24.57 ± 5.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|