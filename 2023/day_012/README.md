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
| lanjian | input-pting | 2.0 ± 0.2 | 1.8 | 2.6 | 1.05 ± 0.12 |
| lanjian | input-lanjian | 2.0 ± 0.2 | 1.7 | 2.6 | 1.06 ± 0.13 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.9 | 1.10 ± 0.13 |
| mattcl | input-kcen | 2.4 ± 0.2 | 2.0 | 3.7 | 1.27 ± 0.16 |
| mattcl | input-lanjian | 2.4 ± 0.3 | 2.0 | 5.1 | 1.29 ± 0.18 |
| mattcl | input-mattcl | 2.5 ± 0.2 | 2.0 | 3.1 | 1.31 ± 0.14 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.0 | 3.1 | 1.33 ± 0.15 |
| pting | input-kcen | 66.7 ± 1.0 | 64.8 | 69.3 | 35.49 ± 2.68 |
| pting | input-lanjian | 67.8 ± 1.0 | 65.7 | 70.1 | 36.07 ± 2.72 |
| pting | input-mattcl | 67.9 ± 1.1 | 66.3 | 71.9 | 36.14 ± 2.74 |
| pting | input-pting | 69.5 ± 1.1 | 67.6 | 71.7 | 36.99 ± 2.80 |
| mattcl-py | input-kcen | 89.3 ± 1.3 | 86.6 | 91.9 | 47.55 ± 3.59 |
| mattcl-py | input-lanjian | 91.1 ± 1.6 | 89.1 | 95.2 | 48.51 ± 3.69 |
| mattcl-py | input-mattcl | 92.1 ± 1.3 | 89.9 | 96.5 | 49.04 ± 3.70 |
| mattcl-py | input-pting | 94.0 ± 1.0 | 91.7 | 96.0 | 50.04 ± 3.75 |
| kcen | input-kcen | 230.3 ± 4.9 | 225.1 | 240.4 | 122.60 ± 9.45 |
| kcen | input-pting | 234.8 ± 4.3 | 229.9 | 244.8 | 125.00 ± 9.54 |
| kcen | input-mattcl | 253.6 ± 7.9 | 243.9 | 266.7 | 135.03 ± 10.85 |
| kcen | input-lanjian | 269.8 ± 6.9 | 261.2 | 282.0 | 143.67 ± 11.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|