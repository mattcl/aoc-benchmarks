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
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.4 | 1.00 |
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.8 | 2.5 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 3.9 | 1.13 ± 0.15 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 2.7 | 1.17 ± 0.13 |
| mattcl | input-kcen | 2.5 ± 0.2 | 2.0 | 3.8 | 1.32 ± 0.14 |
| mattcl | input-mattcl | 2.6 ± 0.2 | 2.1 | 3.2 | 1.35 ± 0.14 |
| mattcl | input-lanjian | 2.6 ± 0.2 | 2.1 | 4.1 | 1.37 ± 0.15 |
| mattcl | input-pting | 2.6 ± 0.3 | 2.1 | 4.8 | 1.37 ± 0.18 |
| pting | input-kcen | 67.6 ± 1.1 | 65.6 | 71.3 | 35.62 ± 2.43 |
| pting | input-lanjian | 68.5 ± 0.9 | 66.7 | 70.8 | 36.10 ± 2.45 |
| pting | input-mattcl | 68.8 ± 0.9 | 67.2 | 70.5 | 36.25 ± 2.46 |
| pting | input-pting | 71.7 ± 5.2 | 68.7 | 103.4 | 37.80 ± 3.74 |
| mattcl-py | input-kcen | 90.0 ± 1.3 | 88.0 | 94.6 | 47.42 ± 3.23 |
| mattcl-py | input-lanjian | 92.1 ± 1.0 | 89.7 | 93.6 | 48.54 ± 3.27 |
| mattcl-py | input-mattcl | 93.1 ± 1.6 | 90.2 | 96.8 | 49.08 ± 3.37 |
| mattcl-py | input-pting | 95.5 ± 1.4 | 93.3 | 99.3 | 50.31 ± 3.43 |
| kcen | input-kcen | 233.6 ± 3.5 | 226.0 | 237.1 | 123.13 ± 8.40 |
| kcen | input-pting | 238.0 ± 4.4 | 231.2 | 245.7 | 125.46 ± 8.66 |
| kcen | input-mattcl | 257.6 ± 7.5 | 248.0 | 268.3 | 135.78 ± 9.87 |
| kcen | input-lanjian | 271.5 ± 6.0 | 262.4 | 282.6 | 143.12 ± 10.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|