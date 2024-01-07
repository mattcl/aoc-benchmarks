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
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.4 | 1.00 |
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.4 | 1.00 ± 0.10 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.5 | 1.11 ± 0.13 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.7 | 2.6 | 1.13 ± 0.13 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.7 | 2.6 | 1.17 ± 0.14 |
| mattcl | input-mattcl | 2.1 ± 0.3 | 1.8 | 4.1 | 1.19 ± 0.17 |
| mattcl | input-pting | 2.1 ± 0.2 | 1.8 | 2.7 | 1.19 ± 0.14 |
| mattcl | input-lanjian | 2.2 ± 0.2 | 1.9 | 2.6 | 1.21 ± 0.14 |
| pting | input-kcen | 66.4 ± 1.0 | 64.4 | 68.3 | 36.78 ± 2.40 |
| pting | input-lanjian | 67.7 ± 1.2 | 65.7 | 71.1 | 37.52 ± 2.48 |
| pting | input-mattcl | 68.3 ± 1.5 | 66.3 | 72.7 | 37.85 ± 2.54 |
| pting | input-pting | 69.6 ± 0.9 | 68.2 | 72.5 | 38.53 ± 2.51 |
| mattcl-py | input-kcen | 90.3 ± 1.7 | 88.0 | 94.8 | 50.03 ± 3.32 |
| mattcl-py | input-lanjian | 92.4 ± 1.3 | 90.3 | 94.7 | 51.17 ± 3.33 |
| mattcl-py | input-mattcl | 92.5 ± 1.4 | 90.4 | 96.8 | 51.22 ± 3.34 |
| mattcl-py | input-pting | 95.1 ± 1.2 | 92.6 | 99.0 | 52.65 ± 3.42 |
| kcen | input-kcen | 232.5 ± 3.3 | 226.5 | 238.9 | 128.77 ± 8.39 |
| kcen | input-pting | 234.6 ± 3.7 | 227.3 | 241.8 | 129.94 ± 8.52 |
| kcen | input-mattcl | 253.4 ± 5.0 | 244.8 | 261.8 | 140.37 ± 9.35 |
| kcen | input-lanjian | 266.9 ± 7.8 | 258.3 | 277.5 | 147.83 ± 10.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|