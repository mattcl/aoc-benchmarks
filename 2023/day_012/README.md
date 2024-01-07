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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.1 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.1 | 1.2 | 1.7 | 1.03 ± 0.16 |
| mattcl | input-pting | 1.4 ± 0.1 | 1.2 | 1.7 | 1.04 ± 0.16 |
| mattcl | input-lanjian | 1.5 ± 0.1 | 1.2 | 1.8 | 1.08 ± 0.16 |
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.8 | 2.4 | 1.37 ± 0.17 |
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.3 | 1.37 ± 0.18 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.7 | 1.51 ± 0.23 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.8 | 2.7 | 1.59 ± 0.24 |
| pting | input-kcen | 66.3 ± 1.0 | 64.2 | 69.1 | 48.17 ± 5.55 |
| pting | input-mattcl | 68.4 ± 1.2 | 66.6 | 71.1 | 49.66 ± 5.73 |
| pting | input-lanjian | 68.9 ± 7.6 | 65.9 | 117.6 | 50.02 ± 7.93 |
| pting | input-pting | 68.9 ± 0.9 | 67.3 | 70.7 | 50.04 ± 5.75 |
| mattcl-py | input-kcen | 89.7 ± 1.2 | 87.5 | 93.7 | 65.10 ± 7.49 |
| mattcl-py | input-mattcl | 92.1 ± 0.9 | 90.5 | 94.1 | 66.84 ± 7.67 |
| mattcl-py | input-lanjian | 93.3 ± 6.3 | 90.1 | 127.1 | 67.78 ± 8.99 |
| mattcl-py | input-pting | 94.5 ± 1.0 | 92.6 | 96.8 | 68.63 ± 7.88 |
| kcen | input-kcen | 230.1 ± 4.4 | 222.8 | 236.8 | 167.11 ± 19.36 |
| kcen | input-pting | 233.5 ± 4.2 | 228.1 | 243.7 | 169.57 ± 19.61 |
| kcen | input-mattcl | 252.9 ± 4.7 | 245.6 | 259.1 | 183.65 ± 21.26 |
| kcen | input-lanjian | 272.0 ± 12.9 | 260.5 | 305.2 | 197.51 ± 24.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|