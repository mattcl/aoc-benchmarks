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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.1 | 1.7 | 1.00 |
| mattcl | input-pting | 1.4 ± 0.2 | 1.1 | 1.8 | 1.02 ± 0.17 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.1 | 1.9 | 1.07 ± 0.17 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.2 | 1.9 | 1.10 ± 0.17 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.2 | 1.35 ± 0.17 |
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.3 | 1.35 ± 0.18 |
| lanjian | input-mattcl | 1.9 ± 0.1 | 1.7 | 2.6 | 1.36 ± 0.18 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.6 | 1.57 ± 0.24 |
| pting | input-kcen | 66.5 ± 0.8 | 64.4 | 68.7 | 48.73 ± 5.63 |
| pting | input-mattcl | 67.9 ± 1.1 | 66.1 | 70.7 | 49.73 ± 5.77 |
| pting | input-lanjian | 68.7 ± 6.3 | 66.0 | 108.5 | 50.33 ± 7.39 |
| pting | input-pting | 69.1 ± 0.9 | 67.3 | 71.1 | 50.64 ± 5.85 |
| mattcl-py | input-kcen | 89.6 ± 0.8 | 88.2 | 91.1 | 65.70 ± 7.57 |
| mattcl-py | input-lanjian | 92.4 ± 1.7 | 89.5 | 99.2 | 67.71 ± 7.88 |
| mattcl-py | input-mattcl | 92.8 ± 1.5 | 90.2 | 95.9 | 68.00 ± 7.89 |
| mattcl-py | input-pting | 94.7 ± 1.2 | 92.9 | 98.4 | 69.44 ± 8.02 |
| kcen | input-kcen | 232.2 ± 3.0 | 227.2 | 236.3 | 170.17 ± 19.66 |
| kcen | input-pting | 232.3 ± 3.1 | 227.8 | 236.4 | 170.28 ± 19.69 |
| kcen | input-mattcl | 253.2 ± 6.6 | 244.0 | 263.6 | 185.53 ± 21.85 |
| kcen | input-lanjian | 265.5 ± 4.8 | 260.2 | 274.1 | 194.62 ± 22.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|