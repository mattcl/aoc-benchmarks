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
| mattcl | input-kcen | 1.3 ± 0.2 | 1.1 | 1.7 | 1.00 |
| mattcl | input-pting | 1.4 ± 0.2 | 1.1 | 2.7 | 1.05 ± 0.19 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.1 | 2.1 | 1.05 ± 0.18 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 1.8 | 1.09 ± 0.19 |
| lanjian | input-kcen | 1.8 ± 0.1 | 1.6 | 2.2 | 1.40 ± 0.20 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.6 | 2.3 | 1.40 ± 0.20 |
| lanjian | input-mattcl | 2.0 ± 0.2 | 1.7 | 2.6 | 1.56 ± 0.25 |
| lanjian | input-pting | 2.1 ± 0.2 | 1.8 | 3.0 | 1.62 ± 0.27 |
| pting | input-kcen | 66.3 ± 1.0 | 64.6 | 69.7 | 51.33 ± 6.35 |
| pting | input-lanjian | 67.5 ± 1.1 | 65.2 | 70.0 | 52.27 ± 6.47 |
| pting | input-mattcl | 68.0 ± 1.1 | 66.3 | 71.4 | 52.66 ± 6.52 |
| pting | input-pting | 69.1 ± 0.8 | 67.9 | 70.9 | 53.55 ± 6.60 |
| mattcl-py | input-kcen | 89.4 ± 1.2 | 87.5 | 91.9 | 69.22 ± 8.55 |
| mattcl-py | input-lanjian | 91.9 ± 1.1 | 89.9 | 93.8 | 71.21 ± 8.78 |
| mattcl-py | input-mattcl | 92.5 ± 1.5 | 89.6 | 97.0 | 71.66 ± 8.88 |
| mattcl-py | input-pting | 95.3 ± 1.0 | 93.5 | 98.4 | 73.84 ± 9.10 |
| kcen | input-kcen | 228.6 ± 4.5 | 220.9 | 234.8 | 177.09 ± 22.02 |
| kcen | input-pting | 234.8 ± 4.7 | 229.8 | 244.1 | 181.86 ± 22.62 |
| kcen | input-mattcl | 255.4 ± 2.6 | 248.5 | 258.1 | 197.83 ± 24.36 |
| kcen | input-lanjian | 267.3 ± 6.8 | 259.6 | 279.5 | 207.10 ± 25.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|