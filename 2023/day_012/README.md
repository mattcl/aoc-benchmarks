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
| lanjian | input-lanjian | 2.0 ± 0.2 | 1.7 | 2.6 | 1.00 |
| lanjian | input-kcen | 2.0 ± 0.2 | 1.7 | 3.3 | 1.01 ± 0.15 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.7 | 1.05 ± 0.14 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.6 | 1.07 ± 0.15 |
| mattcl | input-kcen | 2.2 ± 0.2 | 1.8 | 3.3 | 1.09 ± 0.15 |
| mattcl | input-mattcl | 2.2 ± 0.2 | 1.9 | 2.7 | 1.10 ± 0.15 |
| mattcl | input-pting | 2.2 ± 0.3 | 1.9 | 4.2 | 1.11 ± 0.17 |
| mattcl | input-lanjian | 2.2 ± 0.2 | 1.9 | 3.0 | 1.11 ± 0.15 |
| pting | input-kcen | 66.8 ± 1.0 | 65.1 | 68.8 | 33.70 ± 3.27 |
| pting | input-lanjian | 68.1 ± 1.3 | 66.4 | 73.0 | 34.34 ± 3.36 |
| pting | input-mattcl | 68.2 ± 0.9 | 66.2 | 70.4 | 34.39 ± 3.33 |
| pting | input-pting | 69.4 ± 0.9 | 67.7 | 71.6 | 34.98 ± 3.39 |
| mattcl-py | input-kcen | 88.9 ± 1.2 | 86.8 | 91.1 | 44.80 ± 4.34 |
| mattcl-py | input-lanjian | 91.2 ± 1.2 | 89.3 | 93.9 | 45.98 ± 4.45 |
| mattcl-py | input-mattcl | 92.3 ± 1.4 | 90.5 | 96.2 | 46.50 ± 4.52 |
| mattcl-py | input-pting | 93.9 ± 1.3 | 91.8 | 97.1 | 47.35 ± 4.59 |
| kcen | input-kcen | 234.7 ± 17.8 | 225.3 | 290.4 | 118.31 ± 14.47 |
| kcen | input-pting | 235.8 ± 5.5 | 228.4 | 245.2 | 118.83 ± 11.74 |
| kcen | input-mattcl | 255.5 ± 7.8 | 245.9 | 268.8 | 128.77 ± 12.97 |
| kcen | input-lanjian | 268.3 ± 7.0 | 260.7 | 280.7 | 135.24 ± 13.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|