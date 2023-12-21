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
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.2 | 1.00 |
| lanjian | input-lanjian | 2.0 ± 0.2 | 1.8 | 2.6 | 1.07 ± 0.13 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.6 | 1.11 ± 0.12 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 2.6 | 1.17 ± 0.13 |
| mattcl | input-kcen | 2.5 ± 0.2 | 2.1 | 2.9 | 1.32 ± 0.13 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.1 | 3.2 | 1.35 ± 0.13 |
| mattcl | input-mattcl | 2.5 ± 0.3 | 2.1 | 5.0 | 1.36 ± 0.17 |
| mattcl | input-pting | 2.6 ± 0.3 | 2.1 | 4.1 | 1.39 ± 0.17 |
| pting | input-kcen | 68.4 ± 6.6 | 65.7 | 110.6 | 36.50 ± 4.11 |
| pting | input-lanjian | 68.9 ± 1.2 | 67.1 | 73.0 | 36.75 ± 2.25 |
| pting | input-mattcl | 69.1 ± 1.4 | 66.3 | 73.8 | 36.90 ± 2.29 |
| pting | input-pting | 70.3 ± 1.3 | 68.3 | 73.8 | 37.50 ± 2.30 |
| mattcl-py | input-kcen | 90.3 ± 1.1 | 88.0 | 93.3 | 48.20 ± 2.88 |
| mattcl-py | input-lanjian | 91.5 ± 1.0 | 89.7 | 93.6 | 48.86 ± 2.91 |
| mattcl-py | input-mattcl | 92.6 ± 1.4 | 90.2 | 95.8 | 49.43 ± 2.99 |
| mattcl-py | input-pting | 95.3 ± 1.3 | 92.7 | 98.5 | 50.85 ± 3.05 |
| kcen | input-kcen | 233.7 ± 4.9 | 227.5 | 243.7 | 124.77 ± 7.76 |
| kcen | input-pting | 238.0 ± 3.2 | 234.2 | 243.7 | 127.03 ± 7.63 |
| kcen | input-mattcl | 257.4 ± 5.3 | 249.9 | 265.8 | 137.40 ± 8.52 |
| kcen | input-lanjian | 275.7 ± 6.6 | 264.8 | 285.3 | 147.16 ± 9.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|