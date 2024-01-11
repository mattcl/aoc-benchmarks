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
| mattcl | input-kcen | 1.4 ± 0.2 | 1.1 | 1.9 | 1.00 |
| mattcl | input-pting | 1.4 ± 0.2 | 1.2 | 1.9 | 1.05 ± 0.18 |
| mattcl | input-mattcl | 1.5 ± 0.1 | 1.2 | 1.9 | 1.08 ± 0.17 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.2 | 1.9 | 1.10 ± 0.18 |
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.3 | 1.33 ± 0.18 |
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.7 | 2.5 | 1.36 ± 0.20 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.6 | 1.44 ± 0.25 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.8 | 2.6 | 1.61 ± 0.26 |
| pting | input-kcen | 67.3 ± 1.1 | 64.8 | 70.8 | 49.38 ± 6.25 |
| pting | input-lanjian | 68.5 ± 1.0 | 67.1 | 71.6 | 50.21 ± 6.35 |
| pting | input-mattcl | 68.7 ± 1.0 | 66.8 | 71.6 | 50.36 ± 6.36 |
| pting | input-pting | 71.1 ± 6.9 | 68.1 | 114.1 | 52.15 ± 8.25 |
| mattcl-py | input-kcen | 90.6 ± 1.0 | 88.3 | 92.2 | 66.41 ± 8.37 |
| mattcl-py | input-lanjian | 93.9 ± 1.7 | 90.6 | 98.5 | 68.82 ± 8.73 |
| mattcl-py | input-mattcl | 94.0 ± 1.4 | 91.8 | 97.3 | 68.91 ± 8.71 |
| mattcl-py | input-pting | 96.8 ± 1.5 | 94.5 | 102.8 | 70.96 ± 8.98 |
| kcen | input-kcen | 234.1 ± 3.6 | 228.6 | 240.4 | 171.69 ± 21.72 |
| kcen | input-pting | 243.3 ± 7.7 | 235.0 | 258.7 | 178.38 ± 23.09 |
| kcen | input-mattcl | 257.4 ± 5.9 | 249.5 | 268.5 | 188.75 ± 24.09 |
| kcen | input-lanjian | 270.7 ± 5.9 | 264.2 | 284.4 | 198.47 ± 25.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|