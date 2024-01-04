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
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.8 | 2.4 | 1.00 |
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.3 | 1.00 ± 0.10 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.7 | 1.06 ± 0.13 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.9 | 2.7 | 1.11 ± 0.12 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 2.7 | 1.14 ± 0.14 |
| mattcl | input-pting | 2.2 ± 0.2 | 1.9 | 3.1 | 1.15 ± 0.13 |
| mattcl | input-mattcl | 2.3 ± 0.2 | 2.0 | 2.8 | 1.19 ± 0.13 |
| mattcl | input-lanjian | 2.3 ± 0.2 | 1.9 | 2.9 | 1.19 ± 0.14 |
| pting | input-kcen | 66.4 ± 1.0 | 64.7 | 69.4 | 34.47 ± 2.29 |
| pting | input-lanjian | 67.4 ± 1.1 | 65.5 | 70.8 | 34.97 ± 2.33 |
| pting | input-mattcl | 68.2 ± 1.0 | 65.6 | 70.5 | 35.41 ± 2.35 |
| pting | input-pting | 72.3 ± 11.5 | 67.7 | 132.0 | 37.52 ± 6.43 |
| mattcl-py | input-kcen | 88.8 ± 1.5 | 85.6 | 92.0 | 46.11 ± 3.07 |
| mattcl-py | input-lanjian | 90.9 ± 1.5 | 88.3 | 94.7 | 47.19 ± 3.14 |
| mattcl-py | input-mattcl | 91.5 ± 1.3 | 89.4 | 95.2 | 47.51 ± 3.14 |
| mattcl-py | input-pting | 94.3 ± 1.5 | 92.1 | 97.4 | 48.96 ± 3.25 |
| kcen | input-kcen | 230.7 ± 4.4 | 225.8 | 238.4 | 119.78 ± 8.07 |
| kcen | input-pting | 233.9 ± 2.7 | 230.9 | 238.3 | 121.44 ± 7.97 |
| kcen | input-mattcl | 253.7 ± 6.0 | 244.1 | 262.7 | 131.70 ± 9.07 |
| kcen | input-lanjian | 267.7 ± 5.3 | 260.3 | 278.4 | 139.00 ± 9.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|