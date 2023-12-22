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
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.8 | 2.3 | 1.00 ± 0.10 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.7 | 1.08 ± 0.14 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.6 | 1.09 ± 0.13 |
| mattcl | input-lanjian | 2.5 ± 0.3 | 2.0 | 4.1 | 1.31 ± 0.17 |
| mattcl | input-mattcl | 2.5 ± 0.2 | 2.1 | 3.7 | 1.33 ± 0.15 |
| mattcl | input-pting | 2.6 ± 0.2 | 2.1 | 3.9 | 1.35 ± 0.16 |
| mattcl | input-kcen | 3.0 ± 4.4 | 2.0 | 50.1 | 1.55 ± 2.32 |
| pting | input-kcen | 66.7 ± 0.9 | 65.2 | 69.0 | 34.94 ± 2.61 |
| pting | input-lanjian | 67.9 ± 1.2 | 65.4 | 71.5 | 35.58 ± 2.69 |
| pting | input-mattcl | 68.1 ± 1.1 | 65.8 | 70.7 | 35.69 ± 2.69 |
| pting | input-pting | 69.1 ± 1.0 | 67.4 | 72.0 | 36.16 ± 2.72 |
| mattcl-py | input-kcen | 88.6 ± 1.0 | 86.7 | 90.9 | 46.41 ± 3.45 |
| mattcl-py | input-lanjian | 91.2 ± 1.0 | 88.5 | 93.4 | 47.74 ± 3.55 |
| mattcl-py | input-mattcl | 92.0 ± 1.4 | 89.9 | 95.7 | 48.21 ± 3.62 |
| mattcl-py | input-pting | 94.2 ± 1.6 | 91.7 | 99.4 | 49.36 ± 3.73 |
| kcen | input-kcen | 232.4 ± 5.5 | 224.3 | 241.1 | 121.72 ± 9.41 |
| kcen | input-pting | 235.4 ± 4.6 | 229.1 | 244.8 | 123.29 ± 9.39 |
| kcen | input-mattcl | 253.3 ± 4.2 | 247.3 | 259.5 | 132.66 ± 10.01 |
| kcen | input-lanjian | 269.4 ± 7.5 | 262.1 | 282.8 | 141.11 ± 11.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|