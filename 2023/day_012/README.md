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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.2 | 1.00 |
| lanjian | input-lanjian | 2.0 ± 0.2 | 1.7 | 2.6 | 1.11 ± 0.14 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.8 | 2.6 | 1.13 ± 0.14 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.5 | 1.17 ± 0.13 |
| mattcl | input-kcen | 2.4 ± 0.2 | 2.0 | 3.5 | 1.33 ± 0.14 |
| mattcl | input-mattcl | 2.5 ± 0.2 | 2.0 | 3.2 | 1.37 ± 0.16 |
| mattcl | input-pting | 2.5 ± 0.3 | 2.1 | 5.4 | 1.38 ± 0.19 |
| mattcl | input-lanjian | 2.6 ± 2.4 | 2.0 | 36.8 | 1.45 ± 1.35 |
| pting | input-kcen | 67.2 ± 0.9 | 65.1 | 69.5 | 37.18 ± 2.48 |
| pting | input-lanjian | 68.5 ± 1.3 | 66.8 | 72.9 | 37.93 ± 2.58 |
| pting | input-mattcl | 68.9 ± 1.3 | 66.5 | 72.2 | 38.17 ± 2.60 |
| pting | input-pting | 69.9 ± 1.0 | 68.2 | 72.6 | 38.69 ± 2.59 |
| mattcl-py | input-kcen | 89.8 ± 1.2 | 87.9 | 92.6 | 49.71 ± 3.32 |
| mattcl-py | input-lanjian | 92.1 ± 1.1 | 90.2 | 95.0 | 50.98 ± 3.40 |
| mattcl-py | input-mattcl | 92.5 ± 1.4 | 90.8 | 97.8 | 51.23 ± 3.45 |
| mattcl-py | input-pting | 95.2 ± 1.3 | 92.9 | 97.5 | 52.70 ± 3.52 |
| kcen | input-kcen | 232.9 ± 5.3 | 225.0 | 244.0 | 128.95 ± 8.95 |
| kcen | input-pting | 238.2 ± 6.8 | 228.5 | 252.5 | 131.86 ± 9.42 |
| kcen | input-mattcl | 258.7 ± 4.1 | 253.0 | 267.7 | 143.19 ± 9.65 |
| kcen | input-lanjian | 268.8 ± 5.2 | 261.6 | 280.9 | 148.81 ± 10.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|