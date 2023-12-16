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
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.7 | 2.2 | 1.00 |
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.4 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.6 | 1.11 ± 0.12 |
| lanjian | input-pting | 2.2 ± 0.3 | 1.8 | 4.4 | 1.18 ± 0.16 |
| mattcl | input-kcen | 2.5 ± 0.2 | 2.0 | 3.9 | 1.32 ± 0.15 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.0 | 3.6 | 1.34 ± 0.14 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.1 | 3.5 | 1.34 ± 0.14 |
| mattcl | input-mattcl | 2.5 ± 0.3 | 2.0 | 5.1 | 1.35 ± 0.17 |
| pting | input-kcen | 67.5 ± 1.1 | 65.6 | 70.4 | 36.46 ± 2.03 |
| pting | input-lanjian | 68.5 ± 1.0 | 66.7 | 70.9 | 36.96 ± 2.04 |
| pting | input-mattcl | 69.0 ± 1.1 | 66.4 | 71.2 | 37.24 ± 2.08 |
| pting | input-pting | 70.1 ± 1.1 | 67.5 | 72.0 | 37.85 ± 2.11 |
| mattcl-py | input-kcen | 90.4 ± 1.4 | 88.4 | 94.3 | 48.80 ± 2.71 |
| mattcl-py | input-lanjian | 92.3 ± 1.3 | 89.1 | 95.6 | 49.79 ± 2.76 |
| mattcl-py | input-mattcl | 94.6 ± 7.0 | 90.4 | 128.1 | 51.06 ± 4.68 |
| mattcl-py | input-pting | 95.7 ± 1.5 | 93.4 | 98.7 | 51.65 ± 2.87 |
| kcen | input-kcen | 234.2 ± 3.2 | 228.8 | 239.1 | 126.40 ± 6.97 |
| kcen | input-pting | 238.2 ± 6.3 | 234.4 | 255.4 | 128.59 ± 7.66 |
| kcen | input-mattcl | 258.0 ± 5.9 | 250.8 | 269.2 | 139.24 ± 8.08 |
| kcen | input-lanjian | 273.0 ± 7.7 | 264.7 | 288.9 | 147.37 ± 8.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|