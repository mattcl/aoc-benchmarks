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
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.003 | 1.00 ± 0.11 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.003 | 1.00 ± 0.13 |
| mattcl | input-kcen | 0.003 ± 0.000 | 0.002 | 0.004 | 1.30 ± 0.15 |
| mattcl | input-lanjian | 0.003 ± 0.000 | 0.002 | 0.004 | 1.30 ± 0.15 |
| mattcl | input-mattcl | 0.003 ± 0.000 | 0.002 | 0.004 | 1.32 ± 0.16 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.003 | 1.32 ± 0.15 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.069 | 33.95 ± 2.83 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.072 | 34.48 ± 2.90 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.066 | 0.072 | 34.54 ± 2.90 |
| pting | input-pting | 0.070 ± 0.001 | 0.068 | 0.073 | 35.30 ± 2.94 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.088 | 0.091 | 45.10 ± 3.73 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.088 | 0.095 | 46.09 ± 3.86 |
| mattcl-py | input-mattcl | 0.092 ± 0.001 | 0.090 | 0.095 | 46.27 ± 3.85 |
| mattcl-py | input-pting | 0.096 ± 0.005 | 0.092 | 0.121 | 48.24 ± 4.66 |
| kcen | input-kcen | 1.270 ± 0.013 | 1.256 | 1.280 | 641.57 ± 53.03 |
| kcen | input-pting | 1.287 ± 0.020 | 1.276 | 1.310 | 650.22 ± 54.26 |
| kcen | input-mattcl | 1.400 ± 0.013 | 1.386 | 1.409 | 707.26 ± 58.37 |
| kcen | input-lanjian | 1.457 ± 0.012 | 1.445 | 1.470 | 736.00 ± 60.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|