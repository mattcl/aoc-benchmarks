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
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.10 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.004 | 1.31 ± 0.16 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.004 | 1.32 ± 0.18 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.004 | 1.33 ± 0.15 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.004 | 1.35 ± 0.18 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.070 | 36.48 ± 2.99 |
| pting | input-lanjian | 0.067 ± 0.001 | 0.066 | 0.069 | 36.84 ± 3.00 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.066 | 0.072 | 37.04 ± 3.05 |
| pting | input-pting | 0.069 ± 0.001 | 0.067 | 0.071 | 37.60 ± 3.06 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.087 | 0.094 | 48.64 ± 3.98 |
| mattcl-py | input-lanjian | 0.090 ± 0.001 | 0.089 | 0.093 | 49.38 ± 4.02 |
| mattcl-py | input-mattcl | 0.091 ± 0.001 | 0.089 | 0.094 | 49.75 ± 4.06 |
| mattcl-py | input-pting | 0.094 ± 0.001 | 0.092 | 0.096 | 51.29 ± 4.17 |
| kcen | input-pting | 1.287 ± 0.004 | 1.282 | 1.290 | 703.73 ± 56.64 |
| kcen | input-kcen | 1.296 ± 0.016 | 1.286 | 1.315 | 708.97 ± 57.72 |
| kcen | input-mattcl | 1.414 ± 0.026 | 1.391 | 1.443 | 773.24 ± 63.85 |
| kcen | input-lanjian | 1.470 ± 0.028 | 1.449 | 1.502 | 804.01 ± 66.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|