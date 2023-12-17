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
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.9 ± 0.2 | 1.7 | 2.6 | 1.04 ± 0.13 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.6 | 1.09 ± 0.13 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.7 | 2.6 | 1.09 ± 0.15 |
| mattcl | input-kcen | 2.4 ± 0.2 | 2.0 | 3.7 | 1.29 ± 0.15 |
| mattcl | input-mattcl | 2.5 ± 0.2 | 2.0 | 3.6 | 1.32 ± 0.15 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.0 | 3.4 | 1.32 ± 0.14 |
| mattcl | input-pting | 2.5 ± 0.3 | 2.1 | 4.8 | 1.36 ± 0.18 |
| pting | input-kcen | 66.5 ± 0.9 | 64.8 | 68.6 | 35.71 ± 2.58 |
| pting | input-lanjian | 67.6 ± 1.0 | 65.8 | 69.6 | 36.27 ± 2.62 |
| pting | input-mattcl | 68.3 ± 1.0 | 66.6 | 70.4 | 36.68 ± 2.66 |
| pting | input-pting | 69.1 ± 0.9 | 67.3 | 71.2 | 37.09 ± 2.67 |
| mattcl-py | input-kcen | 89.3 ± 1.5 | 86.7 | 93.8 | 47.96 ± 3.49 |
| mattcl-py | input-lanjian | 90.9 ± 0.9 | 89.1 | 92.3 | 48.77 ± 3.49 |
| mattcl-py | input-mattcl | 91.8 ± 1.4 | 89.6 | 96.0 | 49.28 ± 3.57 |
| mattcl-py | input-pting | 94.2 ± 1.3 | 92.2 | 97.1 | 50.55 ± 3.65 |
| kcen | input-kcen | 231.3 ± 4.9 | 225.7 | 240.2 | 124.19 ± 9.18 |
| kcen | input-pting | 234.8 ± 2.5 | 230.5 | 239.4 | 126.06 ± 9.03 |
| kcen | input-mattcl | 255.7 ± 4.3 | 247.0 | 263.6 | 137.23 ± 10.00 |
| kcen | input-lanjian | 267.5 ± 4.5 | 260.3 | 274.2 | 143.62 ± 10.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|