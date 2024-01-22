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
| mattcl | input-kcen | 1.4 ± 0.1 | 1.2 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.1 | 1.2 | 1.8 | 1.04 ± 0.15 |
| mattcl | input-pting | 1.5 ± 0.2 | 1.2 | 1.9 | 1.05 ± 0.16 |
| mattcl | input-lanjian | 1.7 ± 0.3 | 1.4 | 4.9 | 1.20 ± 0.24 |
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.3 | 1.37 ± 0.17 |
| lanjian | input-lanjian | 2.0 ± 0.2 | 1.7 | 3.0 | 1.42 ± 0.21 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.6 | 1.46 ± 0.21 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.6 | 1.53 ± 0.22 |
| pting | input-kcen | 66.5 ± 1.0 | 65.1 | 69.9 | 47.70 ± 4.96 |
| pting | input-lanjian | 68.0 ± 0.7 | 66.7 | 69.5 | 48.79 ± 5.05 |
| pting | input-mattcl | 68.6 ± 1.0 | 67.0 | 71.4 | 49.23 ± 5.12 |
| pting | input-pting | 69.7 ± 1.2 | 67.7 | 72.6 | 50.02 ± 5.22 |
| mattcl-py | input-kcen | 90.6 ± 1.1 | 88.3 | 92.3 | 64.99 ± 6.73 |
| mattcl-py | input-lanjian | 92.8 ± 1.1 | 91.0 | 95.1 | 66.56 ± 6.90 |
| mattcl-py | input-mattcl | 93.6 ± 1.5 | 91.4 | 96.6 | 67.15 ± 6.99 |
| mattcl-py | input-pting | 95.9 ± 1.2 | 94.1 | 98.6 | 68.83 ± 7.14 |
| kcen | input-kcen | 234.0 ± 3.7 | 227.0 | 241.0 | 167.82 ± 17.47 |
| kcen | input-pting | 237.9 ± 6.5 | 229.5 | 251.2 | 170.68 ± 18.16 |
| kcen | input-mattcl | 263.6 ± 5.2 | 257.2 | 274.1 | 189.07 ± 19.81 |
| kcen | input-lanjian | 269.7 ± 5.0 | 263.5 | 278.5 | 193.47 ± 20.22 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|