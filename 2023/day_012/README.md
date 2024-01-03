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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.5 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.6 | 1.13 ± 0.13 |
| mattcl | input-kcen | 2.2 ± 0.2 | 1.8 | 3.1 | 1.18 ± 0.15 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.8 | 2.6 | 1.19 ± 0.14 |
| mattcl | input-pting | 2.2 ± 0.2 | 1.9 | 2.8 | 1.21 ± 0.14 |
| mattcl | input-mattcl | 2.2 ± 0.2 | 1.9 | 2.7 | 1.22 ± 0.14 |
| mattcl | input-lanjian | 2.3 ± 0.2 | 1.9 | 2.7 | 1.25 ± 0.13 |
| pting | input-kcen | 67.0 ± 0.8 | 65.7 | 69.0 | 36.49 ± 2.37 |
| pting | input-lanjian | 68.5 ± 1.1 | 65.9 | 70.7 | 37.30 ± 2.45 |
| pting | input-mattcl | 68.6 ± 1.0 | 66.8 | 70.7 | 37.37 ± 2.45 |
| pting | input-pting | 70.2 ± 1.1 | 67.9 | 73.3 | 38.22 ± 2.51 |
| mattcl-py | input-kcen | 90.4 ± 1.5 | 87.9 | 94.9 | 49.25 ± 3.25 |
| mattcl-py | input-lanjian | 92.2 ± 1.2 | 90.1 | 94.6 | 50.21 ± 3.27 |
| mattcl-py | input-mattcl | 92.5 ± 1.1 | 90.3 | 94.4 | 50.37 ± 3.27 |
| mattcl-py | input-pting | 95.3 ± 1.4 | 92.9 | 98.2 | 51.93 ± 3.40 |
| kcen | input-kcen | 230.9 ± 3.8 | 226.6 | 239.1 | 125.76 ± 8.28 |
| kcen | input-pting | 236.6 ± 3.6 | 231.7 | 244.4 | 128.89 ± 8.45 |
| kcen | input-mattcl | 257.6 ± 6.4 | 246.7 | 271.0 | 140.30 ± 9.60 |
| kcen | input-lanjian | 268.4 ± 4.6 | 263.1 | 277.0 | 146.21 ± 9.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|