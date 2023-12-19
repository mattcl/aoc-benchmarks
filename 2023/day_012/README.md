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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.4 | 1.00 |
| lanjian | input-lanjian | 2.0 ± 0.3 | 1.7 | 5.8 | 1.12 ± 0.21 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.5 | 1.13 ± 0.14 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.6 | 1.18 ± 0.15 |
| mattcl | input-kcen | 2.4 ± 0.2 | 1.9 | 3.1 | 1.32 ± 0.15 |
| mattcl | input-lanjian | 2.4 ± 0.2 | 2.0 | 2.8 | 1.33 ± 0.14 |
| mattcl | input-mattcl | 2.4 ± 0.3 | 2.0 | 3.9 | 1.37 ± 0.18 |
| mattcl | input-pting | 2.4 ± 0.2 | 2.0 | 3.1 | 1.37 ± 0.14 |
| pting | input-kcen | 67.1 ± 1.0 | 65.3 | 69.7 | 37.56 ± 2.58 |
| pting | input-lanjian | 68.1 ± 0.9 | 66.4 | 70.6 | 38.11 ± 2.61 |
| pting | input-mattcl | 68.8 ± 1.4 | 66.7 | 72.5 | 38.49 ± 2.69 |
| pting | input-pting | 69.9 ± 0.8 | 68.0 | 72.0 | 39.09 ± 2.66 |
| mattcl-py | input-kcen | 88.8 ± 0.9 | 87.0 | 90.8 | 49.68 ± 3.37 |
| mattcl-py | input-lanjian | 91.9 ± 1.3 | 89.7 | 94.3 | 51.42 ± 3.52 |
| mattcl-py | input-mattcl | 92.4 ± 1.6 | 89.5 | 95.7 | 51.68 ± 3.58 |
| mattcl-py | input-pting | 95.4 ± 2.5 | 92.6 | 106.8 | 53.35 ± 3.84 |
| kcen | input-kcen | 233.0 ± 5.1 | 225.7 | 244.1 | 130.35 ± 9.19 |
| kcen | input-pting | 237.5 ± 5.4 | 232.2 | 252.9 | 132.86 ± 9.40 |
| kcen | input-mattcl | 255.9 ± 5.7 | 248.1 | 265.4 | 143.14 ± 10.12 |
| kcen | input-lanjian | 270.0 ± 4.5 | 263.3 | 275.6 | 151.01 ± 10.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|