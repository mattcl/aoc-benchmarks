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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.2 | 1.00 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.6 | 2.3 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.5 | 1.12 ± 0.13 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.6 | 1.18 ± 0.14 |
| mattcl | input-kcen | 2.4 ± 0.3 | 1.9 | 5.1 | 1.33 ± 0.20 |
| mattcl | input-mattcl | 2.4 ± 0.2 | 2.0 | 3.7 | 1.36 ± 0.16 |
| mattcl | input-lanjian | 2.5 ± 0.3 | 2.0 | 5.9 | 1.37 ± 0.21 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.0 | 3.2 | 1.38 ± 0.15 |
| pting | input-kcen | 67.6 ± 1.4 | 65.6 | 71.0 | 37.68 ± 2.76 |
| pting | input-mattcl | 69.1 ± 1.2 | 67.0 | 72.3 | 38.52 ± 2.79 |
| pting | input-lanjian | 70.2 ± 3.9 | 66.3 | 89.7 | 39.12 ± 3.51 |
| pting | input-pting | 70.7 ± 1.1 | 68.8 | 74.0 | 39.38 ± 2.83 |
| mattcl-py | input-kcen | 90.4 ± 1.6 | 87.6 | 95.0 | 50.40 ± 3.66 |
| mattcl-py | input-lanjian | 92.4 ± 1.7 | 89.5 | 95.8 | 51.49 ± 3.74 |
| mattcl-py | input-mattcl | 92.9 ± 1.3 | 90.8 | 96.3 | 51.75 ± 3.71 |
| mattcl-py | input-pting | 95.5 ± 1.1 | 93.1 | 97.5 | 53.23 ± 3.80 |
| kcen | input-kcen | 231.4 ± 4.3 | 226.3 | 238.0 | 128.98 ± 9.38 |
| kcen | input-pting | 241.6 ± 16.1 | 231.9 | 291.7 | 134.68 ± 13.05 |
| kcen | input-mattcl | 261.4 ± 6.6 | 252.4 | 276.1 | 145.72 ± 10.88 |
| kcen | input-lanjian | 272.8 ± 5.6 | 264.4 | 284.1 | 152.06 ± 11.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|