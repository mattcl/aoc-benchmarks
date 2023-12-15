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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.4 | 1.01 ± 0.10 |
| lanjian | input-mattcl | 1.9 ± 0.2 | 1.7 | 2.6 | 1.05 ± 0.14 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.7 | 2.6 | 1.08 ± 0.16 |
| mattcl | input-kcen | 2.4 ± 0.3 | 2.0 | 4.9 | 1.32 ± 0.20 |
| mattcl | input-lanjian | 2.4 ± 0.3 | 2.0 | 4.6 | 1.35 ± 0.20 |
| mattcl | input-mattcl | 2.5 ± 0.2 | 2.0 | 3.9 | 1.36 ± 0.17 |
| mattcl | input-pting | 2.5 ± 0.3 | 2.0 | 5.7 | 1.36 ± 0.20 |
| pting | input-lanjian | 67.9 ± 1.8 | 65.6 | 76.9 | 37.42 ± 2.99 |
| pting | input-kcen | 68.0 ± 5.7 | 65.3 | 94.8 | 37.48 ± 4.21 |
| pting | input-mattcl | 68.3 ± 1.2 | 66.6 | 73.5 | 37.68 ± 2.90 |
| pting | input-pting | 69.6 ± 1.1 | 67.7 | 72.5 | 38.35 ± 2.94 |
| mattcl-py | input-kcen | 89.0 ± 1.4 | 86.8 | 91.7 | 49.10 ± 3.77 |
| mattcl-py | input-lanjian | 91.2 ± 0.9 | 89.4 | 93.2 | 50.27 ± 3.81 |
| mattcl-py | input-mattcl | 91.8 ± 1.3 | 89.8 | 94.7 | 50.60 ± 3.86 |
| mattcl-py | input-pting | 94.1 ± 1.4 | 91.9 | 98.8 | 51.87 ± 3.97 |
| kcen | input-kcen | 233.7 ± 3.1 | 227.0 | 238.9 | 128.88 ± 9.82 |
| kcen | input-pting | 234.5 ± 3.2 | 231.5 | 242.6 | 129.32 ± 9.87 |
| kcen | input-mattcl | 257.6 ± 5.3 | 244.8 | 265.0 | 142.04 ± 11.05 |
| kcen | input-lanjian | 273.1 ± 6.9 | 262.4 | 280.6 | 150.57 ± 11.92 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|