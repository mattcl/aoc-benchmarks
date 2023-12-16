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
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.3 | 1.00 ± 0.10 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.7 | 2.5 | 1.08 ± 0.15 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.8 | 2.6 | 1.11 ± 0.15 |
| mattcl | input-kcen | 2.3 ± 0.2 | 1.9 | 3.0 | 1.28 ± 0.15 |
| mattcl | input-mattcl | 2.4 ± 0.3 | 2.0 | 4.9 | 1.33 ± 0.18 |
| mattcl | input-lanjian | 2.4 ± 0.2 | 2.0 | 3.1 | 1.33 ± 0.16 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.0 | 3.9 | 1.36 ± 0.17 |
| pting | input-kcen | 66.9 ± 1.1 | 64.7 | 70.0 | 36.47 ± 2.98 |
| pting | input-lanjian | 68.0 ± 1.0 | 66.3 | 70.3 | 37.07 ± 3.03 |
| pting | input-mattcl | 68.8 ± 1.3 | 66.1 | 72.1 | 37.47 ± 3.09 |
| pting | input-pting | 69.5 ± 1.2 | 67.5 | 73.5 | 37.89 ± 3.11 |
| mattcl-py | input-kcen | 89.4 ± 1.2 | 87.2 | 92.1 | 48.71 ± 3.97 |
| mattcl-py | input-lanjian | 91.4 ± 1.3 | 89.4 | 94.2 | 49.78 ± 4.06 |
| mattcl-py | input-mattcl | 92.4 ± 1.1 | 89.7 | 94.3 | 50.34 ± 4.08 |
| mattcl-py | input-pting | 94.4 ± 1.3 | 92.1 | 97.6 | 51.43 ± 4.19 |
| kcen | input-kcen | 232.4 ± 2.7 | 226.9 | 238.1 | 126.62 ± 10.26 |
| kcen | input-pting | 234.2 ± 2.9 | 228.3 | 240.0 | 127.62 ± 10.36 |
| kcen | input-mattcl | 253.0 ± 5.2 | 243.1 | 258.1 | 137.84 ± 11.42 |
| kcen | input-lanjian | 268.4 ± 5.8 | 263.0 | 283.7 | 146.24 ± 12.16 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|