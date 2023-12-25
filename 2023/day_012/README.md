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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.3 | 1.00 |
| lanjian | input-lanjian | 2.0 ± 0.2 | 1.7 | 2.5 | 1.08 ± 0.14 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.5 | 1.10 ± 0.13 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.7 | 2.6 | 1.16 ± 0.15 |
| mattcl | input-kcen | 2.4 ± 0.2 | 2.0 | 2.9 | 1.32 ± 0.14 |
| mattcl | input-mattcl | 2.4 ± 0.2 | 2.0 | 3.7 | 1.35 ± 0.16 |
| mattcl | input-pting | 2.4 ± 0.2 | 2.0 | 3.3 | 1.36 ± 0.16 |
| mattcl | input-lanjian | 2.5 ± 0.3 | 2.0 | 5.3 | 1.36 ± 0.21 |
| pting | input-kcen | 67.0 ± 1.2 | 64.8 | 70.2 | 37.14 ± 2.86 |
| pting | input-lanjian | 68.1 ± 1.0 | 66.0 | 69.7 | 37.79 ± 2.88 |
| pting | input-mattcl | 68.7 ± 1.2 | 66.7 | 71.5 | 38.11 ± 2.93 |
| pting | input-pting | 69.9 ± 1.0 | 68.2 | 73.0 | 38.80 ± 2.96 |
| mattcl-py | input-kcen | 89.6 ± 1.5 | 87.2 | 94.0 | 49.67 ± 3.81 |
| mattcl-py | input-lanjian | 91.6 ± 1.3 | 89.3 | 94.6 | 50.81 ± 3.87 |
| mattcl-py | input-mattcl | 92.2 ± 1.4 | 90.3 | 96.3 | 51.15 ± 3.91 |
| mattcl-py | input-pting | 94.9 ± 1.1 | 93.2 | 96.9 | 52.67 ± 3.99 |
| kcen | input-kcen | 231.0 ± 3.7 | 224.7 | 237.2 | 128.14 ± 9.82 |
| kcen | input-pting | 237.1 ± 4.9 | 231.5 | 246.9 | 131.53 ± 10.22 |
| kcen | input-mattcl | 257.0 ± 6.1 | 247.5 | 265.8 | 142.54 ± 11.21 |
| kcen | input-lanjian | 268.5 ± 5.1 | 261.7 | 276.3 | 148.94 ± 11.52 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|