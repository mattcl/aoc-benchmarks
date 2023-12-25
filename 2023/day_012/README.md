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
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.8 | 2.4 | 1.00 |
| lanjian | input-kcen | 1.9 ± 0.1 | 1.8 | 2.4 | 1.00 ± 0.09 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.8 | 1.09 ± 0.12 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.8 | 1.11 ± 0.13 |
| mattcl | input-kcen | 2.5 ± 0.4 | 2.1 | 5.7 | 1.32 ± 0.24 |
| mattcl | input-lanjian | 2.6 ± 0.2 | 2.1 | 3.2 | 1.33 ± 0.13 |
| mattcl | input-mattcl | 2.6 ± 0.3 | 2.1 | 5.0 | 1.35 ± 0.17 |
| mattcl | input-pting | 2.6 ± 0.2 | 2.2 | 3.4 | 1.35 ± 0.14 |
| pting | input-kcen | 66.4 ± 0.9 | 64.7 | 69.5 | 34.46 ± 2.18 |
| pting | input-lanjian | 67.6 ± 1.0 | 65.7 | 70.4 | 35.09 ± 2.22 |
| pting | input-mattcl | 68.3 ± 1.3 | 66.0 | 71.8 | 35.43 ± 2.28 |
| pting | input-pting | 69.4 ± 1.0 | 67.6 | 71.7 | 36.02 ± 2.28 |
| mattcl-py | input-kcen | 88.8 ± 1.3 | 86.2 | 92.5 | 46.07 ± 2.92 |
| mattcl-py | input-lanjian | 90.6 ± 1.1 | 88.5 | 92.9 | 47.04 ± 2.95 |
| mattcl-py | input-mattcl | 91.4 ± 1.1 | 89.6 | 93.8 | 47.42 ± 2.98 |
| mattcl-py | input-pting | 94.2 ± 1.4 | 91.9 | 97.7 | 48.91 ± 3.10 |
| kcen | input-kcen | 229.3 ± 5.1 | 221.6 | 238.2 | 119.00 ± 7.78 |
| kcen | input-pting | 235.7 ± 5.2 | 229.3 | 245.7 | 122.34 ± 7.99 |
| kcen | input-mattcl | 255.2 ± 4.2 | 247.3 | 262.1 | 132.42 ± 8.44 |
| kcen | input-lanjian | 270.6 ± 3.5 | 265.0 | 275.6 | 140.40 ± 8.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|