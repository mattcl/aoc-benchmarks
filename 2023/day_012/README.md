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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.1 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.2 | 1.7 | 1.05 ± 0.16 |
| mattcl | input-pting | 1.4 ± 0.2 | 1.2 | 2.2 | 1.05 ± 0.17 |
| mattcl | input-lanjian | 1.5 ± 0.1 | 1.2 | 1.8 | 1.07 ± 0.16 |
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.3 | 1.38 ± 0.18 |
| lanjian | input-lanjian | 2.0 ± 0.2 | 1.7 | 2.6 | 1.48 ± 0.23 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.7 | 1.52 ± 0.23 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 2.7 | 1.59 ± 0.24 |
| pting | input-kcen | 66.5 ± 1.0 | 64.3 | 69.7 | 48.69 ± 5.57 |
| pting | input-lanjian | 67.9 ± 1.1 | 66.0 | 71.0 | 49.70 ± 5.70 |
| pting | input-mattcl | 68.1 ± 1.1 | 66.0 | 70.4 | 49.88 ± 5.71 |
| pting | input-pting | 69.4 ± 1.0 | 67.7 | 71.8 | 50.84 ± 5.81 |
| mattcl-py | input-kcen | 90.9 ± 7.5 | 87.4 | 131.1 | 66.57 ± 9.33 |
| mattcl-py | input-lanjian | 92.1 ± 1.0 | 90.3 | 94.6 | 67.42 ± 7.69 |
| mattcl-py | input-mattcl | 93.0 ± 1.7 | 90.4 | 98.1 | 68.06 ± 7.82 |
| mattcl-py | input-pting | 95.2 ± 1.2 | 92.9 | 97.8 | 69.69 ± 7.96 |
| kcen | input-kcen | 230.0 ± 4.1 | 221.6 | 234.8 | 168.37 ± 19.33 |
| kcen | input-pting | 235.0 ± 3.8 | 227.7 | 243.2 | 172.01 ± 19.71 |
| kcen | input-mattcl | 254.5 ± 6.2 | 246.2 | 263.4 | 186.32 ± 21.62 |
| kcen | input-lanjian | 265.8 ± 3.5 | 261.2 | 270.4 | 194.59 ± 22.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|