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
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.1 ± 0.3 | 0.8 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.31 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.8 | 1.8 | 1.03 ± 0.33 |
| mattcl-ts | input-mattcl | 14.1 ± 0.3 | 13.4 | 15.0 | 12.72 ± 2.93 |
| mattcl-ts | input-kcen | 14.3 ± 0.4 | 13.4 | 15.5 | 12.91 ± 2.97 |
| mattcl-ts | input-pting | 14.7 ± 1.9 | 13.6 | 40.4 | 13.26 ± 3.49 |
| pting | input-mattcl | 22.0 ± 0.7 | 20.7 | 24.7 | 19.81 ± 4.58 |
| mattcl-py | input-mattcl | 22.1 ± 1.2 | 20.9 | 32.8 | 19.85 ± 4.68 |
| pting | input-kcen | 22.4 ± 0.7 | 21.4 | 25.4 | 20.18 ± 4.67 |
| mattcl-py | input-kcen | 22.5 ± 0.8 | 21.4 | 25.8 | 20.26 ± 4.69 |
| mattcl-py | input-pting | 22.6 ± 0.7 | 21.6 | 25.5 | 20.37 ± 4.71 |
| pting | input-pting | 22.9 ± 0.9 | 21.8 | 26.6 | 20.56 ± 4.78 |
| kcen | input-mattcl | 31.7 ± 0.9 | 30.7 | 35.2 | 28.56 ± 6.59 |
| kcen | input-kcen | 33.1 ± 1.0 | 32.0 | 36.4 | 29.83 ± 6.90 |
| kcen | input-pting | 33.5 ± 0.9 | 32.1 | 36.3 | 30.10 ± 6.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|