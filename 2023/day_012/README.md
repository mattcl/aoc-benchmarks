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
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.3 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.6 | 1.10 ± 0.12 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.6 | 1.11 ± 0.13 |
| mattcl | input-kcen | 2.5 ± 0.4 | 2.0 | 5.0 | 1.30 ± 0.20 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.1 | 4.1 | 1.32 ± 0.14 |
| mattcl | input-mattcl | 2.5 ± 0.3 | 2.1 | 4.4 | 1.34 ± 0.16 |
| mattcl | input-pting | 2.5 ± 0.3 | 2.1 | 4.8 | 1.34 ± 0.18 |
| pting | input-kcen | 66.8 ± 0.8 | 65.3 | 69.4 | 35.18 ± 2.13 |
| pting | input-mattcl | 68.3 ± 1.0 | 66.3 | 71.2 | 35.98 ± 2.20 |
| pting | input-lanjian | 68.7 ± 4.8 | 66.5 | 94.2 | 36.21 ± 3.32 |
| pting | input-pting | 69.4 ± 1.3 | 66.8 | 74.1 | 36.55 ± 2.26 |
| mattcl-py | input-kcen | 90.7 ± 5.7 | 86.9 | 121.7 | 47.78 ± 4.12 |
| mattcl-py | input-lanjian | 91.4 ± 1.3 | 89.7 | 95.6 | 48.14 ± 2.93 |
| mattcl-py | input-mattcl | 92.0 ± 1.2 | 89.8 | 95.0 | 48.46 ± 2.94 |
| mattcl-py | input-pting | 94.2 ± 1.5 | 91.3 | 97.8 | 49.64 ± 3.04 |
| kcen | input-kcen | 231.8 ± 3.9 | 225.1 | 236.7 | 122.14 ± 7.52 |
| kcen | input-pting | 235.2 ± 3.8 | 231.4 | 246.1 | 123.94 ± 7.61 |
| kcen | input-mattcl | 259.3 ± 7.2 | 250.0 | 270.2 | 136.64 ± 8.94 |
| kcen | input-lanjian | 270.0 ± 6.0 | 263.5 | 284.7 | 142.28 ± 9.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|