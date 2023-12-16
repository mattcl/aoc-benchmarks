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
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.7 | 2.3 | 1.00 |
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.3 | 1.00 ± 0.10 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.8 | 2.6 | 1.08 ± 0.14 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.6 | 1.10 ± 0.13 |
| mattcl | input-kcen | 2.4 ± 0.2 | 2.0 | 3.4 | 1.30 ± 0.15 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.0 | 3.0 | 1.32 ± 0.13 |
| mattcl | input-mattcl | 2.5 ± 0.2 | 2.1 | 3.4 | 1.32 ± 0.14 |
| mattcl | input-pting | 2.5 ± 0.3 | 2.1 | 4.9 | 1.35 ± 0.17 |
| pting | input-kcen | 66.5 ± 0.8 | 64.9 | 69.3 | 35.55 ± 2.32 |
| pting | input-lanjian | 68.0 ± 1.0 | 66.1 | 71.2 | 36.33 ± 2.39 |
| pting | input-mattcl | 68.5 ± 1.2 | 66.7 | 73.1 | 36.59 ± 2.43 |
| pting | input-pting | 69.2 ± 1.0 | 67.8 | 72.1 | 36.98 ± 2.42 |
| mattcl-py | input-kcen | 89.2 ± 1.1 | 87.4 | 91.6 | 47.69 ± 3.11 |
| mattcl-py | input-lanjian | 91.6 ± 1.6 | 89.5 | 95.2 | 48.97 ± 3.25 |
| mattcl-py | input-mattcl | 92.1 ± 1.3 | 90.3 | 95.5 | 49.21 ± 3.22 |
| mattcl-py | input-pting | 94.0 ± 1.0 | 91.7 | 96.4 | 50.25 ± 3.26 |
| kcen | input-kcen | 230.7 ± 4.9 | 224.8 | 242.1 | 123.29 ± 8.32 |
| kcen | input-pting | 235.1 ± 6.4 | 227.0 | 249.6 | 125.63 ± 8.75 |
| kcen | input-mattcl | 252.8 ± 6.8 | 244.1 | 267.3 | 135.09 ± 9.38 |
| kcen | input-lanjian | 269.5 ± 5.3 | 261.9 | 275.4 | 144.05 ± 9.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|