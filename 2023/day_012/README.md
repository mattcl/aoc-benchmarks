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
| lanjian | input-kcen | 1.8 ± 0.2 | 1.7 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.7 | 2.3 | 1.00 ± 0.11 |
| lanjian | input-mattcl | 1.9 ± 0.2 | 1.7 | 2.5 | 1.04 ± 0.14 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.6 | 1.15 ± 0.15 |
| mattcl | input-kcen | 2.4 ± 0.3 | 1.9 | 5.2 | 1.31 ± 0.19 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.0 | 3.4 | 1.34 ± 0.15 |
| mattcl | input-pting | 2.5 ± 0.3 | 2.0 | 4.1 | 1.35 ± 0.18 |
| mattcl | input-mattcl | 2.5 ± 0.4 | 2.0 | 6.6 | 1.36 ± 0.24 |
| pting | input-kcen | 66.4 ± 1.1 | 64.2 | 69.5 | 35.90 ± 2.98 |
| pting | input-lanjian | 67.7 ± 1.1 | 65.8 | 70.7 | 36.61 ± 3.04 |
| pting | input-mattcl | 67.8 ± 1.0 | 66.0 | 70.4 | 36.68 ± 3.03 |
| pting | input-pting | 69.2 ± 1.2 | 67.4 | 73.4 | 37.41 ± 3.11 |
| mattcl-py | input-kcen | 88.7 ± 1.3 | 86.3 | 92.1 | 48.00 ± 3.96 |
| mattcl-py | input-mattcl | 91.1 ± 1.1 | 88.7 | 93.3 | 49.27 ± 4.05 |
| mattcl-py | input-lanjian | 91.2 ± 1.4 | 87.8 | 93.8 | 49.35 ± 4.09 |
| mattcl-py | input-pting | 94.9 ± 5.6 | 90.8 | 124.2 | 51.35 ± 5.16 |
| kcen | input-kcen | 229.4 ± 3.1 | 224.8 | 234.2 | 124.10 ± 10.22 |
| kcen | input-pting | 234.9 ± 4.0 | 229.1 | 243.8 | 127.07 ± 10.56 |
| kcen | input-mattcl | 255.5 ± 7.0 | 243.6 | 267.1 | 138.22 ± 11.85 |
| kcen | input-lanjian | 273.1 ± 7.5 | 262.6 | 284.4 | 147.74 ± 12.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|