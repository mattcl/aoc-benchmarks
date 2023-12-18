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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.3 | 1.00 ± 0.11 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.8 | 2.6 | 1.10 ± 0.14 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.7 | 2.6 | 1.10 ± 0.15 |
| mattcl | input-kcen | 2.4 ± 0.2 | 1.9 | 3.2 | 1.30 ± 0.15 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.0 | 3.4 | 1.34 ± 0.15 |
| mattcl | input-mattcl | 2.5 ± 0.3 | 2.0 | 5.5 | 1.34 ± 0.19 |
| mattcl | input-pting | 2.6 ± 0.4 | 2.1 | 5.5 | 1.40 ± 0.23 |
| pting | input-kcen | 66.5 ± 0.8 | 64.9 | 69.1 | 36.02 ± 2.84 |
| pting | input-lanjian | 67.6 ± 0.9 | 66.0 | 69.5 | 36.62 ± 2.89 |
| pting | input-mattcl | 68.2 ± 1.0 | 66.8 | 72.0 | 36.97 ± 2.94 |
| pting | input-pting | 69.3 ± 1.0 | 67.6 | 72.1 | 37.54 ± 2.98 |
| mattcl-py | input-kcen | 89.3 ± 1.5 | 86.6 | 94.1 | 48.40 ± 3.86 |
| mattcl-py | input-mattcl | 91.7 ± 1.4 | 89.2 | 96.0 | 49.69 ± 3.95 |
| mattcl-py | input-lanjian | 92.0 ± 4.6 | 89.3 | 115.8 | 49.82 ± 4.60 |
| mattcl-py | input-pting | 94.4 ± 1.2 | 92.2 | 96.5 | 51.16 ± 4.04 |
| kcen | input-kcen | 234.0 ± 6.0 | 226.0 | 242.3 | 126.77 ± 10.41 |
| kcen | input-pting | 235.2 ± 3.8 | 228.0 | 242.9 | 127.42 ± 10.15 |
| kcen | input-mattcl | 253.2 ± 5.6 | 245.5 | 263.2 | 137.17 ± 11.12 |
| kcen | input-lanjian | 267.4 ± 5.8 | 261.5 | 281.7 | 144.83 ± 11.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|