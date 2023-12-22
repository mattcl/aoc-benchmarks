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
| lanjian | input-mattcl | 1.8 ± 0.1 | 1.6 | 2.2 | 1.00 |
| lanjian | input-kcen | 1.8 ± 0.2 | 1.6 | 3.2 | 1.01 ± 0.11 |
| lanjian | input-lanjian | 1.9 ± 0.2 | 1.6 | 2.5 | 1.09 ± 0.14 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.6 | 1.18 ± 0.14 |
| mattcl | input-kcen | 2.4 ± 0.2 | 1.9 | 3.4 | 1.35 ± 0.15 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.0 | 3.7 | 1.39 ± 0.16 |
| mattcl | input-mattcl | 2.6 ± 0.3 | 2.1 | 4.0 | 1.45 ± 0.18 |
| mattcl | input-lanjian | 2.6 ± 2.6 | 2.0 | 39.7 | 1.49 ± 1.50 |
| pting | input-kcen | 67.4 ± 1.0 | 65.6 | 70.1 | 38.08 ± 2.20 |
| pting | input-lanjian | 68.4 ± 1.2 | 65.7 | 71.8 | 38.67 ± 2.27 |
| pting | input-mattcl | 69.2 ± 1.1 | 67.3 | 72.0 | 39.11 ± 2.28 |
| pting | input-pting | 69.9 ± 1.0 | 67.6 | 72.5 | 39.50 ± 2.28 |
| mattcl-py | input-kcen | 89.7 ± 1.1 | 87.2 | 92.5 | 50.71 ± 2.91 |
| mattcl-py | input-lanjian | 92.0 ± 1.4 | 89.4 | 96.0 | 51.98 ± 3.01 |
| mattcl-py | input-mattcl | 92.8 ± 1.3 | 90.8 | 95.7 | 52.45 ± 3.02 |
| mattcl-py | input-pting | 95.5 ± 1.3 | 92.8 | 99.4 | 53.95 ± 3.11 |
| kcen | input-kcen | 231.8 ± 4.1 | 223.9 | 238.1 | 131.02 ± 7.70 |
| kcen | input-pting | 238.7 ± 4.0 | 233.8 | 244.8 | 134.90 ± 7.89 |
| kcen | input-mattcl | 258.2 ± 5.7 | 248.7 | 268.0 | 145.93 ± 8.78 |
| kcen | input-lanjian | 267.6 ± 2.7 | 263.6 | 271.9 | 151.26 ± 8.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|