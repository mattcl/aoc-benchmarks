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
| mattcl | input-lanjian | 0.024 ± 0.001 | 0.023 | 0.027 | 1.01 ± 0.04 |
| mattcl | input-kcen | 0.024 ± 0.000 | 0.023 | 0.026 | 1.02 ± 0.03 |
| mattcl | input-mattcl | 0.025 ± 0.003 | 0.023 | 0.044 | 1.02 ± 0.11 |
| mattcl-py | input-pting | 0.380 ± 0.003 | 0.376 | 0.383 | 15.86 ± 0.40 |
| mattcl-py | input-mattcl | 0.386 ± 0.002 | 0.382 | 0.388 | 16.07 ± 0.40 |
| mattcl-py | input-lanjian | 0.386 ± 0.004 | 0.378 | 0.392 | 16.09 ± 0.43 |
| mattcl-py | input-kcen | 0.387 ± 0.004 | 0.381 | 0.394 | 16.14 ± 0.43 |
| pting | input-lanjian | 1.874 ± 0.003 | 1.871 | 1.877 | 78.13 ± 1.90 |
| pting | input-kcen | 1.882 ± 0.018 | 1.864 | 1.901 | 78.46 ± 2.05 |
| pting | input-mattcl | 1.883 ± 0.019 | 1.866 | 1.904 | 78.53 ± 2.07 |
| pting | input-pting | 1.921 ± 0.025 | 1.902 | 1.950 | 80.09 ± 2.21 |
| lanjian | input-pting | 2.389 ± 0.032 | 2.354 | 2.415 | 99.62 ± 2.76 |
| lanjian | input-lanjian | 2.396 ± 0.030 | 2.362 | 2.417 | 99.88 ± 2.72 |
| lanjian | input-mattcl | 2.401 ± 0.010 | 2.390 | 2.411 | 100.09 ± 2.47 |
| lanjian | input-kcen | 2.423 ± 0.006 | 2.419 | 2.430 | 101.00 ± 2.47 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|