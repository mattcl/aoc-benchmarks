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
| lanjian | input-kcen | 1.8 ± 0.2 | 1.6 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.5 | 1.00 ± 0.11 |
| lanjian | input-mattcl | 1.9 ± 0.2 | 1.7 | 2.5 | 1.05 ± 0.15 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.7 | 2.5 | 1.08 ± 0.15 |
| mattcl | input-kcen | 2.3 ± 0.2 | 1.9 | 3.1 | 1.26 ± 0.17 |
| mattcl | input-lanjian | 2.4 ± 0.2 | 2.0 | 3.0 | 1.30 ± 0.16 |
| mattcl | input-mattcl | 2.5 ± 0.3 | 2.0 | 4.8 | 1.35 ± 0.19 |
| mattcl | input-pting | 2.5 ± 0.2 | 2.0 | 3.6 | 1.35 ± 0.17 |
| pting | input-kcen | 66.6 ± 1.1 | 64.2 | 69.0 | 36.27 ± 3.16 |
| pting | input-lanjian | 68.0 ± 1.2 | 65.8 | 71.9 | 37.08 ± 3.23 |
| pting | input-mattcl | 68.6 ± 1.5 | 66.4 | 72.4 | 37.38 ± 3.30 |
| pting | input-pting | 69.6 ± 1.2 | 67.6 | 72.9 | 37.95 ± 3.32 |
| mattcl-py | input-kcen | 89.4 ± 1.3 | 87.1 | 92.5 | 48.70 ± 4.23 |
| mattcl-py | input-lanjian | 91.4 ± 1.1 | 89.6 | 93.5 | 49.79 ± 4.30 |
| mattcl-py | input-mattcl | 91.7 ± 1.2 | 89.2 | 94.6 | 49.99 ± 4.32 |
| mattcl-py | input-pting | 94.2 ± 1.3 | 91.3 | 96.7 | 51.31 ± 4.45 |
| kcen | input-kcen | 234.5 ± 4.3 | 227.2 | 239.6 | 127.79 ± 11.19 |
| kcen | input-pting | 235.1 ± 2.7 | 229.1 | 239.0 | 128.12 ± 11.06 |
| kcen | input-mattcl | 255.0 ± 4.2 | 246.1 | 259.6 | 138.94 ± 12.11 |
| kcen | input-lanjian | 270.8 ± 7.3 | 261.6 | 286.1 | 147.57 ± 13.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|