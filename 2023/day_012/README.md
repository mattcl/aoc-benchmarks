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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.4 | 1.00 |
| lanjian | input-mattcl | 1.8 ± 0.2 | 1.7 | 3.3 | 1.01 ± 0.10 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.4 | 1.01 ± 0.08 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.8 | 2.7 | 1.19 ± 0.13 |
| mattcl | input-kcen | 2.4 ± 0.3 | 2.0 | 5.3 | 1.33 ± 0.17 |
| mattcl | input-pting | 2.5 ± 0.3 | 2.1 | 4.7 | 1.37 ± 0.18 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.1 | 3.1 | 1.37 ± 0.13 |
| mattcl | input-mattcl | 2.6 ± 0.2 | 2.1 | 3.8 | 1.41 ± 0.14 |
| pting | input-kcen | 67.3 ± 1.0 | 65.0 | 70.8 | 36.93 ± 2.21 |
| pting | input-lanjian | 68.6 ± 1.2 | 66.5 | 71.3 | 37.66 ± 2.29 |
| pting | input-mattcl | 68.9 ± 1.1 | 67.3 | 72.9 | 37.84 ± 2.27 |
| pting | input-pting | 71.5 ± 5.6 | 67.8 | 97.9 | 39.25 ± 3.84 |
| mattcl-py | input-kcen | 89.7 ± 1.5 | 87.7 | 94.2 | 49.24 ± 2.96 |
| mattcl-py | input-lanjian | 91.9 ± 1.2 | 89.9 | 94.8 | 50.47 ± 3.00 |
| mattcl-py | input-mattcl | 92.7 ± 1.1 | 90.2 | 94.6 | 50.89 ± 3.01 |
| mattcl-py | input-pting | 98.6 ± 10.6 | 93.6 | 141.2 | 54.15 ± 6.59 |
| kcen | input-kcen | 235.9 ± 4.5 | 231.1 | 243.6 | 129.52 ± 7.90 |
| kcen | input-pting | 239.4 ± 7.0 | 233.2 | 255.2 | 131.44 ± 8.54 |
| kcen | input-mattcl | 259.0 ± 7.3 | 249.3 | 271.7 | 142.18 ± 9.17 |
| kcen | input-lanjian | 272.3 ± 6.6 | 263.1 | 283.4 | 149.47 ± 9.40 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|