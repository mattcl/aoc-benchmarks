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
| mattcl | input-kcen | 1.3 ± 0.1 | 1.1 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.1 | 1.1 | 1.8 | 1.03 ± 0.16 |
| mattcl | input-pting | 1.4 ± 0.2 | 1.2 | 1.8 | 1.06 ± 0.17 |
| mattcl | input-lanjian | 1.5 ± 0.1 | 1.2 | 1.7 | 1.09 ± 0.16 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.3 | 1.37 ± 0.17 |
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.5 | 1.39 ± 0.19 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.6 | 1.53 ± 0.23 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.6 | 1.61 ± 0.24 |
| pting | input-kcen | 66.8 ± 1.0 | 64.9 | 70.2 | 50.21 ± 5.68 |
| pting | input-lanjian | 68.1 ± 1.0 | 66.2 | 71.3 | 51.20 ± 5.79 |
| pting | input-mattcl | 68.6 ± 1.2 | 66.6 | 72.0 | 51.55 ± 5.85 |
| pting | input-pting | 70.0 ± 1.2 | 68.4 | 74.2 | 52.66 ± 5.97 |
| mattcl-py | input-kcen | 90.7 ± 0.8 | 89.2 | 92.1 | 68.16 ± 7.67 |
| mattcl-py | input-mattcl | 93.1 ± 1.1 | 91.3 | 95.7 | 70.01 ± 7.89 |
| mattcl-py | input-lanjian | 93.2 ± 1.3 | 91.6 | 96.8 | 70.10 ± 7.92 |
| mattcl-py | input-pting | 96.2 ± 1.5 | 93.9 | 99.5 | 72.30 ± 8.19 |
| kcen | input-kcen | 230.8 ± 4.8 | 225.2 | 240.0 | 173.52 ± 19.80 |
| kcen | input-pting | 239.2 ± 4.1 | 233.4 | 246.8 | 179.81 ± 20.40 |
| kcen | input-mattcl | 259.5 ± 7.3 | 250.9 | 276.7 | 195.07 ± 22.56 |
| kcen | input-lanjian | 270.0 ± 7.4 | 261.4 | 285.6 | 202.97 ± 23.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|