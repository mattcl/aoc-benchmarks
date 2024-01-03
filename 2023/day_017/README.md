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
| mattcl | input-pting | 0.023 ± 0.001 | 0.022 | 0.025 | 1.00 |
| mattcl | input-mattcl | 0.023 ± 0.000 | 0.022 | 0.026 | 1.01 ± 0.03 |
| mattcl | input-lanjian | 0.024 ± 0.001 | 0.022 | 0.026 | 1.01 ± 0.04 |
| mattcl | input-kcen | 0.024 ± 0.001 | 0.023 | 0.027 | 1.02 ± 0.04 |
| mattcl-py | input-pting | 0.374 ± 0.003 | 0.369 | 0.380 | 16.06 ± 0.42 |
| mattcl-py | input-mattcl | 0.380 ± 0.002 | 0.376 | 0.383 | 16.32 ± 0.41 |
| mattcl-py | input-lanjian | 0.384 ± 0.003 | 0.380 | 0.389 | 16.48 ± 0.42 |
| mattcl-py | input-kcen | 0.388 ± 0.005 | 0.381 | 0.392 | 16.67 ± 0.45 |
| pting | input-mattcl | 1.840 ± 0.023 | 1.821 | 1.865 | 78.96 ± 2.15 |
| pting | input-lanjian | 1.858 ± 0.030 | 1.824 | 1.880 | 79.76 ± 2.33 |
| pting | input-pting | 1.887 ± 0.050 | 1.836 | 1.937 | 81.01 ± 2.92 |
| pting | input-kcen | 1.912 ± 0.096 | 1.850 | 2.022 | 82.07 ± 4.57 |
| lanjian | input-pting | 2.357 ± 0.012 | 2.348 | 2.371 | 101.16 ± 2.52 |
| lanjian | input-mattcl | 2.380 ± 0.005 | 2.376 | 2.385 | 102.17 ± 2.49 |
| lanjian | input-lanjian | 2.392 ± 0.028 | 2.366 | 2.422 | 102.68 ± 2.77 |
| lanjian | input-kcen | 2.433 ± 0.057 | 2.394 | 2.499 | 104.45 ± 3.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|