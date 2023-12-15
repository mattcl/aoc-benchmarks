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
| lanjian | input-kcen | 1.9 ± 0.1 | 1.8 | 2.4 | 1.00 |
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.7 | 2.6 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 1.9 ± 0.1 | 1.7 | 3.4 | 1.00 ± 0.11 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.8 | 2.7 | 1.05 ± 0.12 |
| mattcl | input-kcen | 2.5 ± 0.3 | 2.1 | 4.0 | 1.30 ± 0.16 |
| mattcl | input-lanjian | 2.6 ± 0.3 | 2.1 | 5.6 | 1.33 ± 0.18 |
| mattcl | input-pting | 2.7 ± 0.2 | 2.2 | 3.7 | 1.37 ± 0.14 |
| mattcl | input-mattcl | 3.0 ± 4.8 | 2.1 | 70.6 | 1.56 ± 2.49 |
| pting | input-kcen | 67.7 ± 4.8 | 64.7 | 90.3 | 34.90 ± 3.48 |
| pting | input-lanjian | 68.1 ± 1.4 | 66.0 | 71.6 | 35.13 ± 2.59 |
| pting | input-mattcl | 68.5 ± 0.9 | 66.9 | 70.8 | 35.30 ± 2.55 |
| pting | input-pting | 69.9 ± 1.2 | 67.7 | 73.1 | 36.06 ± 2.63 |
| mattcl-py | input-kcen | 89.3 ± 1.3 | 87.2 | 92.5 | 46.06 ± 3.33 |
| mattcl-py | input-lanjian | 91.3 ± 1.1 | 89.0 | 93.6 | 47.08 ± 3.39 |
| mattcl-py | input-mattcl | 92.3 ± 1.3 | 90.0 | 96.2 | 47.57 ± 3.44 |
| mattcl-py | input-pting | 94.6 ± 1.6 | 92.2 | 97.8 | 48.77 ± 3.56 |
| kcen | input-kcen | 230.9 ± 5.1 | 222.8 | 237.9 | 119.07 ± 8.85 |
| kcen | input-pting | 234.5 ± 2.7 | 230.0 | 239.5 | 120.93 ± 8.69 |
| kcen | input-mattcl | 258.8 ± 5.0 | 253.3 | 268.3 | 133.45 ± 9.82 |
| kcen | input-lanjian | 269.5 ± 6.3 | 262.6 | 282.1 | 138.97 ± 10.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|