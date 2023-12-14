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
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.003 | 1.32 ± 0.16 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.003 | 1.32 ± 0.15 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.004 | 1.34 ± 0.17 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.005 | 1.35 ± 0.22 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.072 | 36.88 ± 3.31 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.066 | 0.070 | 37.34 ± 3.33 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.071 | 37.35 ± 3.33 |
| pting | input-pting | 0.069 ± 0.001 | 0.067 | 0.071 | 38.15 ± 3.39 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.087 | 0.091 | 49.03 ± 4.35 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.088 | 0.093 | 50.12 ± 4.46 |
| mattcl-py | input-mattcl | 0.091 ± 0.001 | 0.089 | 0.094 | 50.44 ± 4.48 |
| mattcl-py | input-pting | 0.094 ± 0.001 | 0.092 | 0.096 | 51.76 ± 4.59 |
| kcen | input-kcen | 1.285 ± 0.003 | 1.281 | 1.288 | 710.18 ± 62.36 |
| kcen | input-pting | 1.304 ± 0.012 | 1.292 | 1.315 | 720.97 ± 63.62 |
| kcen | input-mattcl | 1.420 ± 0.015 | 1.404 | 1.434 | 784.75 ± 69.37 |
| kcen | input-lanjian | 1.475 ± 0.005 | 1.469 | 1.479 | 815.11 ± 71.60 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|