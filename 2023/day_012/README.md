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
| lanjian | input-mattcl | 1.9 ± 0.1 | 1.7 | 2.4 | 1.00 |
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.7 | 2.4 | 1.00 ± 0.09 |
| lanjian | input-kcen | 1.9 ± 0.2 | 1.7 | 2.3 | 1.00 ± 0.11 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 2.7 | 1.14 ± 0.13 |
| mattcl | input-kcen | 2.5 ± 0.3 | 2.1 | 5.0 | 1.32 ± 0.18 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.1 | 3.8 | 1.34 ± 0.14 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.1 | 4.4 | 1.34 ± 0.16 |
| mattcl | input-mattcl | 2.6 ± 0.3 | 2.2 | 5.6 | 1.37 ± 0.18 |
| pting | input-kcen | 66.3 ± 1.0 | 64.8 | 69.0 | 34.97 ± 2.35 |
| pting | input-lanjian | 67.7 ± 1.4 | 65.5 | 71.2 | 35.72 ± 2.45 |
| pting | input-mattcl | 68.0 ± 1.1 | 65.8 | 71.0 | 35.86 ± 2.42 |
| pting | input-pting | 69.0 ± 1.0 | 66.9 | 71.7 | 36.38 ± 2.44 |
| mattcl-py | input-kcen | 88.4 ± 1.2 | 86.9 | 91.4 | 46.62 ± 3.12 |
| mattcl-py | input-lanjian | 90.5 ± 1.1 | 88.0 | 92.3 | 47.70 ± 3.18 |
| mattcl-py | input-mattcl | 91.7 ± 1.4 | 89.5 | 96.5 | 48.37 ± 3.25 |
| mattcl-py | input-pting | 93.5 ± 1.0 | 91.4 | 95.3 | 49.28 ± 3.27 |
| kcen | input-kcen | 231.1 ± 2.4 | 228.2 | 235.7 | 121.82 ± 8.08 |
| kcen | input-pting | 233.4 ± 3.4 | 226.3 | 238.7 | 123.04 ± 8.25 |
| kcen | input-mattcl | 255.1 ± 7.0 | 246.7 | 267.7 | 134.49 ± 9.55 |
| kcen | input-lanjian | 267.1 ± 5.5 | 260.8 | 279.2 | 140.83 ± 9.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|