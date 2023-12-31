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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.2 | 1.00 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.3 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.6 | 1.11 ± 0.13 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.9 | 2.6 | 1.17 ± 0.14 |
| mattcl | input-kcen | 2.4 ± 0.2 | 2.0 | 2.8 | 1.33 ± 0.13 |
| mattcl | input-mattcl | 2.5 ± 0.2 | 2.1 | 3.1 | 1.37 ± 0.14 |
| mattcl | input-lanjian | 2.5 ± 0.3 | 2.1 | 4.7 | 1.39 ± 0.17 |
| mattcl | input-pting | 2.6 ± 0.3 | 2.1 | 5.2 | 1.40 ± 0.20 |
| pting | input-kcen | 67.2 ± 0.9 | 65.6 | 69.2 | 36.65 ± 2.47 |
| pting | input-lanjian | 68.3 ± 0.9 | 66.7 | 71.3 | 37.28 ± 2.51 |
| pting | input-mattcl | 69.3 ± 4.2 | 66.9 | 94.9 | 37.82 ± 3.37 |
| pting | input-pting | 70.0 ± 0.8 | 68.8 | 71.8 | 38.20 ± 2.55 |
| mattcl-py | input-kcen | 89.9 ± 1.2 | 87.4 | 93.7 | 49.08 ± 3.31 |
| mattcl-py | input-lanjian | 92.2 ± 1.3 | 89.9 | 96.1 | 50.30 ± 3.39 |
| mattcl-py | input-mattcl | 93.5 ± 4.8 | 90.5 | 118.4 | 51.02 ± 4.27 |
| mattcl-py | input-pting | 95.0 ± 1.2 | 93.4 | 98.1 | 51.86 ± 3.48 |
| kcen | input-kcen | 232.5 ± 3.8 | 228.3 | 240.7 | 126.88 ± 8.63 |
| kcen | input-pting | 238.2 ± 5.1 | 231.9 | 247.6 | 130.00 ± 9.03 |
| kcen | input-mattcl | 260.8 ± 6.1 | 252.4 | 270.9 | 142.32 ± 9.97 |
| kcen | input-lanjian | 271.2 ± 6.5 | 261.3 | 288.0 | 148.02 ± 10.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|