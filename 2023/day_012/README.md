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
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.6 | 2.3 | 1.00 |
| lanjian | input-kcen | 1.8 ± 0.2 | 1.6 | 3.1 | 1.00 ± 0.12 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.5 | 1.09 ± 0.13 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 2.7 | 1.15 ± 0.14 |
| mattcl | input-kcen | 2.4 ± 0.2 | 1.9 | 3.0 | 1.30 ± 0.15 |
| mattcl | input-pting | 2.4 ± 0.2 | 2.0 | 3.5 | 1.33 ± 0.15 |
| mattcl | input-mattcl | 2.4 ± 0.2 | 2.0 | 3.2 | 1.33 ± 0.15 |
| mattcl | input-lanjian | 2.5 ± 0.4 | 1.9 | 5.3 | 1.35 ± 0.24 |
| pting | input-kcen | 66.4 ± 1.1 | 64.6 | 70.4 | 36.27 ± 2.61 |
| pting | input-lanjian | 67.5 ± 1.1 | 65.7 | 70.5 | 36.85 ± 2.66 |
| pting | input-mattcl | 67.9 ± 1.1 | 66.1 | 70.9 | 37.07 ± 2.66 |
| pting | input-pting | 69.4 ± 1.0 | 67.4 | 71.4 | 37.86 ± 2.71 |
| mattcl-py | input-kcen | 88.7 ± 1.2 | 86.8 | 91.9 | 48.40 ± 3.46 |
| mattcl-py | input-lanjian | 91.1 ± 1.3 | 89.1 | 93.9 | 49.72 ± 3.56 |
| mattcl-py | input-mattcl | 91.3 ± 1.1 | 89.5 | 93.3 | 49.82 ± 3.55 |
| mattcl-py | input-pting | 93.7 ± 1.1 | 91.7 | 96.5 | 51.15 ± 3.64 |
| kcen | input-kcen | 230.5 ± 4.3 | 224.9 | 238.2 | 125.85 ± 9.15 |
| kcen | input-pting | 235.0 ± 6.3 | 226.6 | 246.3 | 128.30 ± 9.64 |
| kcen | input-mattcl | 255.1 ± 3.5 | 245.6 | 258.6 | 139.26 ± 9.96 |
| kcen | input-lanjian | 270.0 ± 5.2 | 263.5 | 277.3 | 147.42 ± 10.73 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|