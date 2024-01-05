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
| mattcl | input-pting | 0.010 ± 0.000 | 0.010 | 0.012 | 1.00 |
| mattcl | input-lanjian | 0.010 ± 0.000 | 0.009 | 0.011 | 1.00 ± 0.04 |
| mattcl | input-mattcl | 0.010 ± 0.000 | 0.010 | 0.013 | 1.00 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.010 | 0.013 | 1.01 ± 0.05 |
| mattcl-py | input-pting | 0.295 ± 0.002 | 0.291 | 0.297 | 28.22 ± 0.88 |
| mattcl-py | input-lanjian | 0.298 ± 0.002 | 0.293 | 0.302 | 28.54 ± 0.90 |
| mattcl-py | input-mattcl | 0.299 ± 0.005 | 0.294 | 0.312 | 28.67 ± 1.02 |
| mattcl-py | input-kcen | 0.303 ± 0.002 | 0.300 | 0.305 | 29.02 ± 0.90 |
| pting | input-mattcl | 1.847 ± 0.003 | 1.844 | 1.850 | 176.91 ± 5.41 |
| pting | input-kcen | 1.891 ± 0.038 | 1.865 | 1.934 | 181.14 ± 6.61 |
| pting | input-lanjian | 1.902 ± 0.026 | 1.872 | 1.919 | 182.25 ± 6.11 |
| pting | input-pting | 1.954 ± 0.092 | 1.881 | 2.058 | 187.18 ± 10.53 |
| lanjian | input-pting | 2.373 ± 0.005 | 2.368 | 2.379 | 227.29 ± 6.96 |
| lanjian | input-mattcl | 2.375 ± 0.017 | 2.356 | 2.389 | 227.52 ± 7.15 |
| lanjian | input-lanjian | 2.385 ± 0.012 | 2.372 | 2.397 | 228.50 ± 7.08 |
| lanjian | input-kcen | 2.402 ± 0.015 | 2.393 | 2.419 | 230.08 ± 7.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|