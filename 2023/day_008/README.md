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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.8 | 1.00 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.9 | 1.02 ± 0.31 |
| mattcl | input-lanjian | 1.1 ± 0.3 | 0.8 | 1.7 | 1.03 ± 0.32 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 2.2 | 1.06 ± 0.33 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.8 | 2.6 | 1.09 ± 0.33 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.9 | 1.10 ± 0.34 |
| lanjian | input-pting | 1.2 ± 0.3 | 0.8 | 2.1 | 1.12 ± 0.34 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.18 ± 0.35 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.1 | 17.0 | 13.58 ± 2.97 |
| mattcl-ts | input-kcen | 15.2 ± 0.3 | 14.2 | 16.4 | 13.63 ± 2.97 |
| mattcl-ts | input-lanjian | 15.3 ± 0.4 | 14.3 | 17.1 | 13.70 ± 3.00 |
| mattcl-ts | input-pting | 15.3 ± 0.4 | 14.5 | 16.4 | 13.73 ± 3.00 |
| mattcl-py | input-mattcl | 22.3 ± 0.9 | 21.5 | 30.8 | 20.02 ± 4.42 |
| pting | input-mattcl | 22.5 ± 0.8 | 21.6 | 25.6 | 20.22 ± 4.45 |
| mattcl-py | input-lanjian | 22.9 ± 0.8 | 21.7 | 26.2 | 20.56 ± 4.53 |
| pting | input-lanjian | 23.0 ± 0.8 | 21.8 | 26.3 | 20.64 ± 4.54 |
| mattcl-py | input-kcen | 23.0 ± 0.8 | 21.7 | 26.0 | 20.69 ± 4.55 |
| pting | input-kcen | 23.1 ± 1.0 | 21.8 | 28.8 | 20.75 ± 4.60 |
| pting | input-pting | 23.1 ± 0.7 | 22.2 | 25.9 | 20.80 ± 4.56 |
| mattcl-py | input-pting | 23.2 ± 0.8 | 21.6 | 26.1 | 20.82 ± 4.57 |
| kcen | input-mattcl | 28.5 ± 0.9 | 27.1 | 31.7 | 25.59 ± 5.61 |
| kcen | input-lanjian | 29.3 ± 0.8 | 28.0 | 32.6 | 26.35 ± 5.76 |
| kcen | input-kcen | 29.4 ± 0.8 | 28.2 | 32.4 | 26.42 ± 5.78 |
| kcen | input-pting | 30.0 ± 1.0 | 28.6 | 33.1 | 26.94 ± 5.92 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|