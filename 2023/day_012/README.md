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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.1 | 1.7 | 1.00 |
| mattcl | input-pting | 1.4 ± 0.1 | 1.2 | 1.8 | 1.06 ± 0.16 |
| mattcl | input-mattcl | 1.4 ± 0.1 | 1.2 | 1.7 | 1.06 ± 0.16 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.2 | 1.8 | 1.08 ± 0.17 |
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.3 | 1.36 ± 0.18 |
| lanjian | input-lanjian | 2.0 ± 0.2 | 1.7 | 2.6 | 1.46 ± 0.23 |
| lanjian | input-mattcl | 2.1 ± 0.3 | 1.8 | 4.0 | 1.53 ± 0.26 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.8 | 2.8 | 1.61 ± 0.25 |
| pting | input-kcen | 67.1 ± 1.2 | 64.6 | 69.8 | 49.71 ± 5.73 |
| pting | input-lanjian | 68.2 ± 1.2 | 65.6 | 71.4 | 50.52 ± 5.82 |
| pting | input-mattcl | 68.5 ± 1.2 | 65.9 | 72.1 | 50.72 ± 5.85 |
| pting | input-pting | 69.7 ± 0.9 | 68.0 | 71.5 | 51.59 ± 5.92 |
| mattcl-py | input-kcen | 90.5 ± 1.1 | 88.4 | 93.0 | 66.99 ± 7.67 |
| mattcl-py | input-lanjian | 92.9 ± 1.3 | 90.4 | 96.0 | 68.80 ± 7.90 |
| mattcl-py | input-mattcl | 93.4 ± 1.4 | 91.3 | 96.1 | 69.15 ± 7.94 |
| mattcl-py | input-pting | 95.8 ± 1.3 | 92.4 | 97.9 | 70.90 ± 8.13 |
| kcen | input-kcen | 230.8 ± 3.5 | 226.2 | 237.2 | 170.91 ± 19.64 |
| kcen | input-pting | 235.2 ± 3.9 | 231.0 | 243.8 | 174.17 ± 20.05 |
| kcen | input-mattcl | 255.5 ± 6.5 | 246.5 | 271.2 | 189.20 ± 22.07 |
| kcen | input-lanjian | 268.6 ± 7.0 | 260.9 | 284.9 | 198.90 ± 23.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|