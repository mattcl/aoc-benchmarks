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
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.003 | 1.00 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.003 | 1.07 ± 0.15 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.004 | 1.33 ± 0.18 |
| lanjian | input-lanjian | 0.003 ± 0.001 | 0.002 | 0.009 | 1.36 ± 0.29 |
| mattcl | input-lanjian | 0.004 ± 0.001 | 0.003 | 0.008 | 2.00 ± 0.60 |
| lanjian | input-kcen | 0.005 ± 0.001 | 0.003 | 0.008 | 2.45 ± 0.56 |
| mattcl | input-mattcl | 0.005 ± 0.009 | 0.002 | 0.058 | 2.47 ± 4.40 |
| mattcl | input-kcen | 0.009 ± 0.002 | 0.004 | 0.017 | 4.16 ± 1.10 |
| pting | input-lanjian | 0.071 ± 0.001 | 0.069 | 0.077 | 34.72 ± 3.18 |
| pting | input-mattcl | 0.071 ± 0.002 | 0.068 | 0.076 | 34.82 ± 3.23 |
| pting | input-pting | 0.078 ± 0.026 | 0.070 | 0.208 | 38.07 ± 13.03 |
| mattcl-py | input-mattcl | 0.097 ± 0.002 | 0.094 | 0.103 | 47.24 ± 4.33 |
| mattcl-py | input-pting | 0.098 ± 0.002 | 0.096 | 0.104 | 47.89 ± 4.40 |
| pting | input-kcen | 0.101 ± 0.007 | 0.091 | 0.117 | 49.04 ± 5.65 |
| mattcl-py | input-lanjian | 0.122 ± 0.031 | 0.103 | 0.208 | 59.43 ± 16.11 |
| mattcl-py | input-kcen | 0.125 ± 0.004 | 0.118 | 0.133 | 61.14 ± 5.75 |
| kcen | input-pting | 1.322 ± 0.022 | 1.305 | 1.347 | 644.31 ± 58.45 |
| kcen | input-mattcl | 1.498 ± 0.059 | 1.445 | 1.561 | 730.40 ± 71.13 |
| kcen | input-lanjian | 1.911 ± 0.053 | 1.856 | 1.963 | 931.43 ± 87.04 |
| kcen | input-kcen | 2.755 ± 0.097 | 2.644 | 2.825 | 1342.84 ± 128.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|