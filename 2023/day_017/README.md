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
| mattcl | input-pting | 0.010 ± 0.000 | 0.009 | 0.011 | 1.00 |
| mattcl | input-lanjian | 0.011 ± 0.000 | 0.010 | 0.013 | 1.01 ± 0.05 |
| mattcl | input-mattcl | 0.011 ± 0.000 | 0.010 | 0.013 | 1.01 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.010 | 0.013 | 1.01 ± 0.05 |
| mattcl-py | input-pting | 0.294 ± 0.002 | 0.291 | 0.298 | 28.02 ± 0.90 |
| mattcl-py | input-mattcl | 0.297 ± 0.003 | 0.293 | 0.303 | 28.27 ± 0.91 |
| mattcl-py | input-lanjian | 0.298 ± 0.001 | 0.296 | 0.300 | 28.38 ± 0.89 |
| mattcl-py | input-kcen | 0.301 ± 0.005 | 0.297 | 0.312 | 28.68 ± 0.99 |
| pting | input-mattcl | 1.847 ± 0.011 | 1.834 | 1.856 | 175.89 ± 5.56 |
| pting | input-lanjian | 1.870 ± 0.021 | 1.846 | 1.884 | 178.14 ± 5.88 |
| pting | input-pting | 1.882 ± 0.010 | 1.872 | 1.892 | 179.31 ± 5.64 |
| pting | input-kcen | 1.889 ± 0.005 | 1.885 | 1.895 | 179.98 ± 5.61 |
| lanjian | input-pting | 2.355 ± 0.004 | 2.351 | 2.360 | 224.32 ± 6.97 |
| lanjian | input-mattcl | 2.356 ± 0.003 | 2.353 | 2.359 | 224.43 ± 6.97 |
| lanjian | input-lanjian | 2.381 ± 0.009 | 2.373 | 2.390 | 226.81 ± 7.08 |
| lanjian | input-kcen | 2.391 ± 0.010 | 2.380 | 2.398 | 227.79 ± 7.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|