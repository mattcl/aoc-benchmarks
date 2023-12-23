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
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.2 | 1.00 |
| lanjian | input-mattcl | 1.8 ± 0.1 | 1.7 | 2.3 | 1.00 ± 0.08 |
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.2 | 1.00 ± 0.08 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 2.7 | 1.17 ± 0.13 |
| mattcl | input-kcen | 2.4 ± 0.3 | 2.0 | 3.9 | 1.33 ± 0.16 |
| mattcl | input-pting | 2.5 ± 0.5 | 2.1 | 5.8 | 1.38 ± 0.27 |
| mattcl | input-lanjian | 2.6 ± 0.3 | 2.1 | 5.1 | 1.39 ± 0.18 |
| mattcl | input-mattcl | 3.1 ± 4.6 | 2.1 | 56.0 | 1.67 ± 2.52 |
| pting | input-kcen | 67.3 ± 1.0 | 65.3 | 69.4 | 36.50 ± 2.12 |
| pting | input-lanjian | 68.2 ± 0.9 | 66.2 | 70.6 | 36.97 ± 2.14 |
| pting | input-mattcl | 68.8 ± 1.1 | 66.1 | 71.2 | 37.33 ± 2.18 |
| pting | input-pting | 70.3 ± 1.0 | 67.8 | 72.5 | 38.16 ± 2.21 |
| mattcl-py | input-kcen | 90.4 ± 1.5 | 87.7 | 95.1 | 49.04 ± 2.87 |
| mattcl-py | input-lanjian | 92.4 ± 1.3 | 90.2 | 96.0 | 50.11 ± 2.91 |
| mattcl-py | input-mattcl | 93.6 ± 6.4 | 90.4 | 128.1 | 50.74 ± 4.50 |
| mattcl-py | input-pting | 95.2 ± 1.4 | 92.9 | 98.7 | 51.65 ± 2.99 |
| kcen | input-kcen | 229.7 ± 2.6 | 225.7 | 235.1 | 124.60 ± 7.14 |
| kcen | input-pting | 237.4 ± 4.0 | 228.5 | 243.9 | 128.77 ± 7.55 |
| kcen | input-mattcl | 264.1 ± 16.9 | 250.6 | 312.1 | 143.26 ± 12.20 |
| kcen | input-lanjian | 268.5 ± 5.7 | 263.5 | 280.5 | 145.61 ± 8.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|