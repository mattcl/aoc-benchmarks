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
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.003 | 1.32 ± 0.16 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.005 | 1.33 ± 0.19 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.004 | 1.35 ± 0.17 |
| mattcl | input-mattcl | 0.003 ± 0.000 | 0.002 | 0.005 | 1.35 ± 0.20 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.069 | 36.02 ± 3.00 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.070 | 36.54 ± 3.04 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.067 | 0.071 | 36.71 ± 3.06 |
| pting | input-pting | 0.069 ± 0.001 | 0.067 | 0.072 | 37.28 ± 3.10 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.086 | 0.091 | 47.87 ± 3.98 |
| mattcl-py | input-mattcl | 0.092 ± 0.001 | 0.090 | 0.095 | 49.39 ± 4.11 |
| mattcl-py | input-lanjian | 0.093 ± 0.006 | 0.089 | 0.123 | 49.90 ± 5.28 |
| mattcl-py | input-pting | 0.094 ± 0.001 | 0.092 | 0.097 | 50.52 ± 4.20 |
| kcen | input-kcen | 1.255 ± 0.028 | 1.224 | 1.279 | 674.94 ± 57.36 |
| kcen | input-pting | 1.304 ± 0.034 | 1.265 | 1.327 | 701.45 ± 60.35 |
| kcen | input-mattcl | 1.405 ± 0.018 | 1.384 | 1.417 | 755.68 ± 62.73 |
| kcen | input-lanjian | 1.446 ± 0.007 | 1.440 | 1.454 | 777.62 ± 63.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|