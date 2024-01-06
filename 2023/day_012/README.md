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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.4 | 1.00 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.5 | 1.12 ± 0.13 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.8 | 2.8 | 1.16 ± 0.14 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.7 | 1.18 ± 0.14 |
| lanjian | input-lanjian | 2.1 ± 0.4 | 1.7 | 5.0 | 1.19 ± 0.22 |
| mattcl | input-lanjian | 2.1 ± 0.2 | 1.8 | 2.6 | 1.19 ± 0.13 |
| mattcl | input-mattcl | 2.2 ± 0.3 | 1.8 | 4.9 | 1.21 ± 0.17 |
| mattcl | input-pting | 2.2 ± 0.2 | 1.9 | 4.0 | 1.23 ± 0.15 |
| pting | input-kcen | 67.4 ± 0.9 | 65.6 | 69.4 | 37.54 ± 2.25 |
| pting | input-lanjian | 68.3 ± 1.0 | 66.4 | 70.8 | 38.06 ± 2.30 |
| pting | input-mattcl | 68.7 ± 1.0 | 66.6 | 70.8 | 38.27 ± 2.31 |
| pting | input-pting | 70.3 ± 1.0 | 67.8 | 73.5 | 39.18 ± 2.36 |
| mattcl-py | input-kcen | 91.0 ± 1.3 | 88.5 | 94.7 | 50.69 ± 3.06 |
| mattcl-py | input-lanjian | 93.2 ± 1.4 | 90.8 | 95.9 | 51.90 ± 3.13 |
| mattcl-py | input-mattcl | 94.2 ± 3.0 | 90.3 | 107.8 | 52.49 ± 3.49 |
| mattcl-py | input-pting | 95.7 ± 1.0 | 93.8 | 98.3 | 53.34 ± 3.18 |
| kcen | input-kcen | 233.4 ± 3.7 | 227.6 | 240.2 | 130.04 ± 7.89 |
| kcen | input-pting | 237.5 ± 4.1 | 229.5 | 245.5 | 132.30 ± 8.08 |
| kcen | input-mattcl | 256.0 ± 6.5 | 247.2 | 267.5 | 142.60 ± 9.09 |
| kcen | input-lanjian | 272.4 ± 9.0 | 261.1 | 290.7 | 151.78 ± 10.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|