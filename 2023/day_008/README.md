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
| mattcl | input-mattcl | 1.1 ± 0.3 | 0.7 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.9 | 1.04 ± 0.33 |
| mattcl | input-pting | 1.2 ± 0.3 | 0.8 | 2.0 | 1.05 ± 0.34 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.8 | 1.8 | 1.05 ± 0.33 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 2.0 | 1.07 ± 0.34 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.9 | 1.09 ± 0.34 |
| lanjian | input-pting | 1.2 ± 0.3 | 0.9 | 2.1 | 1.10 ± 0.34 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.9 | 2.2 | 1.11 ± 0.34 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.2 | 16.4 | 13.33 ± 3.03 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.2 | 16.1 | 13.37 ± 3.03 |
| mattcl-ts | input-lanjian | 15.1 ± 0.3 | 14.3 | 16.4 | 13.38 ± 3.03 |
| mattcl-ts | input-pting | 15.2 ± 0.4 | 14.5 | 16.6 | 13.46 ± 3.06 |
| mattcl-py | input-mattcl | 22.4 ± 0.8 | 21.5 | 26.2 | 19.78 ± 4.52 |
| pting | input-mattcl | 22.5 ± 0.9 | 21.3 | 25.6 | 19.86 ± 4.55 |
| pting | input-lanjian | 22.7 ± 0.7 | 21.4 | 25.8 | 20.08 ± 4.57 |
| mattcl-py | input-kcen | 22.8 ± 0.8 | 21.4 | 26.1 | 20.16 ± 4.60 |
| mattcl-py | input-lanjian | 22.8 ± 0.8 | 21.8 | 26.4 | 20.16 ± 4.60 |
| pting | input-kcen | 22.8 ± 0.8 | 21.8 | 26.2 | 20.16 ± 4.61 |
| pting | input-pting | 23.0 ± 0.7 | 22.0 | 26.0 | 20.37 ± 4.64 |
| mattcl-py | input-pting | 23.1 ± 0.8 | 22.0 | 26.6 | 20.44 ± 4.67 |
| kcen | input-mattcl | 28.2 ± 0.8 | 26.8 | 30.6 | 24.93 ± 5.67 |
| kcen | input-lanjian | 29.1 ± 0.8 | 27.7 | 31.5 | 25.78 ± 5.86 |
| kcen | input-kcen | 29.3 ± 0.8 | 27.8 | 32.0 | 25.93 ± 5.90 |
| kcen | input-pting | 29.6 ± 0.8 | 28.3 | 32.4 | 26.17 ± 5.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>21883</pre>|<pre>12833235391111</pre>|
|input-lanjian|<pre>16897</pre>|<pre>16563603485021</pre>|
|input-mattcl|<pre>12361</pre>|<pre>18215611419223</pre>|
|input-pting|<pre>19951</pre>|<pre>16342438708751</pre>|