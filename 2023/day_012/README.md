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
| lanjian | input-lanjian | 1.8 ± 0.2 | 1.6 | 2.4 | 1.02 ± 0.11 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.6 | 2.6 | 1.09 ± 0.15 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.7 | 1.12 ± 0.13 |
| mattcl | input-kcen | 2.4 ± 0.3 | 1.9 | 4.3 | 1.32 ± 0.18 |
| mattcl | input-mattcl | 2.4 ± 0.2 | 2.0 | 2.9 | 1.34 ± 0.14 |
| mattcl | input-lanjian | 2.4 ± 0.2 | 2.0 | 3.9 | 1.36 ± 0.17 |
| mattcl | input-pting | 2.4 ± 0.2 | 2.0 | 3.7 | 1.36 ± 0.16 |
| pting | input-kcen | 67.1 ± 1.0 | 65.2 | 70.2 | 37.52 ± 2.74 |
| pting | input-lanjian | 68.1 ± 1.1 | 66.2 | 71.2 | 38.11 ± 2.79 |
| pting | input-mattcl | 68.8 ± 0.9 | 67.4 | 71.1 | 38.48 ± 2.79 |
| pting | input-pting | 69.7 ± 1.0 | 67.8 | 71.6 | 39.00 ± 2.83 |
| mattcl-py | input-kcen | 89.2 ± 1.5 | 86.1 | 93.6 | 49.88 ± 3.65 |
| mattcl-py | input-lanjian | 91.8 ± 1.4 | 89.3 | 94.2 | 51.34 ± 3.74 |
| mattcl-py | input-mattcl | 92.5 ± 1.3 | 89.5 | 95.0 | 51.74 ± 3.77 |
| mattcl-py | input-pting | 94.8 ± 1.3 | 91.8 | 96.9 | 53.05 ± 3.86 |
| kcen | input-kcen | 232.2 ± 4.1 | 227.4 | 239.8 | 129.92 ± 9.55 |
| kcen | input-pting | 236.4 ± 2.8 | 230.9 | 241.0 | 132.27 ± 9.56 |
| kcen | input-mattcl | 254.0 ± 5.2 | 247.3 | 263.3 | 142.09 ± 10.56 |
| kcen | input-lanjian | 272.1 ± 8.3 | 261.4 | 288.0 | 152.24 ± 11.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|