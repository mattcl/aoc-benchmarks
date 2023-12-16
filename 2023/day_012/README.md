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
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.7 | 2.6 | 1.00 ± 0.11 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.8 | 2.6 | 1.07 ± 0.14 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.7 | 1.09 ± 0.13 |
| mattcl | input-kcen | 2.5 ± 0.3 | 2.0 | 4.2 | 1.29 ± 0.18 |
| mattcl | input-mattcl | 2.5 ± 0.3 | 2.0 | 5.3 | 1.32 ± 0.18 |
| mattcl | input-lanjian | 2.6 ± 0.3 | 2.1 | 4.8 | 1.33 ± 0.17 |
| mattcl | input-pting | 2.6 ± 0.2 | 2.1 | 4.0 | 1.34 ± 0.16 |
| pting | input-kcen | 67.1 ± 1.1 | 64.6 | 69.8 | 35.01 ± 2.76 |
| pting | input-mattcl | 68.1 ± 0.9 | 66.5 | 69.7 | 35.52 ± 2.78 |
| pting | input-lanjian | 68.5 ± 1.5 | 66.2 | 74.9 | 35.71 ± 2.86 |
| pting | input-pting | 69.5 ± 1.2 | 66.9 | 71.9 | 36.23 ± 2.87 |
| mattcl-py | input-kcen | 89.1 ± 1.2 | 86.2 | 93.4 | 46.47 ± 3.64 |
| mattcl-py | input-lanjian | 91.6 ± 1.2 | 89.6 | 93.7 | 47.78 ± 3.74 |
| mattcl-py | input-mattcl | 92.4 ± 1.5 | 90.2 | 95.9 | 48.18 ± 3.80 |
| mattcl-py | input-pting | 94.4 ± 1.2 | 91.4 | 96.1 | 49.20 ± 3.85 |
| kcen | input-kcen | 233.2 ± 4.5 | 223.5 | 241.0 | 121.59 ± 9.67 |
| kcen | input-pting | 234.8 ± 5.1 | 227.3 | 246.9 | 122.42 ± 9.80 |
| kcen | input-mattcl | 254.8 ± 7.0 | 247.2 | 264.4 | 132.87 ± 10.88 |
| kcen | input-lanjian | 272.0 ± 7.6 | 262.4 | 283.2 | 141.85 ± 11.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|