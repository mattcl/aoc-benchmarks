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
| lanjian | input-kcen | 1.8 ± 0.2 | 1.6 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.2 | 1.00 ± 0.10 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.6 | 2.5 | 1.09 ± 0.14 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.7 | 2.5 | 1.13 ± 0.15 |
| mattcl | input-kcen | 2.4 ± 0.2 | 1.9 | 2.8 | 1.30 ± 0.14 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.0 | 3.1 | 1.34 ± 0.16 |
| mattcl | input-mattcl | 2.5 ± 0.3 | 2.0 | 4.0 | 1.35 ± 0.19 |
| mattcl | input-pting | 2.6 ± 0.5 | 2.1 | 6.0 | 1.40 ± 0.28 |
| pting | input-kcen | 66.6 ± 1.2 | 64.8 | 71.4 | 36.47 ± 3.18 |
| pting | input-lanjian | 67.5 ± 1.1 | 65.6 | 70.1 | 36.99 ± 3.21 |
| pting | input-mattcl | 68.5 ± 1.0 | 66.6 | 70.7 | 37.50 ± 3.24 |
| pting | input-pting | 69.3 ± 0.8 | 67.4 | 71.0 | 37.96 ± 3.26 |
| mattcl-py | input-kcen | 89.3 ± 1.5 | 86.8 | 92.8 | 48.91 ± 4.24 |
| mattcl-py | input-lanjian | 91.3 ± 1.3 | 88.9 | 94.7 | 50.01 ± 4.31 |
| mattcl-py | input-mattcl | 92.1 ± 1.3 | 89.6 | 94.8 | 50.44 ± 4.35 |
| mattcl-py | input-pting | 94.2 ± 1.2 | 91.8 | 96.6 | 51.63 ± 4.44 |
| kcen | input-kcen | 231.3 ± 5.0 | 223.6 | 241.8 | 126.71 ± 11.13 |
| kcen | input-pting | 235.0 ± 3.0 | 230.3 | 240.3 | 128.72 ± 11.08 |
| kcen | input-mattcl | 254.1 ± 4.7 | 247.3 | 261.2 | 139.22 ± 12.12 |
| kcen | input-lanjian | 268.9 ± 5.5 | 262.5 | 281.1 | 147.32 ± 12.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|