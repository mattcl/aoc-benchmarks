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
| lanjian | input-lanjian | 2.0 ± 0.2 | 1.7 | 2.6 | 1.06 ± 0.14 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.5 | 1.13 ± 0.13 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.8 | 2.6 | 1.17 ± 0.14 |
| mattcl | input-kcen | 2.5 ± 0.3 | 2.0 | 4.9 | 1.33 ± 0.17 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.0 | 3.8 | 1.35 ± 0.15 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.1 | 4.0 | 1.35 ± 0.15 |
| mattcl | input-mattcl | 2.5 ± 0.3 | 2.0 | 5.2 | 1.38 ± 0.18 |
| pting | input-kcen | 67.6 ± 1.2 | 65.6 | 70.5 | 36.49 ± 2.44 |
| pting | input-mattcl | 69.1 ± 1.1 | 67.1 | 71.4 | 37.31 ± 2.48 |
| pting | input-lanjian | 69.2 ± 1.1 | 66.6 | 71.8 | 37.39 ± 2.48 |
| pting | input-pting | 70.4 ± 0.9 | 68.5 | 72.5 | 38.05 ± 2.50 |
| mattcl-py | input-kcen | 90.7 ± 1.3 | 88.0 | 94.0 | 49.00 ± 3.24 |
| mattcl-py | input-lanjian | 92.4 ± 1.3 | 90.2 | 95.3 | 49.91 ± 3.29 |
| mattcl-py | input-mattcl | 93.8 ± 1.8 | 90.5 | 101.5 | 50.68 ± 3.42 |
| mattcl-py | input-pting | 95.6 ± 1.4 | 93.1 | 98.8 | 51.67 ± 3.42 |
| kcen | input-kcen | 233.1 ± 3.5 | 227.3 | 239.1 | 125.92 ± 8.34 |
| kcen | input-pting | 239.0 ± 4.1 | 233.0 | 246.4 | 129.10 ± 8.62 |
| kcen | input-mattcl | 258.9 ± 6.5 | 249.0 | 272.7 | 139.85 ± 9.68 |
| kcen | input-lanjian | 271.3 ± 5.8 | 264.7 | 283.6 | 146.59 ± 9.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|