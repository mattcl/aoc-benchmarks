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
| mattcl | input-pting | 0.024 ± 0.001 | 0.022 | 0.026 | 1.00 |
| mattcl | input-mattcl | 0.024 ± 0.001 | 0.023 | 0.027 | 1.01 ± 0.04 |
| mattcl | input-kcen | 0.024 ± 0.001 | 0.023 | 0.027 | 1.02 ± 0.04 |
| mattcl | input-lanjian | 0.024 ± 0.004 | 0.022 | 0.064 | 1.02 ± 0.16 |
| mattcl-py | input-pting | 0.382 ± 0.005 | 0.374 | 0.389 | 16.12 ± 0.46 |
| mattcl-py | input-mattcl | 0.383 ± 0.005 | 0.376 | 0.391 | 16.15 ± 0.45 |
| mattcl-py | input-lanjian | 0.386 ± 0.003 | 0.382 | 0.391 | 16.27 ± 0.42 |
| mattcl-py | input-kcen | 0.390 ± 0.004 | 0.385 | 0.397 | 16.45 ± 0.44 |
| pting | input-kcen | 1.902 ± 0.023 | 1.878 | 1.924 | 80.16 ± 2.21 |
| pting | input-lanjian | 1.913 ± 0.025 | 1.883 | 1.928 | 80.64 ± 2.27 |
| pting | input-mattcl | 1.915 ± 0.010 | 1.904 | 1.922 | 80.74 ± 2.05 |
| pting | input-pting | 1.928 ± 0.031 | 1.902 | 1.963 | 81.30 ± 2.40 |
| lanjian | input-mattcl | 2.366 ± 0.024 | 2.351 | 2.394 | 99.73 ± 2.68 |
| lanjian | input-lanjian | 2.392 ± 0.032 | 2.369 | 2.429 | 100.84 ± 2.85 |
| lanjian | input-pting | 2.392 ± 0.031 | 2.357 | 2.416 | 100.86 ± 2.83 |
| lanjian | input-kcen | 2.428 ± 0.010 | 2.421 | 2.440 | 102.34 ± 2.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|