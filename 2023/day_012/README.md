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
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.13 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.004 | 1.32 ± 0.17 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.004 | 1.33 ± 0.17 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.006 | 1.35 ± 0.23 |
| mattcl | input-mattcl | 0.003 ± 0.001 | 0.002 | 0.007 | 1.54 ± 0.44 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.071 | 36.26 ± 3.25 |
| pting | input-mattcl | 0.068 ± 0.001 | 0.066 | 0.071 | 36.78 ± 3.28 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.072 | 36.82 ± 3.33 |
| pting | input-pting | 0.069 ± 0.001 | 0.067 | 0.071 | 37.40 ± 3.33 |
| mattcl-py | input-kcen | 0.089 ± 0.001 | 0.087 | 0.091 | 48.39 ± 4.29 |
| mattcl-py | input-lanjian | 0.091 ± 0.002 | 0.089 | 0.096 | 49.50 ± 4.45 |
| mattcl-py | input-mattcl | 0.092 ± 0.001 | 0.089 | 0.095 | 49.70 ± 4.45 |
| mattcl-py | input-pting | 0.093 ± 0.001 | 0.091 | 0.096 | 50.55 ± 4.50 |
| kcen | input-pting | 1.300 ± 0.028 | 1.268 | 1.317 | 706.12 ± 64.03 |
| kcen | input-kcen | 1.306 ± 0.023 | 1.287 | 1.331 | 709.06 ± 63.70 |
| kcen | input-mattcl | 1.418 ± 0.004 | 1.415 | 1.421 | 770.02 ± 67.91 |
| kcen | input-lanjian | 1.484 ± 0.013 | 1.471 | 1.497 | 805.93 ± 71.41 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|