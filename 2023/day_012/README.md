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
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.6 | 2.3 | 1.00 |
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.2 | 1.00 ± 0.10 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.6 | 1.11 ± 0.13 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.7 | 2.7 | 1.11 ± 0.15 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.8 | 2.6 | 1.14 ± 0.14 |
| mattcl | input-mattcl | 2.2 ± 0.2 | 1.8 | 2.7 | 1.19 ± 0.14 |
| mattcl | input-lanjian | 2.2 ± 0.2 | 1.9 | 2.9 | 1.22 ± 0.14 |
| mattcl | input-pting | 2.2 ± 0.2 | 1.9 | 2.9 | 1.23 ± 0.14 |
| pting | input-kcen | 66.5 ± 0.9 | 64.5 | 68.9 | 36.59 ± 2.46 |
| pting | input-lanjian | 67.9 ± 1.3 | 66.1 | 71.7 | 37.32 ± 2.56 |
| pting | input-mattcl | 67.9 ± 1.3 | 66.0 | 72.4 | 37.33 ± 2.57 |
| pting | input-pting | 69.1 ± 1.0 | 67.5 | 72.6 | 38.01 ± 2.57 |
| mattcl-py | input-kcen | 89.0 ± 1.2 | 86.6 | 91.2 | 48.93 ± 3.29 |
| mattcl-py | input-lanjian | 91.0 ± 1.0 | 89.1 | 93.5 | 50.04 ± 3.35 |
| mattcl-py | input-mattcl | 91.9 ± 1.3 | 89.8 | 94.5 | 50.54 ± 3.41 |
| mattcl-py | input-pting | 94.1 ± 1.3 | 91.9 | 97.6 | 51.77 ± 3.49 |
| kcen | input-kcen | 230.1 ± 3.9 | 223.6 | 238.1 | 126.53 ± 8.63 |
| kcen | input-pting | 234.5 ± 4.2 | 230.8 | 246.1 | 128.96 ± 8.83 |
| kcen | input-mattcl | 254.7 ± 4.2 | 248.2 | 260.6 | 140.04 ± 9.52 |
| kcen | input-lanjian | 268.5 ± 5.1 | 261.6 | 275.4 | 147.65 ± 10.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|