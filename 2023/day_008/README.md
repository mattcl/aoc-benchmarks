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

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.8 | 1.8 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.9 | 2.0 | 1.05 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.9 | 1.9 | 1.05 ± 0.32 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.8 | 1.06 ± 0.33 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.9 | 2.1 | 1.09 ± 0.32 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.9 | 2.2 | 1.11 ± 0.33 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 2.2 | 1.14 ± 0.35 |
| lanjian | input-kcen | 1.7 ± 5.1 | 0.9 | 72.7 | 1.45 ± 4.37 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.1 | 16.4 | 13.06 ± 2.99 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.6 | 16.6 | 13.17 ± 3.01 |
| mattcl-ts | input-kcen | 15.3 ± 0.4 | 14.4 | 16.5 | 13.19 ± 3.02 |
| mattcl-ts | input-pting | 15.4 ± 0.4 | 14.5 | 16.8 | 13.26 ± 3.04 |
| mattcl-py | input-mattcl | 22.4 ± 0.7 | 21.4 | 25.0 | 19.32 ± 4.44 |
| pting | input-mattcl | 22.6 ± 0.9 | 21.5 | 25.6 | 19.48 ± 4.50 |
| pting | input-kcen | 22.8 ± 0.8 | 21.8 | 26.2 | 19.68 ± 4.53 |
| mattcl-py | input-lanjian | 22.9 ± 0.8 | 21.8 | 25.6 | 19.73 ± 4.54 |
| pting | input-lanjian | 22.9 ± 0.6 | 21.9 | 25.6 | 19.73 ± 4.52 |
| mattcl-py | input-kcen | 23.0 ± 1.4 | 22.0 | 34.4 | 19.85 ± 4.67 |
| pting | input-pting | 23.2 ± 0.6 | 22.4 | 27.0 | 20.02 ± 4.59 |
| mattcl-py | input-pting | 23.3 ± 0.9 | 22.3 | 26.1 | 20.13 ± 4.64 |
| kcen | input-mattcl | 28.6 ± 1.0 | 27.1 | 31.2 | 24.68 ± 5.68 |
| kcen | input-lanjian | 29.4 ± 1.0 | 28.0 | 32.3 | 25.35 ± 5.84 |
| kcen | input-kcen | 29.5 ± 1.8 | 27.6 | 42.3 | 25.46 ± 6.00 |
| kcen | input-pting | 29.7 ± 0.8 | 28.4 | 32.4 | 25.66 ± 5.89 |
| chancalan | input-mattcl | 32.8 ± 0.8 | 31.5 | 35.5 | 28.28 ± 6.47 |
| chancalan | input-kcen | 33.6 ± 0.9 | 32.4 | 36.4 | 29.03 ± 6.65 |
| chancalan | input-lanjian | 33.8 ± 1.1 | 32.4 | 36.7 | 29.20 ± 6.71 |
| chancalan | input-pting | 34.2 ± 0.8 | 32.9 | 37.1 | 29.48 ± 6.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|