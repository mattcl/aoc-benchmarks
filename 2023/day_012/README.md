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
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.003 | 1.00 ± 0.10 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.003 | 1.01 ± 0.10 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.003 | 1.10 ± 0.18 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.005 | 1.34 ± 0.18 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.003 | 1.34 ± 0.16 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.004 | 1.35 ± 0.17 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.006 | 1.36 ± 0.23 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.071 | 36.55 ± 2.83 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.071 | 37.16 ± 2.84 |
| pting | input-mattcl | 0.069 ± 0.001 | 0.066 | 0.073 | 37.26 ± 2.88 |
| pting | input-pting | 0.070 ± 0.001 | 0.067 | 0.073 | 37.94 ± 2.93 |
| mattcl-py | input-kcen | 0.090 ± 0.001 | 0.087 | 0.093 | 48.76 ± 3.73 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.089 | 0.095 | 49.73 ± 3.82 |
| mattcl-py | input-mattcl | 0.092 ± 0.001 | 0.090 | 0.094 | 49.96 ± 3.81 |
| mattcl-py | input-pting | 0.094 ± 0.001 | 0.092 | 0.098 | 51.36 ± 3.93 |
| kcen | input-kcen | 1.269 ± 0.013 | 1.254 | 1.276 | 689.92 ± 52.35 |
| kcen | input-pting | 1.300 ± 0.013 | 1.288 | 1.314 | 706.74 ± 53.62 |
| kcen | input-mattcl | 1.393 ± 0.008 | 1.385 | 1.400 | 757.21 ± 57.11 |
| kcen | input-lanjian | 1.438 ± 0.027 | 1.413 | 1.467 | 782.20 ± 60.69 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|