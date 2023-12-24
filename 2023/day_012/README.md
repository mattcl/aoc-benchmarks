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
| lanjian | input-kcen | 2.0 ± 0.2 | 1.7 | 2.6 | 1.00 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 3.5 | 1.04 ± 0.15 |
| lanjian | input-lanjian | 2.2 ± 0.2 | 1.9 | 2.6 | 1.06 ± 0.15 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 2.7 | 1.09 ± 0.15 |
| mattcl | input-mattcl | 2.6 ± 0.3 | 2.1 | 5.3 | 1.29 ± 0.21 |
| mattcl | input-lanjian | 2.6 ± 0.3 | 2.2 | 5.3 | 1.30 ± 0.21 |
| mattcl | input-kcen | 2.7 ± 0.5 | 2.1 | 5.4 | 1.32 ± 0.26 |
| mattcl | input-pting | 2.7 ± 0.3 | 2.2 | 5.7 | 1.32 ± 0.21 |
| pting | input-lanjian | 69.4 ± 1.4 | 67.5 | 73.3 | 34.01 ± 3.58 |
| pting | input-kcen | 77.9 ± 27.6 | 67.0 | 176.2 | 38.17 ± 14.07 |
| pting | input-mattcl | 78.5 ± 27.7 | 67.8 | 191.0 | 38.49 ± 14.14 |
| pting | input-pting | 80.7 ± 26.9 | 69.6 | 175.9 | 39.56 ± 13.79 |
| mattcl-py | input-kcen | 94.7 ± 1.7 | 91.5 | 99.4 | 46.42 ± 4.88 |
| mattcl-py | input-lanjian | 96.5 ± 1.6 | 94.2 | 99.7 | 47.30 ± 4.95 |
| mattcl-py | input-mattcl | 98.1 ± 4.0 | 92.9 | 108.4 | 48.08 ± 5.35 |
| mattcl-py | input-pting | 100.0 ± 1.6 | 97.0 | 104.3 | 49.01 ± 5.13 |
| kcen | input-kcen | 245.1 ± 3.4 | 241.1 | 251.1 | 120.12 ± 12.53 |
| kcen | input-pting | 256.0 ± 7.2 | 248.2 | 268.3 | 125.44 ± 13.45 |
| kcen | input-lanjian | 291.6 ± 6.6 | 285.3 | 306.1 | 142.90 ± 15.13 |
| kcen | input-mattcl | 327.2 ± 83.0 | 268.5 | 440.8 | 160.33 ± 43.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|