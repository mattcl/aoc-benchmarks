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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.9 ± 0.2 | 1.7 | 2.6 | 1.05 ± 0.13 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.5 | 1.13 ± 0.13 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.7 | 1.18 ± 0.14 |
| mattcl | input-kcen | 2.4 ± 0.2 | 2.0 | 3.6 | 1.32 ± 0.15 |
| mattcl | input-lanjian | 2.4 ± 0.2 | 2.0 | 3.3 | 1.35 ± 0.15 |
| mattcl | input-mattcl | 2.4 ± 0.3 | 2.0 | 5.5 | 1.36 ± 0.20 |
| mattcl | input-pting | 2.5 ± 0.3 | 2.0 | 5.5 | 1.38 ± 0.19 |
| pting | input-kcen | 67.0 ± 1.0 | 65.0 | 69.3 | 37.29 ± 2.60 |
| pting | input-lanjian | 68.2 ± 0.8 | 66.4 | 70.7 | 37.95 ± 2.62 |
| pting | input-mattcl | 69.1 ± 1.3 | 66.8 | 73.4 | 38.43 ± 2.71 |
| pting | input-pting | 70.2 ± 1.2 | 68.3 | 73.7 | 39.04 ± 2.74 |
| mattcl-py | input-kcen | 89.7 ± 1.1 | 87.8 | 91.9 | 49.92 ± 3.46 |
| mattcl-py | input-lanjian | 91.8 ± 1.2 | 89.2 | 95.5 | 51.05 ± 3.55 |
| mattcl-py | input-mattcl | 92.4 ± 1.2 | 89.7 | 95.2 | 51.41 ± 3.57 |
| mattcl-py | input-pting | 97.7 ± 8.0 | 93.0 | 139.2 | 54.38 ± 5.78 |
| kcen | input-kcen | 232.0 ± 4.3 | 226.2 | 240.8 | 129.04 ± 9.12 |
| kcen | input-pting | 237.8 ± 3.9 | 232.3 | 246.7 | 132.32 ± 9.28 |
| kcen | input-mattcl | 259.4 ± 4.5 | 251.3 | 268.7 | 144.32 ± 10.16 |
| kcen | input-lanjian | 272.1 ± 5.7 | 267.1 | 283.4 | 151.37 ± 10.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|