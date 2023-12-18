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
| lanjian | input-mattcl | 1.9 ± 0.1 | 1.7 | 2.3 | 1.00 |
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.5 | 1.00 ± 0.11 |
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.7 | 2.3 | 1.00 ± 0.10 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.8 | 2.6 | 1.15 ± 0.14 |
| mattcl | input-kcen | 2.4 ± 0.3 | 1.9 | 5.2 | 1.27 ± 0.20 |
| mattcl | input-pting | 2.5 ± 0.3 | 2.0 | 4.5 | 1.32 ± 0.17 |
| mattcl | input-lanjian | 2.5 ± 0.3 | 2.0 | 5.6 | 1.33 ± 0.21 |
| mattcl | input-mattcl | 2.6 ± 0.2 | 2.2 | 3.9 | 1.35 ± 0.16 |
| pting | input-kcen | 66.8 ± 1.1 | 65.2 | 70.9 | 35.28 ± 2.61 |
| pting | input-mattcl | 68.2 ± 1.1 | 66.2 | 70.9 | 36.04 ± 2.66 |
| pting | input-lanjian | 68.7 ± 6.3 | 65.8 | 109.4 | 36.32 ± 4.25 |
| pting | input-pting | 69.1 ± 1.0 | 67.1 | 71.8 | 36.51 ± 2.68 |
| mattcl-py | input-kcen | 89.0 ± 0.9 | 87.5 | 91.7 | 47.05 ± 3.42 |
| mattcl-py | input-lanjian | 91.0 ± 1.2 | 88.7 | 93.4 | 48.10 ± 3.52 |
| mattcl-py | input-mattcl | 91.6 ± 1.2 | 89.9 | 94.2 | 48.42 ± 3.54 |
| mattcl-py | input-pting | 94.2 ± 1.0 | 92.6 | 96.7 | 49.78 ± 3.62 |
| kcen | input-kcen | 231.3 ± 5.7 | 222.9 | 240.0 | 122.22 ± 9.30 |
| kcen | input-pting | 236.3 ± 3.1 | 231.6 | 244.0 | 124.87 ± 9.15 |
| kcen | input-mattcl | 255.8 ± 6.1 | 244.8 | 264.7 | 135.16 ± 10.26 |
| kcen | input-lanjian | 271.4 ± 10.1 | 260.6 | 295.7 | 143.39 ± 11.63 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|