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
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.5 | 1.00 ± 0.08 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.7 | 1.12 ± 0.12 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 2.6 | 1.18 ± 0.13 |
| mattcl | input-kcen | 2.5 ± 0.2 | 2.0 | 4.2 | 1.34 ± 0.15 |
| mattcl | input-mattcl | 2.5 ± 0.3 | 2.0 | 3.8 | 1.35 ± 0.16 |
| mattcl | input-lanjian | 2.5 ± 0.3 | 2.0 | 5.9 | 1.36 ± 0.19 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.1 | 3.2 | 1.37 ± 0.13 |
| pting | input-kcen | 67.6 ± 1.0 | 65.0 | 69.7 | 36.61 ± 2.18 |
| pting | input-lanjian | 68.6 ± 1.2 | 66.6 | 71.6 | 37.16 ± 2.23 |
| pting | input-mattcl | 69.2 ± 1.3 | 66.6 | 71.8 | 37.46 ± 2.26 |
| pting | input-pting | 70.1 ± 1.0 | 68.1 | 72.4 | 37.96 ± 2.25 |
| mattcl-py | input-kcen | 90.0 ± 1.4 | 87.5 | 92.7 | 48.74 ± 2.91 |
| mattcl-py | input-lanjian | 92.2 ± 1.4 | 89.5 | 95.6 | 49.91 ± 2.97 |
| mattcl-py | input-mattcl | 92.9 ± 1.2 | 90.5 | 95.3 | 50.29 ± 2.96 |
| mattcl-py | input-pting | 95.4 ± 1.3 | 92.7 | 97.7 | 51.68 ± 3.05 |
| kcen | input-kcen | 235.0 ± 4.5 | 226.5 | 240.9 | 127.26 ± 7.72 |
| kcen | input-pting | 237.5 ± 3.2 | 232.3 | 244.8 | 128.63 ± 7.61 |
| kcen | input-mattcl | 257.2 ± 8.7 | 245.8 | 271.1 | 139.30 ± 9.30 |
| kcen | input-lanjian | 270.8 ± 6.1 | 265.0 | 284.3 | 146.70 ± 9.07 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|