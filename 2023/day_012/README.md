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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.2 | 1.00 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.4 | 1.00 ± 0.10 |
| lanjian | input-mattcl | 1.9 ± 0.2 | 1.7 | 2.4 | 1.02 ± 0.12 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.7 | 2.7 | 1.11 ± 0.15 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.8 | 2.5 | 1.12 ± 0.13 |
| mattcl | input-pting | 2.2 ± 0.2 | 1.8 | 2.9 | 1.17 ± 0.15 |
| mattcl | input-lanjian | 2.2 ± 0.2 | 1.9 | 2.7 | 1.19 ± 0.14 |
| mattcl | input-mattcl | 2.3 ± 0.4 | 1.9 | 6.3 | 1.24 ± 0.23 |
| pting | input-kcen | 66.4 ± 1.0 | 64.6 | 69.4 | 36.14 ± 2.79 |
| pting | input-lanjian | 67.8 ± 1.2 | 66.3 | 72.2 | 36.87 ± 2.87 |
| pting | input-mattcl | 68.4 ± 1.2 | 66.5 | 72.5 | 37.21 ± 2.90 |
| pting | input-pting | 69.2 ± 1.0 | 67.2 | 72.3 | 37.68 ± 2.91 |
| mattcl-py | input-kcen | 89.7 ± 1.5 | 87.3 | 93.6 | 48.81 ± 3.78 |
| mattcl-py | input-lanjian | 92.0 ± 1.0 | 89.8 | 94.2 | 50.06 ± 3.84 |
| mattcl-py | input-mattcl | 92.4 ± 1.1 | 90.1 | 95.1 | 50.28 ± 3.86 |
| mattcl-py | input-pting | 94.6 ± 1.0 | 92.7 | 96.9 | 51.50 ± 3.95 |
| kcen | input-kcen | 228.8 ± 4.7 | 223.0 | 239.4 | 124.50 ± 9.78 |
| kcen | input-pting | 236.5 ± 4.4 | 232.2 | 243.5 | 128.69 ± 10.04 |
| kcen | input-mattcl | 255.0 ± 4.0 | 248.8 | 264.0 | 138.77 ± 10.74 |
| kcen | input-lanjian | 267.7 ± 4.9 | 260.9 | 277.4 | 145.70 ± 11.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|