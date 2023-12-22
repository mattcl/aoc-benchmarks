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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.5 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.5 | 1.13 ± 0.12 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.6 | 1.18 ± 0.13 |
| mattcl | input-kcen | 2.4 ± 0.2 | 1.9 | 3.9 | 1.34 ± 0.15 |
| mattcl | input-mattcl | 2.5 ± 0.3 | 2.0 | 4.9 | 1.36 ± 0.16 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.0 | 4.1 | 1.37 ± 0.15 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.1 | 3.5 | 1.39 ± 0.15 |
| pting | input-kcen | 67.1 ± 1.0 | 64.9 | 69.2 | 37.11 ± 1.90 |
| pting | input-lanjian | 68.2 ± 1.0 | 65.4 | 70.8 | 37.75 ± 1.93 |
| pting | input-mattcl | 68.7 ± 0.9 | 66.9 | 71.0 | 38.00 ± 1.93 |
| pting | input-pting | 69.9 ± 1.0 | 66.8 | 72.0 | 38.68 ± 1.97 |
| mattcl-py | input-kcen | 90.1 ± 1.1 | 87.4 | 92.0 | 49.87 ± 2.52 |
| mattcl-py | input-lanjian | 92.3 ± 1.1 | 90.6 | 94.6 | 51.09 ± 2.57 |
| mattcl-py | input-mattcl | 93.2 ± 3.8 | 90.2 | 112.9 | 51.58 ± 3.29 |
| mattcl-py | input-pting | 95.3 ± 1.1 | 93.6 | 97.7 | 52.71 ± 2.66 |
| kcen | input-kcen | 235.2 ± 6.1 | 227.3 | 244.4 | 130.17 ± 7.20 |
| kcen | input-pting | 238.2 ± 5.3 | 232.7 | 250.4 | 131.79 ± 7.10 |
| kcen | input-mattcl | 257.8 ± 7.8 | 246.6 | 269.0 | 142.64 ± 8.20 |
| kcen | input-lanjian | 272.5 ± 4.3 | 263.5 | 277.8 | 150.79 ± 7.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|