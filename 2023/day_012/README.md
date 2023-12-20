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
| lanjian | input-kcen | 1.9 ± 0.2 | 1.7 | 3.3 | 1.00 |
| lanjian | input-lanjian | 2.0 ± 0.3 | 1.7 | 3.8 | 1.06 ± 0.17 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.7 | 1.11 ± 0.15 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 2.6 | 1.17 ± 0.16 |
| mattcl | input-kcen | 2.5 ± 0.2 | 2.0 | 3.2 | 1.32 ± 0.16 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.0 | 3.3 | 1.35 ± 0.16 |
| mattcl | input-mattcl | 2.5 ± 0.2 | 2.1 | 3.6 | 1.35 ± 0.18 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.1 | 3.6 | 1.35 ± 0.17 |
| pting | input-kcen | 67.1 ± 1.3 | 65.1 | 73.0 | 36.10 ± 3.39 |
| pting | input-mattcl | 68.5 ± 1.0 | 66.6 | 70.5 | 36.85 ± 3.43 |
| pting | input-lanjian | 68.8 ± 1.5 | 66.9 | 73.1 | 36.99 ± 3.50 |
| pting | input-pting | 70.0 ± 1.2 | 67.7 | 73.5 | 37.62 ± 3.52 |
| mattcl-py | input-kcen | 89.6 ± 1.0 | 87.8 | 91.7 | 48.22 ± 4.47 |
| mattcl-py | input-lanjian | 92.0 ± 1.1 | 90.3 | 94.9 | 49.46 ± 4.58 |
| mattcl-py | input-mattcl | 92.8 ± 1.4 | 90.2 | 95.2 | 49.92 ± 4.65 |
| mattcl-py | input-pting | 95.1 ± 1.3 | 92.8 | 98.0 | 51.16 ± 4.76 |
| kcen | input-kcen | 233.8 ± 3.8 | 227.3 | 241.6 | 125.73 ± 11.74 |
| kcen | input-pting | 239.0 ± 3.5 | 233.9 | 244.9 | 128.52 ± 11.97 |
| kcen | input-mattcl | 259.5 ± 6.3 | 248.1 | 266.8 | 139.55 ± 13.28 |
| kcen | input-lanjian | 270.8 ± 9.7 | 262.2 | 297.9 | 145.65 ± 14.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|