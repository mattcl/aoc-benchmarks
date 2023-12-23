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
| lanjian | input-kcen | 1.9 ± 0.1 | 1.8 | 2.4 | 1.00 |
| lanjian | input-lanjian | 2.0 ± 0.1 | 1.8 | 2.6 | 1.00 ± 0.08 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.8 | 2.7 | 1.11 ± 0.14 |
| lanjian | input-mattcl | 2.2 ± 0.2 | 1.9 | 2.7 | 1.12 ± 0.13 |
| mattcl | input-kcen | 2.6 ± 0.2 | 2.1 | 3.7 | 1.32 ± 0.15 |
| mattcl | input-mattcl | 2.6 ± 0.2 | 2.2 | 3.7 | 1.34 ± 0.14 |
| mattcl | input-pting | 2.6 ± 0.2 | 2.2 | 4.0 | 1.36 ± 0.14 |
| mattcl | input-lanjian | 2.7 ± 0.3 | 2.2 | 5.4 | 1.37 ± 0.20 |
| pting | input-kcen | 67.1 ± 0.9 | 65.1 | 69.6 | 34.42 ± 2.13 |
| pting | input-mattcl | 68.7 ± 1.0 | 67.0 | 71.5 | 35.25 ± 2.19 |
| pting | input-lanjian | 69.0 ± 1.5 | 67.0 | 74.0 | 35.38 ± 2.27 |
| pting | input-pting | 70.1 ± 1.0 | 68.1 | 73.2 | 35.96 ± 2.24 |
| mattcl-py | input-kcen | 89.9 ± 1.3 | 87.4 | 92.3 | 46.10 ± 2.86 |
| mattcl-py | input-lanjian | 92.0 ± 1.6 | 89.6 | 97.1 | 47.21 ± 2.96 |
| mattcl-py | input-mattcl | 92.7 ± 1.3 | 90.6 | 95.6 | 47.55 ± 2.94 |
| mattcl-py | input-pting | 95.2 ± 1.3 | 92.9 | 98.0 | 48.85 ± 3.02 |
| kcen | input-kcen | 230.4 ± 3.6 | 223.5 | 237.5 | 118.20 ± 7.38 |
| kcen | input-pting | 238.9 ± 5.9 | 231.2 | 252.6 | 122.57 ± 7.99 |
| kcen | input-mattcl | 257.5 ± 7.6 | 245.5 | 271.6 | 132.09 ± 8.88 |
| kcen | input-lanjian | 276.0 ± 9.1 | 263.9 | 293.9 | 141.60 ± 9.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|