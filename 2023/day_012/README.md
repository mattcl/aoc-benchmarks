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
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.6 | 2.2 | 1.00 |
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.2 | 1.00 ± 0.10 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.5 | 1.12 ± 0.13 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.5 | 1.17 ± 0.14 |
| mattcl | input-kcen | 2.3 ± 0.2 | 1.9 | 3.2 | 1.33 ± 0.15 |
| mattcl | input-pting | 2.4 ± 0.2 | 2.0 | 2.9 | 1.37 ± 0.14 |
| mattcl | input-mattcl | 2.4 ± 0.3 | 2.0 | 4.3 | 1.39 ± 0.18 |
| mattcl | input-lanjian | 2.5 ± 0.3 | 2.0 | 5.7 | 1.40 ± 0.19 |
| pting | input-kcen | 67.1 ± 1.2 | 64.7 | 69.7 | 38.33 ± 2.35 |
| pting | input-lanjian | 68.3 ± 1.3 | 66.4 | 71.9 | 39.04 ± 2.41 |
| pting | input-mattcl | 68.7 ± 1.2 | 66.4 | 72.9 | 39.24 ± 2.40 |
| pting | input-pting | 69.8 ± 1.0 | 67.2 | 72.9 | 39.86 ± 2.41 |
| mattcl-py | input-kcen | 89.8 ± 1.1 | 88.2 | 91.9 | 51.28 ± 3.07 |
| mattcl-py | input-lanjian | 91.6 ± 1.0 | 88.5 | 93.7 | 52.32 ± 3.13 |
| mattcl-py | input-mattcl | 92.4 ± 1.0 | 89.4 | 93.8 | 52.77 ± 3.15 |
| mattcl-py | input-pting | 94.9 ± 1.1 | 92.8 | 96.8 | 54.24 ± 3.25 |
| kcen | input-kcen | 232.1 ± 5.9 | 222.9 | 244.6 | 132.57 ± 8.48 |
| kcen | input-pting | 238.9 ± 5.4 | 231.1 | 245.9 | 136.47 ± 8.59 |
| kcen | input-mattcl | 258.6 ± 5.3 | 249.1 | 267.5 | 147.71 ± 9.19 |
| kcen | input-lanjian | 269.8 ± 3.2 | 265.7 | 276.1 | 154.12 ± 9.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|