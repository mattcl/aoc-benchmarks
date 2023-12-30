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
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.2 | 1.00 |
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.7 | 1.01 ± 0.10 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.8 | 2.8 | 1.11 ± 0.12 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.7 | 2.5 | 1.14 ± 0.14 |
| mattcl | input-kcen | 2.5 ± 0.3 | 2.0 | 4.9 | 1.34 ± 0.17 |
| mattcl | input-mattcl | 2.5 ± 0.2 | 2.1 | 3.5 | 1.37 ± 0.14 |
| mattcl | input-pting | 2.5 ± 0.3 | 2.1 | 3.9 | 1.39 ± 0.16 |
| mattcl | input-lanjian | 2.6 ± 0.2 | 2.1 | 3.6 | 1.41 ± 0.13 |
| pting | input-kcen | 67.1 ± 1.1 | 64.7 | 70.7 | 36.59 ± 2.29 |
| pting | input-lanjian | 68.1 ± 0.8 | 66.1 | 70.0 | 37.15 ± 2.29 |
| pting | input-mattcl | 68.7 ± 1.0 | 66.6 | 70.5 | 37.50 ± 2.32 |
| pting | input-pting | 69.9 ± 1.0 | 67.8 | 72.8 | 38.13 ± 2.36 |
| mattcl-py | input-kcen | 89.9 ± 1.0 | 88.2 | 92.0 | 49.06 ± 3.01 |
| mattcl-py | input-lanjian | 92.2 ± 1.3 | 89.8 | 95.2 | 50.32 ± 3.11 |
| mattcl-py | input-mattcl | 92.7 ± 1.2 | 90.5 | 95.2 | 50.57 ± 3.11 |
| mattcl-py | input-pting | 94.7 ± 1.1 | 92.6 | 96.8 | 51.70 ± 3.18 |
| kcen | input-kcen | 234.1 ± 5.6 | 225.2 | 242.2 | 127.75 ± 8.28 |
| kcen | input-pting | 238.5 ± 5.7 | 232.0 | 253.7 | 130.15 ± 8.45 |
| kcen | input-mattcl | 257.0 ± 5.8 | 246.2 | 263.6 | 140.27 ± 9.02 |
| kcen | input-lanjian | 269.0 ± 5.2 | 263.5 | 279.0 | 146.76 ± 9.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|