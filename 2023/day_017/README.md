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
| mattcl | input-kcen | 0.025 ± 0.001 | 0.024 | 0.027 | 1.00 |
| mattcl | input-mattcl | 0.027 ± 0.006 | 0.024 | 0.055 | 1.08 ± 0.23 |
| mattcl | input-lanjian | 0.029 ± 0.006 | 0.023 | 0.052 | 1.17 ± 0.25 |
| mattcl | input-pting | 0.041 ± 0.008 | 0.034 | 0.074 | 1.67 ± 0.32 |
| mattcl-py | input-kcen | 0.395 ± 0.003 | 0.392 | 0.400 | 16.02 ± 0.34 |
| mattcl-py | input-mattcl | 0.403 ± 0.015 | 0.393 | 0.436 | 16.35 ± 0.69 |
| mattcl-py | input-lanjian | 0.557 ± 0.005 | 0.550 | 0.563 | 22.59 ± 0.50 |
| mattcl-py | input-pting | 0.764 ± 0.001 | 0.763 | 0.765 | 30.99 ± 0.63 |
| pting | input-kcen | 1.919 ± 0.038 | 1.875 | 1.943 | 77.83 ± 2.21 |
| pting | input-mattcl | 2.006 ± 0.169 | 1.897 | 2.201 | 81.36 ± 7.07 |
| lanjian | input-lanjian | 2.443 ± 0.014 | 2.428 | 2.453 | 99.09 ± 2.09 |
| lanjian | input-mattcl | 2.490 ± 0.010 | 2.479 | 2.497 | 100.98 ± 2.09 |
| pting | input-lanjian | 2.507 ± 0.123 | 2.434 | 2.649 | 101.70 ± 5.39 |
| lanjian | input-kcen | 2.583 ± 0.114 | 2.489 | 2.710 | 104.75 ± 5.10 |
| pting | input-pting | 3.162 ± 0.329 | 2.927 | 3.537 | 128.25 ± 13.58 |
| lanjian | input-pting | 4.263 ± 0.124 | 4.132 | 4.378 | 172.92 ± 6.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|