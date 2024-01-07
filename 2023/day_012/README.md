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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.2 | 1.00 ± 0.08 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.5 | 1.13 ± 0.13 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.8 | 2.6 | 1.16 ± 0.12 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 3.0 | 1.19 ± 0.14 |
| mattcl | input-mattcl | 2.2 ± 0.3 | 1.8 | 4.7 | 1.22 ± 0.16 |
| mattcl | input-pting | 2.2 ± 0.2 | 1.8 | 3.3 | 1.24 ± 0.14 |
| mattcl | input-lanjian | 2.2 ± 0.2 | 1.9 | 2.8 | 1.24 ± 0.13 |
| pting | input-kcen | 67.6 ± 1.0 | 65.4 | 69.6 | 37.71 ± 1.94 |
| pting | input-lanjian | 68.5 ± 1.2 | 66.1 | 70.9 | 38.20 ± 1.99 |
| pting | input-mattcl | 69.1 ± 1.1 | 67.3 | 72.0 | 38.55 ± 2.00 |
| pting | input-pting | 70.2 ± 1.2 | 68.0 | 74.1 | 39.17 ± 2.04 |
| mattcl-py | input-kcen | 90.9 ± 1.4 | 88.8 | 94.9 | 50.71 ± 2.63 |
| mattcl-py | input-lanjian | 93.3 ± 1.3 | 90.7 | 95.9 | 52.04 ± 2.66 |
| mattcl-py | input-mattcl | 93.6 ± 1.7 | 91.4 | 98.3 | 52.23 ± 2.74 |
| mattcl-py | input-pting | 96.2 ± 1.1 | 94.3 | 99.1 | 53.69 ± 2.72 |
| kcen | input-kcen | 231.2 ± 5.0 | 224.8 | 241.9 | 129.02 ± 6.96 |
| kcen | input-pting | 237.3 ± 4.3 | 232.3 | 246.3 | 132.42 ± 6.97 |
| kcen | input-mattcl | 258.2 ± 5.7 | 249.6 | 267.4 | 144.05 ± 7.78 |
| kcen | input-lanjian | 270.2 ± 6.9 | 261.2 | 280.7 | 150.78 ± 8.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|