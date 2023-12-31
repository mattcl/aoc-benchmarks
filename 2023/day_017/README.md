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
| mattcl | input-mattcl | 0.024 ± 0.001 | 0.023 | 0.026 | 1.01 ± 0.04 |
| mattcl | input-lanjian | 0.024 ± 0.003 | 0.023 | 0.059 | 1.01 ± 0.14 |
| mattcl | input-kcen | 0.024 ± 0.001 | 0.023 | 0.027 | 1.02 ± 0.04 |
| mattcl-py | input-pting | 0.383 ± 0.002 | 0.380 | 0.387 | 16.08 ± 0.48 |
| mattcl-py | input-mattcl | 0.385 ± 0.003 | 0.381 | 0.391 | 16.15 ± 0.49 |
| mattcl-py | input-kcen | 0.386 ± 0.005 | 0.380 | 0.392 | 16.18 ± 0.51 |
| mattcl-py | input-lanjian | 0.388 ± 0.003 | 0.383 | 0.392 | 16.27 ± 0.49 |
| pting | input-kcen | 1.874 ± 0.025 | 1.856 | 1.903 | 78.61 ± 2.51 |
| pting | input-mattcl | 1.877 ± 0.021 | 1.859 | 1.900 | 78.73 ± 2.44 |
| pting | input-lanjian | 1.890 ± 0.010 | 1.878 | 1.896 | 79.27 ± 2.34 |
| pting | input-pting | 1.960 ± 0.020 | 1.937 | 1.975 | 82.21 ± 2.53 |
| lanjian | input-mattcl | 2.397 ± 0.006 | 2.391 | 2.404 | 100.55 ± 2.93 |
| lanjian | input-pting | 2.413 ± 0.019 | 2.400 | 2.435 | 101.19 ± 3.05 |
| lanjian | input-lanjian | 2.418 ± 0.003 | 2.415 | 2.421 | 101.43 ± 2.94 |
| lanjian | input-kcen | 2.424 ± 0.002 | 2.422 | 2.425 | 101.66 ± 2.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|