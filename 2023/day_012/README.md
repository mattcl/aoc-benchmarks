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

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 1.3 ± 0.2 | 1.1 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 1.7 | 1.05 ± 0.17 |
| mattcl | input-pting | 1.4 ± 0.2 | 1.1 | 1.8 | 1.08 ± 0.18 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.2 | 1.8 | 1.11 ± 0.18 |
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.4 | 1.37 ± 0.19 |
| lanjian | input-lanjian | 1.8 ± 0.2 | 1.7 | 3.2 | 1.38 ± 0.21 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.6 | 1.56 ± 0.26 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.6 | 1.63 ± 0.26 |
| pting | input-kcen | 67.4 ± 0.9 | 65.4 | 69.4 | 51.15 ± 6.40 |
| pting | input-lanjian | 68.6 ± 1.1 | 66.4 | 72.3 | 52.02 ± 6.53 |
| pting | input-mattcl | 69.0 ± 1.2 | 66.1 | 71.4 | 52.32 ± 6.57 |
| pting | input-pting | 70.4 ± 1.0 | 68.2 | 73.5 | 53.36 ± 6.69 |
| mattcl-py | input-kcen | 90.8 ± 1.1 | 89.0 | 93.4 | 68.83 ± 8.61 |
| mattcl-py | input-lanjian | 93.1 ± 1.5 | 91.1 | 97.1 | 70.64 ± 8.86 |
| mattcl-py | input-mattcl | 93.6 ± 1.4 | 90.9 | 96.6 | 71.00 ± 8.90 |
| mattcl-py | input-pting | 96.0 ± 1.4 | 92.9 | 100.0 | 72.79 ± 9.13 |
| kcen | input-kcen | 233.0 ± 3.7 | 228.3 | 240.6 | 176.73 ± 22.18 |
| kcen | input-pting | 236.8 ± 5.2 | 229.8 | 246.7 | 179.61 ± 22.70 |
| kcen | input-mattcl | 257.6 ± 8.6 | 245.9 | 273.2 | 195.39 ± 25.18 |
| kcen | input-lanjian | 269.8 ± 4.4 | 263.3 | 277.7 | 204.63 ± 25.69 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|