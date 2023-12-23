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
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.3 | 1.00 |
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.3 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.7 | 1.12 ± 0.13 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 2.9 | 1.17 ± 0.13 |
| mattcl | input-mattcl | 2.5 ± 0.2 | 2.1 | 4.5 | 1.35 ± 0.15 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.1 | 3.2 | 1.36 ± 0.14 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.1 | 3.2 | 1.36 ± 0.13 |
| mattcl | input-kcen | 2.7 ± 3.6 | 2.0 | 53.0 | 1.48 ± 1.94 |
| pting | input-kcen | 67.4 ± 1.0 | 65.4 | 70.3 | 36.43 ± 2.04 |
| pting | input-lanjian | 68.5 ± 0.9 | 67.2 | 71.2 | 37.01 ± 2.06 |
| pting | input-mattcl | 68.9 ± 1.2 | 67.0 | 72.2 | 37.24 ± 2.11 |
| pting | input-pting | 70.1 ± 1.1 | 68.2 | 72.5 | 37.88 ± 2.13 |
| mattcl-py | input-kcen | 92.2 ± 13.6 | 87.3 | 167.4 | 49.85 ± 7.82 |
| mattcl-py | input-lanjian | 92.3 ± 1.3 | 89.9 | 95.0 | 49.90 ± 2.78 |
| mattcl-py | input-mattcl | 92.5 ± 1.5 | 89.7 | 96.1 | 50.02 ± 2.81 |
| mattcl-py | input-pting | 95.2 ± 1.2 | 93.2 | 98.4 | 51.48 ± 2.85 |
| kcen | input-kcen | 233.6 ± 4.9 | 225.6 | 242.1 | 126.29 ± 7.31 |
| kcen | input-pting | 238.2 ± 5.6 | 232.1 | 251.3 | 128.75 ± 7.58 |
| kcen | input-mattcl | 257.1 ± 5.7 | 248.1 | 267.0 | 138.99 ± 8.11 |
| kcen | input-lanjian | 276.2 ± 6.1 | 266.2 | 283.9 | 149.29 ± 8.71 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|