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
| mattcl | input-kcen | 1.3 ± 0.2 | 1.1 | 1.8 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.2 | 1.1 | 1.8 | 1.04 ± 0.18 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 1.7 | 1.05 ± 0.18 |
| mattcl | input-lanjian | 1.4 ± 0.1 | 1.1 | 1.7 | 1.06 ± 0.18 |
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.2 | 1.41 ± 0.21 |
| lanjian | input-lanjian | 1.9 ± 0.2 | 1.7 | 2.5 | 1.50 ± 0.24 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.4 | 1.55 ± 0.24 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.7 | 1.63 ± 0.26 |
| pting | input-kcen | 67.0 ± 1.1 | 64.8 | 70.2 | 51.79 ± 6.65 |
| pting | input-lanjian | 67.9 ± 1.1 | 65.8 | 70.9 | 52.51 ± 6.74 |
| pting | input-mattcl | 68.7 ± 1.4 | 66.1 | 71.3 | 53.12 ± 6.84 |
| pting | input-pting | 69.8 ± 1.0 | 67.5 | 71.8 | 53.99 ± 6.92 |
| mattcl-py | input-kcen | 90.3 ± 1.0 | 88.4 | 93.1 | 69.84 ± 8.93 |
| mattcl-py | input-lanjian | 92.8 ± 1.1 | 91.0 | 95.7 | 71.75 ± 9.18 |
| mattcl-py | input-mattcl | 93.1 ± 1.2 | 90.6 | 95.5 | 71.96 ± 9.21 |
| mattcl-py | input-pting | 96.0 ± 1.2 | 93.2 | 98.6 | 74.19 ± 9.49 |
| kcen | input-kcen | 230.7 ± 4.3 | 225.1 | 239.6 | 178.35 ± 22.96 |
| kcen | input-pting | 239.3 ± 4.6 | 232.3 | 249.2 | 184.97 ± 23.82 |
| kcen | input-mattcl | 255.0 ± 5.9 | 247.8 | 268.0 | 197.13 ± 25.51 |
| kcen | input-lanjian | 273.1 ± 7.3 | 263.4 | 285.1 | 211.08 ± 27.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|