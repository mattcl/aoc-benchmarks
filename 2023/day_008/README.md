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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.9 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 1.8 | 1.02 ± 0.28 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.12 ± 0.33 |
| lanjian | input-lanjian | 1.3 ± 0.3 | 0.9 | 2.1 | 1.13 ± 0.33 |
| lanjian | input-kcen | 1.4 ± 0.3 | 1.0 | 2.0 | 1.20 ± 0.33 |
| lanjian | input-pting | 1.6 ± 0.2 | 1.2 | 2.4 | 1.43 ± 0.34 |
| mattcl | input-pting | 1.7 ± 0.3 | 1.2 | 3.0 | 1.51 ± 0.40 |
| mattcl | input-lanjian | 3.3 ± 6.7 | 0.9 | 41.8 | 2.85 ± 5.85 |
| mattcl-ts | input-mattcl | 15.2 ± 0.4 | 14.5 | 18.0 | 13.30 ± 2.75 |
| mattcl-ts | input-lanjian | 15.4 ± 0.4 | 14.5 | 16.9 | 13.44 ± 2.78 |
| mattcl-ts | input-kcen | 15.7 ± 2.2 | 14.8 | 35.3 | 13.74 ± 3.41 |
| mattcl-ts | input-pting | 20.5 ± 7.7 | 16.7 | 59.8 | 17.96 ± 7.71 |
| mattcl-py | input-mattcl | 22.5 ± 0.8 | 21.2 | 25.1 | 19.65 ± 4.09 |
| mattcl-py | input-lanjian | 22.9 ± 0.6 | 21.9 | 25.1 | 20.05 ± 4.15 |
| pting | input-kcen | 23.3 ± 0.7 | 22.1 | 29.3 | 20.38 ± 4.23 |
| mattcl-py | input-kcen | 24.7 ± 3.9 | 22.6 | 38.0 | 21.57 ± 5.57 |
| pting | input-lanjian | 24.8 ± 4.6 | 21.8 | 38.9 | 21.71 ± 6.02 |
| kcen | input-mattcl | 28.4 ± 0.8 | 27.4 | 31.4 | 24.88 ± 5.15 |
| pting | input-pting | 28.8 ± 0.8 | 27.5 | 31.0 | 25.18 ± 5.22 |
| kcen | input-lanjian | 29.7 ± 0.7 | 28.5 | 32.7 | 25.99 ± 5.37 |
| kcen | input-kcen | 30.0 ± 0.8 | 29.1 | 33.6 | 26.23 ± 5.43 |
| pting | input-mattcl | 30.8 ± 2.5 | 22.3 | 38.4 | 26.91 ± 5.93 |
| mattcl-py | input-pting | 31.1 ± 0.5 | 29.0 | 33.0 | 27.22 ± 5.61 |
| kcen | input-pting | 42.2 ± 0.7 | 40.0 | 44.5 | 36.93 ± 7.60 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|