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
| lanjian | input-kcen | 1.8 ± 0.2 | 1.6 | 4.0 | 1.00 |
| lanjian | input-mattcl | 1.9 ± 0.2 | 1.7 | 2.5 | 1.08 ± 0.17 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.7 | 2.6 | 1.13 ± 0.19 |
| lanjian | input-lanjian | 2.2 ± 3.8 | 1.6 | 56.1 | 1.22 ± 2.13 |
| mattcl | input-kcen | 2.3 ± 0.2 | 1.8 | 3.5 | 1.26 ± 0.20 |
| mattcl | input-lanjian | 2.4 ± 0.3 | 1.9 | 5.7 | 1.31 ± 0.24 |
| mattcl | input-pting | 2.4 ± 0.2 | 1.9 | 4.0 | 1.32 ± 0.21 |
| mattcl | input-mattcl | 2.4 ± 0.3 | 2.0 | 3.7 | 1.32 ± 0.22 |
| pting | input-kcen | 66.9 ± 1.2 | 65.0 | 71.0 | 37.11 ± 4.72 |
| pting | input-lanjian | 67.7 ± 1.4 | 65.3 | 71.4 | 37.54 ± 4.79 |
| pting | input-mattcl | 67.9 ± 1.1 | 66.1 | 70.4 | 37.64 ± 4.77 |
| pting | input-pting | 69.5 ± 1.1 | 67.3 | 72.1 | 38.54 ± 4.88 |
| mattcl-py | input-kcen | 88.8 ± 1.4 | 86.3 | 93.9 | 49.23 ± 6.24 |
| mattcl-py | input-lanjian | 90.8 ± 1.1 | 88.6 | 93.6 | 50.36 ± 6.36 |
| mattcl-py | input-mattcl | 91.4 ± 1.6 | 87.8 | 95.6 | 50.69 ± 6.44 |
| mattcl-py | input-pting | 94.1 ± 1.4 | 91.5 | 97.7 | 52.15 ± 6.60 |
| kcen | input-kcen | 229.3 ± 5.0 | 220.3 | 235.8 | 127.10 ± 16.23 |
| kcen | input-pting | 233.9 ± 2.3 | 230.5 | 239.4 | 129.64 ± 16.36 |
| kcen | input-mattcl | 254.1 ± 6.8 | 245.7 | 263.9 | 140.88 ± 18.12 |
| kcen | input-lanjian | 274.6 ± 11.4 | 261.0 | 299.3 | 152.22 ± 20.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|