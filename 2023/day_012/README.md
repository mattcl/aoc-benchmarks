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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.1 | 1.9 | 1.00 |
| mattcl | input-pting | 1.4 ± 0.2 | 1.2 | 1.8 | 1.02 ± 0.17 |
| mattcl | input-mattcl | 1.5 ± 0.1 | 1.2 | 1.9 | 1.09 ± 0.18 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.2 | 1.8 | 1.10 ± 0.18 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.3 | 1.34 ± 0.19 |
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.4 | 1.34 ± 0.20 |
| lanjian | input-mattcl | 1.8 ± 0.1 | 1.7 | 2.3 | 1.34 ± 0.19 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.8 | 3.2 | 1.59 ± 0.26 |
| pting | input-kcen | 67.3 ± 1.0 | 65.5 | 70.3 | 49.62 ± 6.34 |
| pting | input-lanjian | 68.8 ± 1.3 | 67.0 | 72.6 | 50.71 ± 6.52 |
| pting | input-mattcl | 69.2 ± 1.1 | 67.2 | 72.0 | 51.00 ± 6.53 |
| pting | input-pting | 70.3 ± 1.4 | 67.2 | 73.6 | 51.83 ± 6.67 |
| mattcl-py | input-kcen | 90.7 ± 1.2 | 88.4 | 92.9 | 66.86 ± 8.54 |
| mattcl-py | input-lanjian | 93.6 ± 1.4 | 91.5 | 97.7 | 68.97 ± 8.83 |
| mattcl-py | input-mattcl | 94.0 ± 1.6 | 90.7 | 98.7 | 69.32 ± 8.89 |
| mattcl-py | input-pting | 96.6 ± 1.8 | 93.8 | 101.5 | 71.24 ± 9.15 |
| kcen | input-kcen | 229.6 ± 3.1 | 224.3 | 235.6 | 169.27 ± 21.63 |
| kcen | input-pting | 237.8 ± 6.0 | 229.9 | 251.6 | 175.29 ± 22.71 |
| kcen | input-mattcl | 256.8 ± 7.7 | 246.4 | 267.1 | 189.29 ± 24.71 |
| kcen | input-lanjian | 271.4 ± 4.8 | 263.1 | 277.9 | 200.03 ± 25.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|