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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.4 | 1.00 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.4 | 1.00 ± 0.09 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.6 | 1.16 ± 0.14 |
| lanjian | input-mattcl | 2.2 ± 3.8 | 1.7 | 55.3 | 1.19 ± 2.07 |
| mattcl | input-kcen | 2.4 ± 0.2 | 2.0 | 3.0 | 1.31 ± 0.14 |
| mattcl | input-pting | 2.5 ± 0.3 | 2.0 | 4.0 | 1.36 ± 0.18 |
| mattcl | input-lanjian | 2.5 ± 0.3 | 2.0 | 5.0 | 1.37 ± 0.19 |
| mattcl | input-mattcl | 2.5 ± 0.4 | 2.0 | 5.1 | 1.38 ± 0.22 |
| pting | input-kcen | 67.2 ± 0.9 | 65.5 | 69.4 | 36.69 ± 2.77 |
| pting | input-lanjian | 68.5 ± 1.0 | 67.0 | 70.6 | 37.39 ± 2.83 |
| pting | input-mattcl | 68.5 ± 0.9 | 66.8 | 70.2 | 37.44 ± 2.83 |
| pting | input-pting | 70.0 ± 0.9 | 68.7 | 72.9 | 38.27 ± 2.89 |
| mattcl-py | input-kcen | 89.9 ± 1.2 | 88.2 | 92.8 | 49.13 ± 3.71 |
| mattcl-py | input-lanjian | 92.4 ± 1.5 | 90.4 | 96.3 | 50.45 ± 3.83 |
| mattcl-py | input-mattcl | 92.5 ± 1.3 | 90.8 | 95.1 | 50.53 ± 3.82 |
| mattcl-py | input-pting | 95.5 ± 1.0 | 92.9 | 98.6 | 52.16 ± 3.92 |
| kcen | input-kcen | 232.6 ± 5.0 | 223.8 | 239.6 | 127.09 ± 9.83 |
| kcen | input-pting | 240.2 ± 6.8 | 231.8 | 254.6 | 131.21 ± 10.42 |
| kcen | input-mattcl | 259.4 ± 5.2 | 251.2 | 267.8 | 141.73 ± 10.91 |
| kcen | input-lanjian | 273.8 ± 8.2 | 264.7 | 286.8 | 149.54 ± 11.98 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|