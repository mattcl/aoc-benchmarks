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
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 3.4 | 1.11 ± 0.14 |
| lanjian | input-lanjian | 2.2 ± 3.6 | 1.7 | 53.2 | 1.16 ± 1.95 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 3.8 | 1.18 ± 0.15 |
| mattcl | input-kcen | 2.4 ± 0.2 | 2.0 | 3.6 | 1.31 ± 0.14 |
| mattcl | input-mattcl | 2.5 ± 0.2 | 2.1 | 3.8 | 1.36 ± 0.16 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.0 | 3.7 | 1.36 ± 0.15 |
| mattcl | input-lanjian | 2.6 ± 0.3 | 2.1 | 5.2 | 1.37 ± 0.17 |
| pting | input-kcen | 67.3 ± 1.0 | 65.9 | 70.3 | 36.07 ± 2.46 |
| pting | input-lanjian | 68.4 ± 1.1 | 66.2 | 72.7 | 36.67 ± 2.51 |
| pting | input-mattcl | 68.9 ± 1.1 | 66.5 | 71.3 | 36.94 ± 2.53 |
| pting | input-pting | 70.3 ± 0.9 | 68.5 | 72.6 | 37.67 ± 2.55 |
| mattcl-py | input-kcen | 89.5 ± 1.2 | 87.3 | 92.9 | 47.98 ± 3.26 |
| mattcl-py | input-lanjian | 91.9 ± 1.4 | 89.7 | 95.1 | 49.25 ± 3.36 |
| mattcl-py | input-mattcl | 92.1 ± 1.2 | 89.1 | 95.0 | 49.40 ± 3.35 |
| mattcl-py | input-pting | 94.8 ± 1.2 | 92.4 | 96.8 | 50.84 ± 3.44 |
| kcen | input-kcen | 234.9 ± 3.0 | 228.7 | 240.0 | 125.92 ± 8.53 |
| kcen | input-pting | 238.9 ± 5.1 | 230.1 | 246.2 | 128.07 ± 8.95 |
| kcen | input-mattcl | 255.9 ± 7.0 | 247.8 | 266.4 | 137.17 ± 9.86 |
| kcen | input-lanjian | 270.5 ± 4.2 | 261.7 | 274.3 | 144.99 ± 9.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|