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
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.8 | 2.3 | 1.00 |
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.4 | 1.00 ± 0.08 |
| lanjian | input-mattcl | 1.9 ± 0.1 | 1.7 | 2.4 | 1.00 ± 0.07 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 2.7 | 1.18 ± 0.12 |
| mattcl | input-kcen | 2.5 ± 0.2 | 2.1 | 4.3 | 1.34 ± 0.15 |
| mattcl | input-lanjian | 2.6 ± 0.2 | 2.1 | 3.1 | 1.39 ± 0.12 |
| mattcl | input-pting | 2.6 ± 0.3 | 2.2 | 4.9 | 1.40 ± 0.19 |
| mattcl | input-mattcl | 2.7 ± 0.2 | 2.2 | 3.9 | 1.42 ± 0.13 |
| pting | input-kcen | 67.6 ± 1.1 | 65.0 | 70.6 | 35.93 ± 1.81 |
| pting | input-lanjian | 68.7 ± 1.2 | 66.6 | 71.4 | 36.47 ± 1.86 |
| pting | input-mattcl | 69.3 ± 0.9 | 67.6 | 71.2 | 36.79 ± 1.83 |
| pting | input-pting | 70.2 ± 1.0 | 68.2 | 72.1 | 37.26 ± 1.86 |
| mattcl-py | input-kcen | 89.8 ± 1.3 | 87.8 | 92.8 | 47.67 ± 2.38 |
| mattcl-py | input-lanjian | 92.0 ± 1.1 | 90.5 | 94.3 | 48.85 ± 2.40 |
| mattcl-py | input-mattcl | 92.8 ± 1.1 | 90.4 | 94.9 | 49.27 ± 2.42 |
| mattcl-py | input-pting | 97.2 ± 5.8 | 93.3 | 122.5 | 51.61 ± 3.95 |
| kcen | input-kcen | 233.5 ± 2.9 | 228.4 | 238.2 | 124.01 ± 6.12 |
| kcen | input-pting | 239.4 ± 5.2 | 234.3 | 249.4 | 127.14 ± 6.67 |
| kcen | input-mattcl | 258.5 ± 6.4 | 249.5 | 270.3 | 137.31 ± 7.39 |
| kcen | input-lanjian | 273.2 ± 6.9 | 264.0 | 285.0 | 145.09 ± 7.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|