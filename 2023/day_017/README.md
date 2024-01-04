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
| mattcl | input-mattcl | 0.010 ± 0.000 | 0.009 | 0.011 | 1.00 ± 0.04 |
| mattcl | input-lanjian | 0.010 ± 0.000 | 0.009 | 0.013 | 1.01 ± 0.05 |
| mattcl | input-kcen | 0.010 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.05 |
| mattcl-py | input-pting | 0.293 ± 0.003 | 0.290 | 0.300 | 28.44 ± 0.85 |
| mattcl-py | input-mattcl | 0.297 ± 0.004 | 0.292 | 0.303 | 28.79 ± 0.88 |
| mattcl-py | input-lanjian | 0.297 ± 0.002 | 0.294 | 0.302 | 28.86 ± 0.85 |
| mattcl-py | input-kcen | 0.302 ± 0.002 | 0.300 | 0.305 | 29.31 ± 0.85 |
| pting | input-mattcl | 1.841 ± 0.030 | 1.812 | 1.873 | 178.66 ± 5.86 |
| pting | input-kcen | 1.871 ± 0.023 | 1.846 | 1.893 | 181.56 ± 5.61 |
| pting | input-pting | 1.874 ± 0.018 | 1.860 | 1.894 | 181.92 ± 5.42 |
| pting | input-lanjian | 1.903 ± 0.026 | 1.884 | 1.933 | 184.69 ± 5.81 |
| lanjian | input-mattcl | 2.353 ± 0.016 | 2.335 | 2.363 | 228.38 ± 6.64 |
| lanjian | input-pting | 2.357 ± 0.009 | 2.347 | 2.365 | 228.77 ± 6.53 |
| lanjian | input-lanjian | 2.386 ± 0.003 | 2.383 | 2.390 | 231.60 ± 6.56 |
| lanjian | input-kcen | 2.389 ± 0.006 | 2.382 | 2.393 | 231.87 ± 6.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|