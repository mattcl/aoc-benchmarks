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
| mattcl | input-kcen | 1.3 ± 0.1 | 1.1 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.1 | 1.1 | 1.7 | 1.04 ± 0.16 |
| mattcl | input-pting | 1.4 ± 0.1 | 1.1 | 1.7 | 1.04 ± 0.16 |
| mattcl | input-mattcl | 1.4 ± 0.1 | 1.2 | 1.7 | 1.08 ± 0.16 |
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.4 | 1.39 ± 0.19 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.6 | 2.2 | 1.39 ± 0.18 |
| lanjian | input-mattcl | 1.8 ± 0.2 | 1.7 | 2.5 | 1.40 ± 0.20 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.7 | 2.5 | 1.55 ± 0.24 |
| pting | input-kcen | 65.8 ± 1.1 | 63.8 | 68.9 | 50.12 ± 5.72 |
| pting | input-lanjian | 67.2 ± 1.4 | 64.3 | 70.8 | 51.17 ± 5.88 |
| pting | input-mattcl | 67.5 ± 1.1 | 66.1 | 69.8 | 51.41 ± 5.86 |
| pting | input-pting | 68.4 ± 0.9 | 66.8 | 70.8 | 52.09 ± 5.92 |
| mattcl-py | input-kcen | 88.8 ± 1.3 | 86.3 | 92.4 | 67.61 ± 7.70 |
| mattcl-py | input-lanjian | 91.4 ± 0.8 | 90.1 | 93.0 | 69.58 ± 7.87 |
| mattcl-py | input-mattcl | 92.3 ± 1.3 | 90.0 | 95.4 | 70.24 ± 7.99 |
| mattcl-py | input-pting | 94.0 ± 1.3 | 91.9 | 96.9 | 71.58 ± 8.14 |
| kcen | input-kcen | 229.6 ± 4.5 | 221.4 | 236.8 | 174.75 ± 20.01 |
| kcen | input-pting | 233.3 ± 2.0 | 230.2 | 235.8 | 177.57 ± 20.09 |
| kcen | input-mattcl | 254.0 ± 7.5 | 245.3 | 264.8 | 193.39 ± 22.55 |
| kcen | input-lanjian | 268.8 ± 7.4 | 259.8 | 280.8 | 204.62 ± 23.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|