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
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.004 | 1.32 ± 0.16 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.004 | 1.32 ± 0.17 |
| mattcl | input-mattcl | 0.003 ± 0.000 | 0.002 | 0.004 | 1.34 ± 0.17 |
| mattcl | input-pting | 0.003 ± 0.000 | 0.002 | 0.004 | 1.34 ± 0.16 |
| pting | input-kcen | 0.068 ± 0.008 | 0.064 | 0.117 | 36.11 ± 5.08 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.066 | 0.070 | 36.27 ± 2.98 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.073 | 36.46 ± 3.01 |
| pting | input-pting | 0.069 ± 0.001 | 0.067 | 0.071 | 37.12 ± 3.02 |
| mattcl-py | input-kcen | 0.087 ± 0.001 | 0.085 | 0.090 | 46.78 ± 3.83 |
| mattcl-py | input-lanjian | 0.090 ± 0.002 | 0.088 | 0.096 | 48.19 ± 3.96 |
| mattcl-py | input-mattcl | 0.091 ± 0.002 | 0.088 | 0.093 | 48.65 ± 3.99 |
| mattcl-py | input-pting | 0.093 ± 0.001 | 0.091 | 0.096 | 49.67 ± 4.05 |
| kcen | input-kcen | 1.290 ± 0.041 | 1.248 | 1.330 | 690.07 ± 59.60 |
| kcen | input-pting | 1.302 ± 0.038 | 1.262 | 1.336 | 696.16 ± 59.44 |
| kcen | input-mattcl | 1.401 ± 0.017 | 1.391 | 1.420 | 749.40 ± 60.88 |
| kcen | input-lanjian | 1.431 ± 0.053 | 1.395 | 1.492 | 765.35 ± 67.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|