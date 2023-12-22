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
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.7 | 2.2 | 1.00 |
| lanjian | input-kcen | 1.9 ± 0.2 | 1.7 | 2.5 | 1.00 ± 0.10 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.8 | 2.7 | 1.09 ± 0.12 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.6 | 1.14 ± 0.13 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.1 | 3.7 | 1.34 ± 0.15 |
| mattcl | input-mattcl | 2.5 ± 0.2 | 2.0 | 4.0 | 1.34 ± 0.15 |
| mattcl | input-kcen | 2.5 ± 0.3 | 2.0 | 4.4 | 1.34 ± 0.19 |
| mattcl | input-pting | 2.5 ± 0.3 | 2.1 | 5.0 | 1.35 ± 0.18 |
| pting | input-kcen | 66.4 ± 1.0 | 64.8 | 69.4 | 35.66 ± 2.23 |
| pting | input-lanjian | 67.5 ± 1.0 | 65.9 | 70.5 | 36.25 ± 2.27 |
| pting | input-mattcl | 67.8 ± 1.0 | 65.6 | 70.2 | 36.41 ± 2.28 |
| pting | input-pting | 70.7 ± 7.9 | 67.2 | 120.3 | 37.95 ± 4.85 |
| mattcl-py | input-kcen | 88.4 ± 0.9 | 86.7 | 90.2 | 47.49 ± 2.92 |
| mattcl-py | input-mattcl | 91.2 ± 1.0 | 89.4 | 93.2 | 48.98 ± 3.02 |
| mattcl-py | input-lanjian | 91.3 ± 1.3 | 89.5 | 94.6 | 49.03 ± 3.06 |
| mattcl-py | input-pting | 94.1 ± 1.5 | 91.6 | 97.0 | 50.53 ± 3.17 |
| kcen | input-kcen | 231.9 ± 2.8 | 224.8 | 236.3 | 124.55 ± 7.70 |
| kcen | input-pting | 232.9 ± 2.1 | 229.7 | 237.8 | 125.05 ± 7.66 |
| kcen | input-mattcl | 251.0 ± 6.1 | 244.1 | 265.3 | 134.79 ± 8.80 |
| kcen | input-lanjian | 272.1 ± 6.1 | 264.1 | 280.0 | 146.12 ± 9.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|