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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.2 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.6 | 2.5 | 1.10 ± 0.12 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.7 | 1.16 ± 0.13 |
| mattcl | input-kcen | 2.4 ± 0.3 | 1.9 | 4.0 | 1.33 ± 0.17 |
| mattcl | input-mattcl | 2.4 ± 0.3 | 2.0 | 4.8 | 1.36 ± 0.18 |
| mattcl | input-lanjian | 2.4 ± 0.2 | 2.0 | 3.2 | 1.36 ± 0.13 |
| mattcl | input-pting | 2.4 ± 0.2 | 2.0 | 3.8 | 1.37 ± 0.15 |
| pting | input-kcen | 67.3 ± 1.1 | 65.2 | 70.1 | 37.69 ± 2.24 |
| pting | input-lanjian | 68.5 ± 1.1 | 66.9 | 71.3 | 38.37 ± 2.28 |
| pting | input-mattcl | 69.2 ± 1.5 | 66.5 | 74.8 | 38.76 ± 2.36 |
| pting | input-pting | 69.8 ± 1.1 | 67.8 | 72.6 | 39.06 ± 2.32 |
| mattcl-py | input-kcen | 89.9 ± 1.5 | 87.3 | 94.5 | 50.33 ± 3.01 |
| mattcl-py | input-mattcl | 92.7 ± 1.3 | 90.1 | 95.5 | 51.90 ± 3.06 |
| mattcl-py | input-lanjian | 94.2 ± 3.2 | 90.5 | 101.5 | 52.77 ± 3.50 |
| mattcl-py | input-pting | 96.9 ± 5.6 | 93.5 | 125.5 | 54.27 ± 4.43 |
| kcen | input-kcen | 235.0 ± 6.5 | 225.4 | 247.8 | 131.59 ± 8.37 |
| kcen | input-pting | 237.8 ± 3.7 | 234.0 | 244.7 | 133.19 ± 7.90 |
| kcen | input-mattcl | 258.2 ± 7.8 | 246.3 | 268.8 | 144.58 ± 9.35 |
| kcen | input-lanjian | 270.7 ± 5.7 | 263.7 | 283.8 | 151.57 ± 9.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|