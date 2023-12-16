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
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.8 | 2.4 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.7 | 1.11 ± 0.13 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 2.7 | 1.17 ± 0.14 |
| mattcl | input-kcen | 2.5 ± 0.2 | 2.1 | 3.5 | 1.30 ± 0.14 |
| mattcl | input-mattcl | 2.5 ± 0.2 | 2.1 | 3.4 | 1.33 ± 0.14 |
| mattcl | input-pting | 2.6 ± 0.3 | 2.2 | 5.4 | 1.35 ± 0.18 |
| mattcl | input-lanjian | 2.6 ± 0.2 | 2.1 | 4.0 | 1.35 ± 0.15 |
| pting | input-kcen | 67.5 ± 1.0 | 65.5 | 70.1 | 35.47 ± 2.43 |
| pting | input-lanjian | 68.6 ± 1.1 | 66.6 | 71.5 | 36.06 ± 2.47 |
| pting | input-mattcl | 69.0 ± 1.1 | 67.0 | 71.8 | 36.29 ± 2.49 |
| pting | input-pting | 70.5 ± 1.2 | 68.7 | 74.4 | 37.05 ± 2.55 |
| mattcl-py | input-kcen | 90.4 ± 1.5 | 88.1 | 94.1 | 47.54 ± 3.27 |
| mattcl-py | input-lanjian | 92.2 ± 1.3 | 89.3 | 95.0 | 48.50 ± 3.30 |
| mattcl-py | input-mattcl | 92.7 ± 1.2 | 90.1 | 95.0 | 48.74 ± 3.32 |
| mattcl-py | input-pting | 95.6 ± 1.3 | 93.9 | 98.5 | 50.24 ± 3.42 |
| kcen | input-kcen | 233.9 ± 6.1 | 227.0 | 249.1 | 123.00 ± 8.81 |
| kcen | input-pting | 235.6 ± 3.5 | 231.5 | 241.3 | 123.88 ± 8.48 |
| kcen | input-mattcl | 257.5 ± 7.1 | 250.7 | 274.6 | 135.39 ± 9.79 |
| kcen | input-lanjian | 271.7 ± 6.1 | 265.0 | 283.1 | 142.88 ± 10.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|