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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.2 | 1.00 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.3 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.6 | 1.12 ± 0.13 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.6 | 1.18 ± 0.14 |
| mattcl | input-kcen | 2.5 ± 0.4 | 2.0 | 5.3 | 1.37 ± 0.23 |
| mattcl | input-mattcl | 2.5 ± 0.2 | 2.1 | 3.9 | 1.38 ± 0.16 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.1 | 3.4 | 1.39 ± 0.15 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.1 | 3.6 | 1.41 ± 0.17 |
| pting | input-kcen | 67.2 ± 1.1 | 64.9 | 69.6 | 37.17 ± 2.59 |
| pting | input-lanjian | 68.1 ± 0.9 | 66.6 | 71.1 | 37.67 ± 2.60 |
| pting | input-mattcl | 68.8 ± 1.1 | 67.2 | 72.4 | 38.06 ± 2.66 |
| pting | input-pting | 69.9 ± 1.0 | 67.2 | 72.0 | 38.66 ± 2.68 |
| mattcl-py | input-kcen | 91.8 ± 7.6 | 88.1 | 131.8 | 50.75 ± 5.42 |
| mattcl-py | input-lanjian | 92.1 ± 1.0 | 90.6 | 94.2 | 50.93 ± 3.50 |
| mattcl-py | input-mattcl | 92.4 ± 1.5 | 90.4 | 97.9 | 51.08 ± 3.56 |
| mattcl-py | input-pting | 95.3 ± 0.9 | 93.9 | 96.8 | 52.71 ± 3.61 |
| kcen | input-kcen | 236.1 ± 3.7 | 229.8 | 243.1 | 130.56 ± 9.10 |
| kcen | input-pting | 238.1 ± 4.3 | 232.9 | 246.4 | 131.66 ± 9.24 |
| kcen | input-mattcl | 258.0 ± 6.6 | 250.2 | 270.2 | 142.66 ± 10.35 |
| kcen | input-lanjian | 267.8 ± 5.0 | 262.7 | 277.1 | 148.10 ± 10.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|