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
| lanjian | input-lanjian | 2.0 ± 0.2 | 1.7 | 3.9 | 1.04 ± 0.14 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.9 | 2.6 | 1.13 ± 0.13 |
| lanjian | input-pting | 2.2 ± 0.3 | 1.9 | 4.3 | 1.18 ± 0.16 |
| mattcl | input-kcen | 2.5 ± 0.2 | 2.0 | 3.5 | 1.31 ± 0.15 |
| mattcl | input-mattcl | 2.5 ± 0.2 | 2.1 | 3.0 | 1.34 ± 0.14 |
| mattcl | input-lanjian | 2.5 ± 0.3 | 2.1 | 3.9 | 1.34 ± 0.16 |
| mattcl | input-pting | 3.2 ± 4.6 | 2.1 | 45.4 | 1.71 ± 2.45 |
| pting | input-kcen | 67.5 ± 1.1 | 65.3 | 70.8 | 36.00 ± 2.54 |
| pting | input-lanjian | 68.6 ± 1.5 | 66.5 | 75.0 | 36.61 ± 2.63 |
| pting | input-mattcl | 69.0 ± 1.3 | 66.6 | 72.7 | 36.81 ± 2.62 |
| pting | input-pting | 70.4 ± 1.6 | 68.2 | 78.1 | 37.54 ± 2.71 |
| mattcl-py | input-kcen | 90.0 ± 1.4 | 87.0 | 92.7 | 47.98 ± 3.37 |
| mattcl-py | input-lanjian | 91.8 ± 1.2 | 89.1 | 95.3 | 48.95 ± 3.41 |
| mattcl-py | input-mattcl | 92.8 ± 1.7 | 89.9 | 95.9 | 49.52 ± 3.50 |
| mattcl-py | input-pting | 95.6 ± 1.8 | 92.1 | 100.3 | 51.01 ± 3.62 |
| kcen | input-kcen | 233.7 ± 5.1 | 227.3 | 243.8 | 124.68 ± 8.96 |
| kcen | input-pting | 238.0 ± 4.3 | 230.5 | 244.2 | 126.96 ± 8.99 |
| kcen | input-mattcl | 256.5 ± 6.0 | 248.2 | 265.4 | 136.83 ± 9.89 |
| kcen | input-lanjian | 271.6 ± 6.6 | 263.7 | 283.4 | 144.87 ± 10.52 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|