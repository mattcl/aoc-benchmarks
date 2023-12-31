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
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.9 ± 0.2 | 1.7 | 2.6 | 1.07 ± 0.14 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.5 | 1.12 ± 0.14 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.5 | 1.17 ± 0.14 |
| mattcl | input-kcen | 2.4 ± 0.2 | 1.9 | 4.4 | 1.35 ± 0.16 |
| mattcl | input-mattcl | 2.4 ± 0.2 | 2.1 | 3.1 | 1.37 ± 0.15 |
| mattcl | input-lanjian | 2.5 ± 0.2 | 2.0 | 3.2 | 1.38 ± 0.16 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.0 | 3.3 | 1.41 ± 0.16 |
| pting | input-kcen | 67.0 ± 1.0 | 65.4 | 69.3 | 37.53 ± 2.75 |
| pting | input-lanjian | 68.4 ± 1.3 | 66.5 | 72.1 | 38.33 ± 2.84 |
| pting | input-mattcl | 68.7 ± 0.9 | 67.2 | 70.6 | 38.48 ± 2.80 |
| pting | input-pting | 70.2 ± 1.1 | 68.2 | 72.9 | 39.30 ± 2.88 |
| mattcl-py | input-kcen | 89.9 ± 1.1 | 88.0 | 91.8 | 50.35 ± 3.66 |
| mattcl-py | input-lanjian | 92.2 ± 1.3 | 90.3 | 96.9 | 51.66 ± 3.78 |
| mattcl-py | input-mattcl | 92.3 ± 1.3 | 90.3 | 94.8 | 51.69 ± 3.77 |
| mattcl-py | input-pting | 98.3 ± 12.0 | 93.0 | 154.9 | 55.04 ± 7.82 |
| kcen | input-kcen | 233.7 ± 4.6 | 228.1 | 243.6 | 130.92 ± 9.74 |
| kcen | input-pting | 237.2 ± 3.4 | 231.8 | 243.8 | 132.86 ± 9.72 |
| kcen | input-mattcl | 259.2 ± 7.2 | 247.0 | 270.9 | 145.19 ± 11.16 |
| kcen | input-lanjian | 271.1 ± 5.5 | 263.9 | 278.2 | 151.86 ± 11.31 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|