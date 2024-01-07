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
| mattcl | input-lanjian | 0.010 ± 0.000 | 0.010 | 0.012 | 1.00 ± 0.05 |
| mattcl | input-mattcl | 0.011 ± 0.000 | 0.010 | 0.013 | 1.01 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.004 | 0.009 | 0.054 | 1.04 ± 0.37 |
| mattcl-py | input-pting | 0.295 ± 0.004 | 0.291 | 0.304 | 28.22 ± 1.02 |
| mattcl-py | input-mattcl | 0.296 ± 0.002 | 0.293 | 0.299 | 28.33 ± 0.98 |
| mattcl-py | input-lanjian | 0.300 ± 0.003 | 0.296 | 0.307 | 28.74 ± 1.02 |
| mattcl-py | input-kcen | 0.302 ± 0.005 | 0.298 | 0.314 | 28.92 ± 1.09 |
| pting | input-pting | 1.889 ± 0.006 | 1.885 | 1.895 | 180.66 ± 6.13 |
| pting | input-mattcl | 1.948 ± 0.121 | 1.875 | 2.088 | 186.33 ± 13.22 |
| pting | input-kcen | 1.954 ± 0.071 | 1.913 | 2.036 | 186.95 ± 9.28 |
| pting | input-lanjian | 2.021 ± 0.257 | 1.858 | 2.317 | 193.35 ± 25.40 |
| lanjian | input-mattcl | 2.338 ± 0.016 | 2.320 | 2.350 | 223.69 ± 7.72 |
| lanjian | input-pting | 2.358 ± 0.003 | 2.356 | 2.362 | 225.60 ± 7.63 |
| lanjian | input-lanjian | 2.377 ± 0.007 | 2.372 | 2.385 | 227.37 ± 7.71 |
| lanjian | input-kcen | 2.454 ± 0.111 | 2.382 | 2.582 | 234.73 ± 13.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|