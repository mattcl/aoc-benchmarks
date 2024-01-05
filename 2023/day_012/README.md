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
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.8 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.6 | 1.12 ± 0.13 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.8 | 2.8 | 1.16 ± 0.14 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.8 | 2.6 | 1.18 ± 0.14 |
| mattcl | input-mattcl | 2.2 ± 0.2 | 1.9 | 2.9 | 1.21 ± 0.14 |
| mattcl | input-pting | 2.2 ± 0.2 | 1.9 | 2.8 | 1.22 ± 0.14 |
| mattcl | input-lanjian | 2.3 ± 0.3 | 1.9 | 4.6 | 1.25 ± 0.17 |
| pting | input-kcen | 67.1 ± 1.0 | 64.7 | 69.7 | 36.54 ± 2.38 |
| pting | input-lanjian | 68.3 ± 1.2 | 66.6 | 73.2 | 37.18 ± 2.44 |
| pting | input-mattcl | 69.1 ± 1.2 | 66.9 | 71.6 | 37.64 ± 2.46 |
| pting | input-pting | 70.0 ± 0.9 | 68.1 | 72.3 | 38.09 ± 2.46 |
| mattcl-py | input-kcen | 90.4 ± 1.2 | 88.2 | 92.9 | 49.23 ± 3.18 |
| mattcl-py | input-lanjian | 93.2 ± 1.5 | 90.5 | 98.0 | 50.74 ± 3.30 |
| mattcl-py | input-mattcl | 93.3 ± 1.5 | 91.0 | 96.7 | 50.78 ± 3.30 |
| mattcl-py | input-pting | 95.8 ± 1.2 | 93.0 | 98.1 | 52.12 ± 3.35 |
| kcen | input-kcen | 232.3 ± 3.2 | 228.0 | 236.4 | 126.47 ± 8.17 |
| kcen | input-pting | 238.9 ± 6.0 | 232.8 | 253.7 | 130.04 ± 8.83 |
| kcen | input-mattcl | 258.3 ± 5.7 | 247.8 | 269.6 | 140.62 ± 9.42 |
| kcen | input-lanjian | 269.9 ± 7.2 | 262.1 | 281.8 | 146.94 ± 10.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|