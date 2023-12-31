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
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.8 | 2.2 | 1.00 |
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.4 | 1.00 ± 0.08 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.8 | 2.6 | 1.04 ± 0.11 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 2.7 | 1.17 ± 0.12 |
| mattcl | input-kcen | 2.5 ± 0.2 | 2.1 | 3.7 | 1.34 ± 0.12 |
| mattcl | input-pting | 2.6 ± 0.4 | 2.1 | 5.0 | 1.38 ± 0.20 |
| mattcl | input-mattcl | 2.6 ± 0.3 | 2.1 | 4.8 | 1.40 ± 0.16 |
| mattcl | input-lanjian | 2.9 ± 3.2 | 2.1 | 47.8 | 1.52 ± 1.70 |
| pting | input-kcen | 67.6 ± 1.3 | 64.8 | 71.8 | 35.87 ± 1.67 |
| pting | input-lanjian | 68.4 ± 1.3 | 66.5 | 72.5 | 36.30 ± 1.67 |
| pting | input-mattcl | 68.8 ± 1.1 | 66.8 | 71.7 | 36.56 ± 1.65 |
| pting | input-pting | 70.3 ± 0.8 | 68.7 | 72.2 | 37.31 ± 1.63 |
| mattcl-py | input-kcen | 90.0 ± 1.2 | 88.0 | 92.9 | 47.77 ± 2.11 |
| mattcl-py | input-mattcl | 92.7 ± 1.2 | 90.3 | 95.4 | 49.22 ± 2.17 |
| mattcl-py | input-pting | 95.3 ± 1.2 | 93.1 | 98.5 | 50.62 ± 2.23 |
| mattcl-py | input-lanjian | 96.5 ± 17.0 | 89.6 | 176.6 | 51.25 ± 9.28 |
| kcen | input-kcen | 232.2 ± 2.7 | 228.1 | 238.6 | 123.29 ± 5.39 |
| kcen | input-pting | 237.7 ± 6.2 | 230.4 | 246.6 | 126.22 ± 6.24 |
| kcen | input-mattcl | 257.2 ± 8.5 | 246.7 | 273.1 | 136.58 ± 7.30 |
| kcen | input-lanjian | 271.4 ± 5.6 | 263.7 | 280.8 | 144.12 ± 6.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|