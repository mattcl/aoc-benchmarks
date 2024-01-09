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
| mattcl | input-kcen | 1.3 ± 0.1 | 1.1 | 1.7 | 1.00 |
| mattcl | input-pting | 1.4 ± 0.2 | 1.2 | 1.8 | 1.05 ± 0.16 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.2 | 1.8 | 1.08 ± 0.16 |
| mattcl | input-mattcl | 1.5 ± 0.1 | 1.2 | 2.0 | 1.09 ± 0.16 |
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.3 | 1.38 ± 0.18 |
| lanjian | input-mattcl | 1.9 ± 0.1 | 1.7 | 2.2 | 1.39 ± 0.17 |
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.7 | 2.3 | 1.39 ± 0.17 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.7 | 1.57 ± 0.24 |
| pting | input-kcen | 66.6 ± 1.1 | 64.4 | 69.7 | 49.61 ± 5.33 |
| pting | input-lanjian | 67.7 ± 0.9 | 66.3 | 70.0 | 50.41 ± 5.39 |
| pting | input-mattcl | 68.0 ± 1.1 | 66.1 | 71.2 | 50.63 ± 5.43 |
| pting | input-pting | 69.2 ± 1.2 | 66.8 | 72.3 | 51.55 ± 5.53 |
| mattcl-py | input-kcen | 89.8 ± 1.2 | 87.6 | 92.8 | 66.92 ± 7.16 |
| mattcl-py | input-lanjian | 92.4 ± 1.2 | 90.3 | 94.9 | 68.84 ± 7.36 |
| mattcl-py | input-mattcl | 93.3 ± 1.6 | 91.0 | 97.9 | 69.48 ± 7.47 |
| mattcl-py | input-pting | 95.1 ± 1.3 | 92.8 | 98.7 | 70.85 ± 7.58 |
| kcen | input-kcen | 232.2 ± 5.1 | 225.1 | 241.4 | 172.96 ± 18.74 |
| kcen | input-pting | 235.9 ± 3.4 | 228.0 | 240.0 | 175.70 ± 18.81 |
| kcen | input-mattcl | 253.3 ± 6.5 | 244.4 | 264.6 | 188.68 ± 20.58 |
| kcen | input-lanjian | 272.2 ± 5.5 | 261.3 | 279.6 | 202.74 ± 21.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|