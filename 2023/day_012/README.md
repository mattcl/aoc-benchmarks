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
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.3 | 1.00 ± 0.11 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.6 | 1.10 ± 0.14 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.7 | 2.6 | 1.10 ± 0.15 |
| mattcl | input-kcen | 2.4 ± 0.3 | 1.9 | 5.8 | 1.29 ± 0.22 |
| mattcl | input-lanjian | 2.4 ± 0.2 | 1.9 | 3.0 | 1.30 ± 0.15 |
| mattcl | input-mattcl | 2.4 ± 0.3 | 2.0 | 4.7 | 1.33 ± 0.19 |
| mattcl | input-pting | 2.4 ± 0.2 | 2.0 | 3.1 | 1.33 ± 0.16 |
| pting | input-kcen | 66.6 ± 1.1 | 65.2 | 69.5 | 36.34 ± 2.95 |
| pting | input-lanjian | 68.0 ± 1.3 | 65.7 | 71.2 | 37.08 ± 3.03 |
| pting | input-mattcl | 68.3 ± 1.3 | 66.4 | 72.9 | 37.26 ± 3.04 |
| pting | input-pting | 69.3 ± 1.2 | 67.1 | 72.1 | 37.77 ± 3.07 |
| mattcl-py | input-kcen | 88.8 ± 1.1 | 86.5 | 92.0 | 48.43 ± 3.90 |
| mattcl-py | input-lanjian | 91.0 ± 1.2 | 89.1 | 93.2 | 49.64 ± 4.00 |
| mattcl-py | input-mattcl | 92.1 ± 1.4 | 90.0 | 96.3 | 50.21 ± 4.07 |
| mattcl-py | input-pting | 94.4 ± 1.2 | 92.3 | 96.9 | 51.46 ± 4.14 |
| kcen | input-kcen | 231.8 ± 4.6 | 221.8 | 239.1 | 126.43 ± 10.36 |
| kcen | input-pting | 236.5 ± 4.7 | 230.0 | 245.1 | 129.00 ± 10.58 |
| kcen | input-mattcl | 253.1 ± 6.7 | 245.9 | 267.3 | 138.04 ± 11.57 |
| kcen | input-lanjian | 271.2 ± 7.3 | 262.3 | 285.2 | 147.90 ± 12.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|