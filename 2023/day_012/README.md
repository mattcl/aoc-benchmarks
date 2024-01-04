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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.2 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.6 | 1.11 ± 0.14 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.6 | 2.7 | 1.12 ± 0.16 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.8 | 2.6 | 1.13 ± 0.14 |
| mattcl | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.6 | 1.18 ± 0.14 |
| mattcl | input-pting | 2.2 ± 0.2 | 1.8 | 2.7 | 1.21 ± 0.15 |
| mattcl | input-lanjian | 2.2 ± 0.2 | 1.9 | 2.8 | 1.22 ± 0.15 |
| pting | input-kcen | 66.2 ± 1.2 | 64.2 | 69.4 | 36.57 ± 2.83 |
| pting | input-lanjian | 67.3 ± 1.1 | 65.8 | 70.0 | 37.18 ± 2.86 |
| pting | input-mattcl | 67.8 ± 1.3 | 65.9 | 71.9 | 37.47 ± 2.91 |
| pting | input-pting | 69.0 ± 0.9 | 67.4 | 71.1 | 38.14 ± 2.91 |
| mattcl-py | input-kcen | 88.5 ± 1.1 | 86.8 | 91.5 | 48.89 ± 3.72 |
| mattcl-py | input-lanjian | 90.9 ± 1.1 | 89.2 | 93.4 | 50.22 ± 3.82 |
| mattcl-py | input-mattcl | 90.9 ± 1.3 | 88.0 | 94.1 | 50.24 ± 3.84 |
| mattcl-py | input-pting | 93.4 ± 1.0 | 91.6 | 95.4 | 51.63 ± 3.92 |
| kcen | input-kcen | 230.9 ± 4.6 | 224.6 | 238.3 | 127.59 ± 9.91 |
| kcen | input-pting | 234.2 ± 3.6 | 226.8 | 242.7 | 129.38 ± 9.92 |
| kcen | input-mattcl | 254.9 ± 5.3 | 242.6 | 263.0 | 140.84 ± 10.98 |
| kcen | input-lanjian | 265.7 ± 6.3 | 258.8 | 280.9 | 146.81 ± 11.57 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|