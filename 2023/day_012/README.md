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
| mattcl | input-kcen | 1.3 ± 0.2 | 1.1 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 1.8 | 1.05 ± 0.17 |
| mattcl | input-pting | 1.4 ± 0.1 | 1.1 | 1.8 | 1.07 ± 0.17 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.2 | 1.8 | 1.08 ± 0.17 |
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.2 | 1.37 ± 0.18 |
| lanjian | input-lanjian | 1.9 ± 0.2 | 1.7 | 2.5 | 1.44 ± 0.22 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.6 | 1.55 ± 0.24 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.8 | 2.7 | 1.62 ± 0.25 |
| pting | input-kcen | 67.7 ± 1.2 | 65.7 | 70.4 | 50.71 ± 6.02 |
| pting | input-lanjian | 68.6 ± 1.0 | 66.8 | 70.9 | 51.41 ± 6.09 |
| pting | input-mattcl | 68.8 ± 1.3 | 66.5 | 73.1 | 51.51 ± 6.14 |
| pting | input-pting | 70.5 ± 1.2 | 68.5 | 75.0 | 52.78 ± 6.27 |
| mattcl-py | input-kcen | 91.1 ± 1.2 | 89.3 | 93.7 | 68.20 ± 8.07 |
| mattcl-py | input-lanjian | 93.4 ± 1.1 | 91.1 | 95.7 | 69.93 ± 8.26 |
| mattcl-py | input-mattcl | 93.7 ± 1.4 | 91.2 | 96.9 | 70.21 ± 8.32 |
| mattcl-py | input-pting | 96.9 ± 1.6 | 93.3 | 100.1 | 72.56 ± 8.61 |
| kcen | input-kcen | 232.6 ± 3.9 | 226.4 | 237.7 | 174.20 ± 20.68 |
| kcen | input-pting | 236.4 ± 4.3 | 230.6 | 247.6 | 177.08 ± 21.05 |
| kcen | input-mattcl | 260.6 ± 5.5 | 252.5 | 270.1 | 195.20 ± 23.31 |
| kcen | input-lanjian | 270.3 ± 6.5 | 262.3 | 282.8 | 202.43 ± 24.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|