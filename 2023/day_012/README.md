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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.9 ± 0.2 | 1.6 | 2.4 | 1.07 ± 0.14 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.8 | 2.5 | 1.12 ± 0.13 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.5 | 1.19 ± 0.14 |
| mattcl | input-kcen | 2.4 ± 0.2 | 1.9 | 3.8 | 1.35 ± 0.15 |
| mattcl | input-lanjian | 2.4 ± 0.3 | 1.9 | 5.5 | 1.36 ± 0.19 |
| mattcl | input-mattcl | 2.5 ± 0.3 | 2.0 | 4.0 | 1.37 ± 0.17 |
| mattcl | input-pting | 2.5 ± 0.3 | 2.0 | 4.9 | 1.39 ± 0.19 |
| pting | input-kcen | 67.1 ± 0.8 | 65.7 | 68.7 | 37.42 ± 2.35 |
| pting | input-lanjian | 68.2 ± 1.0 | 66.1 | 70.6 | 38.01 ± 2.40 |
| pting | input-mattcl | 68.7 ± 1.0 | 66.8 | 71.0 | 38.32 ± 2.43 |
| pting | input-pting | 70.3 ± 1.2 | 67.6 | 72.8 | 39.22 ± 2.50 |
| mattcl-py | input-lanjian | 91.3 ± 1.5 | 88.8 | 95.3 | 50.89 ± 3.25 |
| mattcl-py | input-mattcl | 92.3 ± 1.4 | 90.0 | 95.2 | 51.50 ± 3.27 |
| mattcl-py | input-kcen | 92.7 ± 11.8 | 88.0 | 157.5 | 51.69 ± 7.29 |
| mattcl-py | input-pting | 95.3 ± 1.6 | 93.1 | 100.1 | 53.14 ± 3.39 |
| kcen | input-kcen | 232.4 ± 5.9 | 224.8 | 244.1 | 129.58 ± 8.64 |
| kcen | input-pting | 237.9 ± 3.8 | 232.7 | 244.6 | 132.64 ± 8.44 |
| kcen | input-mattcl | 259.5 ± 6.5 | 250.2 | 274.1 | 144.72 ± 9.62 |
| kcen | input-lanjian | 268.4 ± 4.5 | 262.1 | 275.2 | 149.70 ± 9.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|