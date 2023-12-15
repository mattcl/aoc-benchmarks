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
| lanjian | input-kcen | 1.9 ± 0.1 | 1.7 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.9 ± 0.2 | 1.7 | 2.5 | 1.03 ± 0.12 |
| lanjian | input-pting | 1.9 ± 0.2 | 1.7 | 2.6 | 1.04 ± 0.13 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.5 | 1.07 ± 0.14 |
| mattcl | input-kcen | 2.5 ± 0.3 | 2.0 | 5.0 | 1.33 ± 0.18 |
| mattcl | input-mattcl | 2.5 ± 0.2 | 2.0 | 3.3 | 1.35 ± 0.15 |
| mattcl | input-lanjian | 2.5 ± 0.3 | 2.1 | 4.5 | 1.35 ± 0.18 |
| mattcl | input-pting | 2.6 ± 0.3 | 2.1 | 3.8 | 1.39 ± 0.18 |
| pting | input-kcen | 66.8 ± 1.0 | 64.6 | 68.9 | 35.93 ± 2.93 |
| pting | input-lanjian | 68.1 ± 1.4 | 66.1 | 72.7 | 36.63 ± 3.04 |
| pting | input-pting | 69.5 ± 1.1 | 66.7 | 72.3 | 37.42 ± 3.06 |
| pting | input-mattcl | 71.0 ± 9.7 | 66.3 | 122.7 | 38.19 ± 6.03 |
| mattcl-py | input-kcen | 89.6 ± 1.2 | 87.2 | 92.8 | 48.22 ± 3.92 |
| mattcl-py | input-mattcl | 91.7 ± 1.1 | 90.4 | 94.9 | 49.37 ± 4.00 |
| mattcl-py | input-lanjian | 91.8 ± 1.2 | 90.0 | 94.5 | 49.42 ± 4.02 |
| mattcl-py | input-pting | 94.2 ± 1.1 | 92.3 | 96.9 | 50.71 ± 4.11 |
| kcen | input-kcen | 230.0 ± 2.8 | 225.4 | 234.3 | 123.78 ± 10.04 |
| kcen | input-pting | 235.3 ± 5.5 | 227.7 | 249.4 | 126.62 ± 10.58 |
| kcen | input-mattcl | 254.4 ± 7.5 | 242.3 | 265.0 | 136.90 ± 11.69 |
| kcen | input-lanjian | 268.3 ± 7.1 | 262.1 | 284.3 | 144.35 ± 12.19 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|