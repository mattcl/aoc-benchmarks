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
| lanjian | input-kcen | 1.9 ± 0.2 | 1.7 | 2.6 | 1.00 |
| lanjian | input-mattcl | 2.2 ± 0.3 | 1.8 | 5.3 | 1.15 ± 0.18 |
| lanjian | input-lanjian | 2.3 ± 0.3 | 1.8 | 4.4 | 1.17 ± 0.19 |
| lanjian | input-pting | 2.3 ± 0.2 | 1.9 | 3.1 | 1.18 ± 0.15 |
| mattcl | input-pting | 2.5 ± 0.4 | 2.0 | 6.3 | 1.28 ± 0.21 |
| mattcl | input-lanjian | 2.5 ± 0.4 | 1.9 | 5.0 | 1.30 ± 0.23 |
| mattcl | input-kcen | 2.5 ± 0.2 | 2.0 | 3.4 | 1.31 ± 0.16 |
| mattcl | input-mattcl | 2.6 ± 0.4 | 2.0 | 5.3 | 1.33 ± 0.24 |
| pting | input-lanjian | 69.8 ± 3.6 | 67.3 | 91.6 | 36.17 ± 3.52 |
| pting | input-kcen | 70.0 ± 1.6 | 65.6 | 72.7 | 36.25 ± 3.11 |
| pting | input-mattcl | 70.5 ± 1.3 | 67.9 | 73.8 | 36.50 ± 3.09 |
| pting | input-pting | 72.1 ± 3.4 | 68.6 | 92.0 | 37.36 ± 3.57 |
| mattcl-py | input-lanjian | 93.5 ± 1.8 | 90.7 | 97.9 | 48.43 ± 4.11 |
| mattcl-py | input-kcen | 94.8 ± 2.4 | 90.2 | 99.7 | 49.12 ± 4.24 |
| mattcl-py | input-mattcl | 95.3 ± 1.8 | 91.7 | 99.5 | 49.38 ± 4.18 |
| mattcl-py | input-pting | 98.2 ± 2.4 | 94.5 | 104.8 | 50.87 ± 4.38 |
| kcen | input-kcen | 240.7 ± 9.1 | 228.9 | 254.7 | 124.64 ± 11.32 |
| kcen | input-pting | 256.3 ± 13.3 | 241.9 | 283.5 | 132.75 ± 12.97 |
| kcen | input-mattcl | 267.9 ± 4.3 | 260.9 | 275.1 | 138.72 ± 11.69 |
| kcen | input-lanjian | 285.5 ± 7.5 | 278.2 | 304.3 | 147.84 ± 12.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|