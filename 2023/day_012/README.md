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
| lanjian | input-kcen | 1.8 ± 0.2 | 1.6 | 2.3 | 1.00 |
| lanjian | input-mattcl | 1.8 ± 0.1 | 1.6 | 2.4 | 1.00 ± 0.12 |
| lanjian | input-pting | 1.8 ± 0.2 | 1.7 | 2.6 | 1.04 ± 0.13 |
| lanjian | input-lanjian | 2.0 ± 3.6 | 1.6 | 53.3 | 1.15 ± 2.05 |
| mattcl | input-kcen | 2.3 ± 0.2 | 1.9 | 3.8 | 1.32 ± 0.18 |
| mattcl | input-mattcl | 2.4 ± 0.2 | 2.0 | 3.1 | 1.37 ± 0.17 |
| mattcl | input-pting | 2.4 ± 0.2 | 2.0 | 3.7 | 1.37 ± 0.18 |
| mattcl | input-lanjian | 2.7 ± 4.3 | 2.0 | 62.9 | 1.53 ± 2.41 |
| pting | input-kcen | 67.0 ± 1.1 | 65.1 | 70.1 | 37.61 ± 3.32 |
| pting | input-lanjian | 67.9 ± 0.9 | 66.4 | 70.0 | 38.15 ± 3.35 |
| pting | input-mattcl | 68.4 ± 1.1 | 66.8 | 71.3 | 38.40 ± 3.39 |
| pting | input-pting | 69.0 ± 1.1 | 67.3 | 71.3 | 38.73 ± 3.41 |
| mattcl-py | input-kcen | 89.4 ± 1.3 | 87.7 | 93.9 | 50.19 ± 4.42 |
| mattcl-py | input-mattcl | 91.6 ± 1.2 | 89.3 | 95.1 | 51.47 ± 4.51 |
| mattcl-py | input-lanjian | 94.0 ± 11.3 | 89.8 | 149.2 | 52.80 ± 7.84 |
| mattcl-py | input-pting | 94.2 ± 1.3 | 92.4 | 98.0 | 52.90 ± 4.65 |
| kcen | input-kcen | 232.7 ± 4.0 | 227.1 | 242.3 | 130.69 ± 11.55 |
| kcen | input-pting | 236.1 ± 5.3 | 230.8 | 246.5 | 132.60 ± 11.88 |
| kcen | input-mattcl | 255.6 ± 7.5 | 246.5 | 266.9 | 143.57 ± 13.14 |
| kcen | input-lanjian | 273.0 ± 8.4 | 262.0 | 284.5 | 153.35 ± 14.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|