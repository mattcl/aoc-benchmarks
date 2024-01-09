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
| mattcl | input-pting | 0.010 ± 0.000 | 0.010 | 0.013 | 1.00 |
| mattcl | input-mattcl | 0.010 ± 0.000 | 0.010 | 0.012 | 1.01 ± 0.05 |
| mattcl | input-lanjian | 0.010 ± 0.000 | 0.010 | 0.013 | 1.01 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.010 | 0.012 | 1.02 ± 0.05 |
| mattcl-py | input-pting | 0.294 ± 0.003 | 0.290 | 0.301 | 28.41 ± 1.02 |
| mattcl-py | input-mattcl | 0.302 ± 0.019 | 0.292 | 0.356 | 29.18 ± 2.11 |
| mattcl-py | input-lanjian | 0.302 ± 0.004 | 0.297 | 0.310 | 29.19 ± 1.10 |
| mattcl-py | input-kcen | 0.304 ± 0.004 | 0.300 | 0.313 | 29.32 ± 1.08 |
| pting | input-mattcl | 1.881 ± 0.016 | 1.862 | 1.891 | 181.66 ± 6.52 |
| pting | input-kcen | 1.883 ± 0.016 | 1.868 | 1.901 | 181.91 ± 6.52 |
| pting | input-lanjian | 1.885 ± 0.038 | 1.851 | 1.926 | 182.09 ± 7.32 |
| pting | input-pting | 1.913 ± 0.019 | 1.901 | 1.935 | 184.77 ± 6.69 |
| lanjian | input-pting | 2.350 ± 0.016 | 2.332 | 2.362 | 226.94 ± 8.04 |
| lanjian | input-mattcl | 2.351 ± 0.012 | 2.341 | 2.364 | 227.05 ± 7.99 |
| lanjian | input-lanjian | 2.383 ± 0.008 | 2.377 | 2.392 | 230.13 ± 8.05 |
| lanjian | input-kcen | 2.390 ± 0.004 | 2.386 | 2.394 | 230.82 ± 8.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|