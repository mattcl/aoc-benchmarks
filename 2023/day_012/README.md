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
| lanjian | input-lanjian | 1.9 ± 0.3 | 1.6 | 4.8 | 1.08 ± 0.19 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.6 | 1.12 ± 0.13 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.6 | 1.17 ± 0.14 |
| mattcl | input-kcen | 2.4 ± 0.2 | 2.0 | 3.6 | 1.35 ± 0.15 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.1 | 3.6 | 1.38 ± 0.16 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.1 | 3.1 | 1.39 ± 0.14 |
| mattcl | input-mattcl | 2.5 ± 0.3 | 2.0 | 5.0 | 1.40 ± 0.20 |
| pting | input-kcen | 67.0 ± 0.9 | 64.2 | 68.8 | 37.42 ± 2.54 |
| pting | input-lanjian | 68.1 ± 1.1 | 66.0 | 70.7 | 38.04 ± 2.61 |
| pting | input-mattcl | 68.7 ± 1.0 | 66.7 | 70.9 | 38.39 ± 2.62 |
| pting | input-pting | 70.2 ± 1.0 | 67.6 | 72.1 | 39.23 ± 2.68 |
| mattcl-py | input-kcen | 89.9 ± 1.1 | 87.7 | 92.0 | 50.25 ± 3.40 |
| mattcl-py | input-lanjian | 91.3 ± 1.1 | 89.4 | 93.0 | 51.05 ± 3.45 |
| mattcl-py | input-mattcl | 92.4 ± 1.4 | 90.1 | 96.0 | 51.65 ± 3.52 |
| mattcl-py | input-pting | 95.1 ± 1.3 | 92.7 | 99.2 | 53.14 ± 3.62 |
| kcen | input-kcen | 231.3 ± 4.2 | 226.9 | 242.5 | 129.29 ± 8.92 |
| kcen | input-pting | 239.4 ± 5.4 | 232.8 | 248.2 | 133.82 ± 9.42 |
| kcen | input-mattcl | 256.0 ± 8.4 | 244.6 | 276.5 | 143.07 ± 10.62 |
| kcen | input-lanjian | 272.6 ± 5.8 | 265.0 | 280.2 | 152.34 ± 10.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|