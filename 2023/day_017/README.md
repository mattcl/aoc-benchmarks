# Day 17 benchmarks

[link to problem](https://adventofcode.com/2023/day/17)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 17)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [s] | Min [s] | Max [s] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 0.024 ± 0.001 | 0.023 | 0.027 | 1.00 |
| mattcl | input-mattcl | 0.024 ± 0.001 | 0.023 | 0.027 | 1.01 ± 0.04 |
| mattcl | input-lanjian | 0.024 ± 0.001 | 0.023 | 0.026 | 1.01 ± 0.04 |
| mattcl-py | input-pting | 0.376 ± 0.004 | 0.371 | 0.382 | 15.91 ± 0.48 |
| mattcl-py | input-lanjian | 0.383 ± 0.004 | 0.378 | 0.388 | 16.19 ± 0.48 |
| mattcl-py | input-mattcl | 0.383 ± 0.003 | 0.378 | 0.388 | 16.21 ± 0.48 |
| pting | input-mattcl | 1.864 ± 0.006 | 1.858 | 1.869 | 78.85 ± 2.23 |
| pting | input-pting | 1.891 ± 0.015 | 1.874 | 1.905 | 80.00 ± 2.34 |
| pting | input-lanjian | 1.902 ± 0.022 | 1.878 | 1.923 | 80.46 ± 2.45 |
| lanjian | input-mattcl | 2.372 ± 0.027 | 2.342 | 2.391 | 100.36 ± 3.04 |
| lanjian | input-pting | 2.386 ± 0.004 | 2.381 | 2.389 | 100.94 ± 2.84 |
| lanjian | input-lanjian | 2.399 ± 0.005 | 2.395 | 2.404 | 101.51 ± 2.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|