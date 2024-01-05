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
| mattcl | input-pting | 0.010 ± 0.000 | 0.010 | 0.011 | 1.00 |
| mattcl | input-mattcl | 0.010 ± 0.000 | 0.010 | 0.011 | 1.00 ± 0.04 |
| mattcl | input-lanjian | 0.010 ± 0.000 | 0.009 | 0.011 | 1.01 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.05 |
| mattcl-py | input-pting | 0.294 ± 0.002 | 0.291 | 0.298 | 28.34 ± 0.86 |
| mattcl-py | input-mattcl | 0.297 ± 0.002 | 0.293 | 0.300 | 28.68 ± 0.87 |
| mattcl-py | input-lanjian | 0.298 ± 0.003 | 0.293 | 0.302 | 28.76 ± 0.87 |
| mattcl-py | input-kcen | 0.300 ± 0.002 | 0.297 | 0.303 | 28.99 ± 0.86 |
| pting | input-mattcl | 1.858 ± 0.035 | 1.829 | 1.897 | 179.33 ± 6.21 |
| pting | input-lanjian | 1.868 ± 0.025 | 1.839 | 1.883 | 180.28 ± 5.76 |
| pting | input-kcen | 1.871 ± 0.012 | 1.858 | 1.878 | 180.60 ± 5.37 |
| pting | input-pting | 1.906 ± 0.023 | 1.889 | 1.932 | 183.99 ± 5.78 |
| lanjian | input-mattcl | 2.354 ± 0.017 | 2.337 | 2.371 | 227.24 ± 6.80 |
| lanjian | input-pting | 2.361 ± 0.007 | 2.356 | 2.369 | 227.87 ± 6.66 |
| lanjian | input-kcen | 2.378 ± 0.004 | 2.374 | 2.381 | 229.49 ± 6.68 |
| lanjian | input-lanjian | 2.384 ± 0.010 | 2.376 | 2.394 | 230.07 ± 6.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|