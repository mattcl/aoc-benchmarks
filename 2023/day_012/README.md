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
| lanjian | input-mattcl | 1.9 ± 0.2 | 1.8 | 2.6 | 1.00 |
| lanjian | input-kcen | 2.0 ± 0.3 | 1.7 | 5.1 | 1.01 ± 0.17 |
| lanjian | input-lanjian | 2.0 ± 0.2 | 1.8 | 2.6 | 1.02 ± 0.13 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 2.7 | 1.15 ± 0.15 |
| mattcl | input-kcen | 2.5 ± 0.3 | 2.1 | 5.1 | 1.29 ± 0.18 |
| mattcl | input-lanjian | 2.6 ± 0.2 | 2.1 | 3.5 | 1.32 ± 0.16 |
| mattcl | input-pting | 2.6 ± 0.3 | 2.1 | 6.1 | 1.33 ± 0.20 |
| mattcl | input-mattcl | 2.6 ± 0.3 | 2.1 | 5.3 | 1.36 ± 0.20 |
| pting | input-kcen | 67.1 ± 1.2 | 65.6 | 71.5 | 34.58 ± 3.00 |
| pting | input-lanjian | 68.4 ± 1.1 | 66.5 | 71.4 | 35.24 ± 3.05 |
| pting | input-mattcl | 68.8 ± 1.1 | 67.0 | 72.0 | 35.44 ± 3.06 |
| pting | input-pting | 69.9 ± 1.0 | 68.3 | 73.6 | 36.02 ± 3.10 |
| mattcl-py | input-kcen | 89.4 ± 0.9 | 87.2 | 91.0 | 46.06 ± 3.94 |
| mattcl-py | input-lanjian | 91.6 ± 1.3 | 89.2 | 94.9 | 47.20 ± 4.07 |
| mattcl-py | input-mattcl | 92.7 ± 1.5 | 90.5 | 96.9 | 47.77 ± 4.13 |
| mattcl-py | input-pting | 95.3 ± 1.3 | 93.1 | 97.8 | 49.10 ± 4.23 |
| kcen | input-kcen | 232.7 ± 4.1 | 227.4 | 239.4 | 119.86 ± 10.40 |
| kcen | input-pting | 237.4 ± 4.7 | 230.8 | 244.4 | 122.28 ± 10.66 |
| kcen | input-mattcl | 258.3 ± 5.0 | 248.8 | 265.7 | 133.05 ± 11.59 |
| kcen | input-lanjian | 269.5 ± 3.3 | 264.7 | 273.9 | 138.82 ± 11.92 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|