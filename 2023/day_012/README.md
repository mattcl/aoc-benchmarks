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
| lanjian | input-kcen | 1.9 ± 0.1 | 1.8 | 2.6 | 1.00 |
| lanjian | input-lanjian | 2.0 ± 0.1 | 1.8 | 2.4 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 2.2 ± 0.2 | 1.9 | 2.8 | 1.11 ± 0.13 |
| lanjian | input-pting | 2.2 ± 0.2 | 2.0 | 2.7 | 1.15 ± 0.14 |
| mattcl | input-kcen | 2.6 ± 0.3 | 2.1 | 5.6 | 1.31 ± 0.18 |
| mattcl | input-pting | 2.6 ± 0.2 | 2.2 | 3.1 | 1.33 ± 0.14 |
| mattcl | input-lanjian | 2.6 ± 0.2 | 2.2 | 3.4 | 1.35 ± 0.14 |
| mattcl | input-mattcl | 2.6 ± 0.3 | 2.2 | 4.1 | 1.36 ± 0.16 |
| pting | input-kcen | 67.2 ± 1.0 | 64.9 | 69.9 | 34.45 ± 2.45 |
| pting | input-lanjian | 68.5 ± 1.1 | 66.3 | 72.0 | 35.13 ± 2.51 |
| pting | input-mattcl | 68.8 ± 1.1 | 66.6 | 71.9 | 35.28 ± 2.51 |
| pting | input-pting | 70.1 ± 1.2 | 67.8 | 72.8 | 35.97 ± 2.58 |
| mattcl-py | input-kcen | 90.0 ± 1.3 | 87.3 | 92.9 | 46.15 ± 3.27 |
| mattcl-py | input-lanjian | 91.6 ± 1.1 | 89.7 | 95.0 | 46.98 ± 3.31 |
| mattcl-py | input-mattcl | 92.8 ± 1.9 | 90.0 | 100.0 | 47.58 ± 3.44 |
| mattcl-py | input-pting | 95.0 ± 1.4 | 92.6 | 98.0 | 48.75 ± 3.46 |
| kcen | input-kcen | 232.2 ± 4.2 | 226.5 | 238.4 | 119.13 ± 8.54 |
| kcen | input-pting | 236.8 ± 6.3 | 229.2 | 247.6 | 121.50 ± 9.03 |
| kcen | input-mattcl | 257.2 ± 4.9 | 247.4 | 264.9 | 131.96 ± 9.50 |
| kcen | input-lanjian | 268.8 ± 4.4 | 262.5 | 275.8 | 137.88 ± 9.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|