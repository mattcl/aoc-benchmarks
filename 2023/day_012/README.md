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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.2 | 1.9 | 1.00 |
| mattcl | input-mattcl | 1.5 ± 0.1 | 1.2 | 1.8 | 1.03 ± 0.16 |
| mattcl | input-pting | 1.5 ± 0.1 | 1.2 | 1.9 | 1.04 ± 0.15 |
| mattcl | input-lanjian | 1.5 ± 0.1 | 1.2 | 1.9 | 1.07 ± 0.16 |
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.7 | 1.34 ± 0.17 |
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.8 | 2.5 | 1.34 ± 0.17 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.9 | 2.6 | 1.49 ± 0.22 |
| lanjian | input-pting | 2.6 ± 5.7 | 1.7 | 82.1 | 1.81 ± 3.95 |
| pting | input-kcen | 67.5 ± 1.2 | 65.5 | 71.5 | 47.11 ± 5.35 |
| pting | input-lanjian | 68.7 ± 1.0 | 66.6 | 70.9 | 47.93 ± 5.43 |
| pting | input-mattcl | 69.2 ± 1.2 | 67.2 | 71.8 | 48.27 ± 5.48 |
| pting | input-pting | 70.5 ± 1.2 | 68.5 | 74.2 | 49.16 ± 5.58 |
| mattcl-py | input-kcen | 91.4 ± 1.8 | 88.2 | 95.4 | 63.74 ± 7.27 |
| mattcl-py | input-mattcl | 95.1 ± 6.2 | 92.1 | 128.8 | 66.36 ± 8.63 |
| mattcl-py | input-lanjian | 96.1 ± 7.1 | 91.2 | 123.4 | 67.02 ± 9.03 |
| mattcl-py | input-pting | 97.1 ± 1.3 | 93.7 | 99.9 | 67.73 ± 7.66 |
| kcen | input-kcen | 232.5 ± 4.3 | 225.9 | 239.9 | 162.19 ± 18.46 |
| kcen | input-pting | 239.7 ± 6.5 | 234.0 | 256.8 | 167.20 ± 19.32 |
| kcen | input-mattcl | 256.5 ± 6.5 | 247.6 | 267.2 | 178.92 ± 20.59 |
| kcen | input-lanjian | 273.4 ± 6.9 | 263.4 | 283.0 | 190.71 ± 21.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|