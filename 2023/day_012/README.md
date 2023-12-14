# Day 12 benchmarks

[link to problem](https://adventofcode.com/2023/day/12)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 12)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [s] | Min [s] | Max [s] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.09 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.003 | 1.33 ± 0.16 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.004 | 1.34 ± 0.16 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.006 | 1.35 ± 0.22 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.004 | 1.36 ± 0.17 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.072 | 37.71 ± 2.99 |
| pting | input-kcen | 0.068 ± 0.007 | 0.065 | 0.113 | 37.80 ± 4.88 |
| pting | input-mattcl | 0.069 ± 0.001 | 0.066 | 0.072 | 38.23 ± 3.03 |
| pting | input-pting | 0.069 ± 0.001 | 0.067 | 0.072 | 38.58 ± 3.05 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.088 | 0.092 | 49.58 ± 3.88 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.089 | 0.094 | 50.64 ± 3.96 |
| mattcl-py | input-mattcl | 0.092 ± 0.001 | 0.089 | 0.094 | 50.82 ± 3.98 |
| mattcl-py | input-pting | 0.094 ± 0.001 | 0.092 | 0.098 | 52.38 ± 4.10 |
| kcen | input-kcen | 1.263 ± 0.011 | 1.251 | 1.274 | 701.31 ± 54.55 |
| kcen | input-pting | 1.287 ± 0.020 | 1.266 | 1.305 | 714.70 ± 56.34 |
| kcen | input-mattcl | 1.411 ± 0.018 | 1.391 | 1.427 | 783.34 ± 61.38 |
| kcen | input-lanjian | 1.464 ± 0.032 | 1.430 | 1.493 | 812.64 ± 65.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|