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
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.01 ± 0.10 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.004 | 1.33 ± 0.16 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.005 | 1.33 ± 0.17 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.005 | 1.33 ± 0.18 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.003 | 1.34 ± 0.16 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.071 | 36.02 ± 2.93 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.066 | 0.071 | 36.74 ± 2.98 |
| pting | input-lanjian | 0.069 ± 0.002 | 0.066 | 0.074 | 36.86 ± 3.08 |
| pting | input-pting | 0.070 ± 0.001 | 0.068 | 0.072 | 37.49 ± 3.03 |
| mattcl-py | input-kcen | 0.090 ± 0.001 | 0.087 | 0.092 | 48.16 ± 3.89 |
| mattcl-py | input-lanjian | 0.092 ± 0.001 | 0.088 | 0.095 | 49.21 ± 3.97 |
| mattcl-py | input-mattcl | 0.092 ± 0.002 | 0.089 | 0.096 | 49.44 ± 4.04 |
| mattcl-py | input-pting | 0.095 ± 0.001 | 0.093 | 0.098 | 50.92 ± 4.11 |
| kcen | input-kcen | 1.284 ± 0.003 | 1.282 | 1.288 | 690.11 ± 54.98 |
| kcen | input-pting | 1.316 ± 0.021 | 1.298 | 1.340 | 707.15 ± 57.49 |
| kcen | input-mattcl | 1.425 ± 0.023 | 1.399 | 1.441 | 765.73 ± 62.17 |
| kcen | input-lanjian | 1.458 ± 0.017 | 1.443 | 1.476 | 783.48 ± 63.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|