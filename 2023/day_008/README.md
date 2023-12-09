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
| mattcl | input-mattcl | 1.1 ± 0.3 | 0.8 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.8 | 1.8 | 1.05 ± 0.33 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.8 | 1.8 | 1.05 ± 0.34 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.8 | 1.9 | 1.07 ± 0.34 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.0 | 1.08 ± 0.35 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.8 | 2.0 | 1.12 ± 0.34 |
| lanjian | input-pting | 1.3 ± 0.3 | 0.9 | 1.9 | 1.17 ± 0.36 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.18 ± 0.36 |
| mattcl-ts | input-mattcl | 14.6 ± 0.4 | 13.5 | 15.8 | 13.34 ± 3.16 |
| mattcl-ts | input-lanjian | 14.7 ± 0.4 | 13.8 | 15.7 | 13.45 ± 3.18 |
| mattcl-ts | input-pting | 15.0 ± 2.9 | 13.6 | 55.6 | 13.76 ± 4.19 |
| mattcl-ts | input-kcen | 15.5 ± 6.8 | 13.8 | 79.3 | 14.23 ± 7.03 |
| pting | input-mattcl | 22.4 ± 0.9 | 21.2 | 25.4 | 20.52 ± 4.90 |
| mattcl-py | input-mattcl | 22.4 ± 3.1 | 21.1 | 56.6 | 20.54 ± 5.58 |
| mattcl-py | input-lanjian | 22.5 ± 0.8 | 21.4 | 26.1 | 20.62 ± 4.90 |
| mattcl-py | input-kcen | 22.6 ± 0.8 | 21.6 | 26.3 | 20.70 ± 4.93 |
| pting | input-kcen | 22.6 ± 0.8 | 21.5 | 26.0 | 20.70 ± 4.93 |
| pting | input-lanjian | 22.8 ± 0.9 | 21.6 | 26.0 | 20.85 ± 4.98 |
| mattcl-py | input-pting | 22.9 ± 0.8 | 22.0 | 26.3 | 21.00 ± 5.00 |
| pting | input-pting | 23.1 ± 1.0 | 22.1 | 28.7 | 21.14 ± 5.05 |
| kcen | input-mattcl | 28.0 ± 0.9 | 26.8 | 32.2 | 25.69 ± 6.11 |
| kcen | input-lanjian | 28.9 ± 0.8 | 27.7 | 31.6 | 26.49 ± 6.28 |
| kcen | input-kcen | 29.0 ± 1.1 | 27.7 | 32.4 | 26.58 ± 6.34 |
| kcen | input-pting | 29.6 ± 1.0 | 28.4 | 32.8 | 27.11 ± 6.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|