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
| lanjian | input-mattcl | 1.9 ± 0.1 | 1.8 | 2.4 | 1.00 |
| lanjian | input-lanjian | 2.0 ± 0.1 | 1.8 | 2.3 | 1.00 ± 0.09 |
| lanjian | input-kcen | 2.0 ± 0.1 | 1.8 | 2.4 | 1.00 ± 0.09 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 2.7 | 1.14 ± 0.14 |
| mattcl | input-kcen | 2.5 ± 0.2 | 2.0 | 3.1 | 1.27 ± 0.14 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.1 | 3.3 | 1.30 ± 0.14 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.1 | 3.6 | 1.30 ± 0.14 |
| mattcl | input-mattcl | 2.6 ± 0.2 | 2.2 | 3.9 | 1.35 ± 0.15 |
| pting | input-kcen | 66.4 ± 0.9 | 64.7 | 69.3 | 34.06 ± 2.29 |
| pting | input-lanjian | 67.9 ± 0.9 | 66.2 | 71.2 | 34.84 ± 2.34 |
| pting | input-mattcl | 68.4 ± 1.1 | 66.6 | 71.9 | 35.09 ± 2.38 |
| pting | input-pting | 69.7 ± 1.1 | 67.9 | 72.2 | 35.77 ± 2.42 |
| mattcl-py | input-kcen | 89.2 ± 1.2 | 86.7 | 91.9 | 45.77 ± 3.07 |
| mattcl-py | input-lanjian | 91.5 ± 1.2 | 89.5 | 95.3 | 46.95 ± 3.16 |
| mattcl-py | input-mattcl | 91.7 ± 1.1 | 88.9 | 93.4 | 47.06 ± 3.15 |
| mattcl-py | input-pting | 94.4 ± 1.4 | 91.9 | 97.6 | 48.41 ± 3.27 |
| kcen | input-kcen | 234.0 ± 4.8 | 227.1 | 242.7 | 120.00 ± 8.28 |
| kcen | input-pting | 234.6 ± 2.5 | 231.0 | 237.8 | 120.33 ± 8.02 |
| kcen | input-mattcl | 261.3 ± 12.1 | 245.9 | 283.9 | 134.00 ± 10.79 |
| kcen | input-lanjian | 268.7 ± 7.1 | 260.3 | 286.1 | 137.79 ± 9.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|