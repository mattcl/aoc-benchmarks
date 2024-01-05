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
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.4 | 1.00 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.7 | 1.06 ± 0.14 |
| lanjian | input-lanjian | 2.0 ± 0.2 | 1.8 | 2.6 | 1.09 ± 0.14 |
| mattcl | input-kcen | 2.2 ± 0.2 | 1.8 | 2.9 | 1.15 ± 0.14 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.8 | 2.7 | 1.15 ± 0.14 |
| mattcl | input-lanjian | 2.2 ± 0.2 | 1.9 | 2.9 | 1.20 ± 0.15 |
| mattcl | input-mattcl | 2.3 ± 0.2 | 1.9 | 2.9 | 1.23 ± 0.14 |
| mattcl | input-pting | 2.3 ± 0.2 | 1.9 | 2.8 | 1.23 ± 0.14 |
| pting | input-kcen | 67.3 ± 1.2 | 65.2 | 71.4 | 35.93 ± 2.62 |
| pting | input-lanjian | 68.3 ± 0.9 | 66.6 | 70.6 | 36.49 ± 2.63 |
| pting | input-mattcl | 68.9 ± 1.0 | 66.6 | 71.5 | 36.80 ± 2.66 |
| pting | input-pting | 70.1 ± 1.0 | 67.6 | 72.5 | 37.46 ± 2.70 |
| mattcl-py | input-kcen | 89.8 ± 1.6 | 87.2 | 94.2 | 47.98 ± 3.49 |
| mattcl-py | input-lanjian | 92.1 ± 1.4 | 89.6 | 95.6 | 49.17 ± 3.56 |
| mattcl-py | input-mattcl | 92.4 ± 1.5 | 90.6 | 96.2 | 49.37 ± 3.58 |
| mattcl-py | input-pting | 95.2 ± 1.3 | 93.1 | 99.1 | 50.86 ± 3.66 |
| kcen | input-kcen | 235.2 ± 3.2 | 229.7 | 239.7 | 125.62 ± 9.03 |
| kcen | input-pting | 248.8 ± 7.7 | 240.3 | 267.2 | 132.88 ± 10.26 |
| kcen | input-mattcl | 259.1 ± 7.3 | 248.2 | 270.9 | 138.36 ± 10.52 |
| kcen | input-lanjian | 271.5 ± 6.6 | 260.8 | 281.6 | 145.00 ± 10.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|