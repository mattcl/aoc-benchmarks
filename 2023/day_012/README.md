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
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.8 | 2.4 | 1.00 |
| lanjian | input-kcen | 1.9 ± 0.1 | 1.8 | 2.4 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 1.9 ± 0.1 | 1.8 | 2.5 | 1.00 ± 0.09 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 2.7 | 1.14 ± 0.13 |
| mattcl | input-kcen | 2.5 ± 0.3 | 2.0 | 5.1 | 1.27 ± 0.18 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.1 | 3.8 | 1.31 ± 0.13 |
| mattcl | input-lanjian | 2.6 ± 0.2 | 2.2 | 4.2 | 1.32 ± 0.14 |
| mattcl | input-mattcl | 2.6 ± 0.3 | 2.2 | 5.3 | 1.36 ± 0.18 |
| pting | input-kcen | 66.6 ± 0.9 | 64.7 | 68.9 | 34.31 ± 1.96 |
| pting | input-lanjian | 67.2 ± 0.8 | 65.9 | 69.8 | 34.66 ± 1.96 |
| pting | input-mattcl | 68.3 ± 1.1 | 66.4 | 71.9 | 35.22 ± 2.03 |
| pting | input-pting | 69.5 ± 1.0 | 67.7 | 72.6 | 35.81 ± 2.05 |
| mattcl-py | input-kcen | 88.9 ± 1.0 | 86.7 | 91.2 | 45.84 ± 2.59 |
| mattcl-py | input-lanjian | 91.2 ± 0.8 | 89.9 | 93.1 | 47.02 ± 2.63 |
| mattcl-py | input-mattcl | 93.0 ± 6.4 | 89.8 | 126.9 | 47.96 ± 4.25 |
| mattcl-py | input-pting | 93.9 ± 1.4 | 91.5 | 98.5 | 48.38 ± 2.77 |
| kcen | input-kcen | 228.6 ± 5.1 | 221.7 | 238.0 | 117.84 ± 7.03 |
| kcen | input-pting | 234.5 ± 3.5 | 228.6 | 239.6 | 120.85 ± 6.92 |
| kcen | input-mattcl | 259.3 ± 13.2 | 248.0 | 296.4 | 133.67 ± 10.06 |
| kcen | input-lanjian | 265.7 ± 6.4 | 259.0 | 281.7 | 136.95 ± 8.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|