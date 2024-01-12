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
| mattcl | input-kcen | 1.4 ± 0.1 | 1.1 | 1.8 | 1.00 |
| mattcl | input-pting | 1.4 ± 0.2 | 1.2 | 1.8 | 1.02 ± 0.16 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.2 | 1.8 | 1.05 ± 0.17 |
| mattcl | input-lanjian | 1.5 ± 0.1 | 1.2 | 1.8 | 1.08 ± 0.16 |
| lanjian | input-kcen | 1.8 ± 0.1 | 1.7 | 2.2 | 1.35 ± 0.16 |
| lanjian | input-lanjian | 2.0 ± 0.3 | 1.7 | 4.2 | 1.44 ± 0.24 |
| lanjian | input-mattcl | 2.1 ± 0.2 | 1.8 | 2.5 | 1.54 ± 0.22 |
| lanjian | input-pting | 2.2 ± 0.2 | 1.9 | 2.6 | 1.62 ± 0.24 |
| pting | input-kcen | 67.3 ± 1.3 | 65.3 | 71.1 | 49.54 ± 5.50 |
| pting | input-lanjian | 68.6 ± 1.2 | 66.8 | 72.5 | 50.43 ± 5.60 |
| pting | input-mattcl | 68.6 ± 1.0 | 66.7 | 70.8 | 50.45 ± 5.57 |
| pting | input-pting | 70.1 ± 1.1 | 68.3 | 72.9 | 51.53 ± 5.70 |
| mattcl-py | input-kcen | 90.9 ± 1.6 | 87.9 | 96.6 | 66.84 ± 7.41 |
| mattcl-py | input-lanjian | 93.1 ± 1.5 | 90.4 | 98.3 | 68.52 ± 7.59 |
| mattcl-py | input-mattcl | 93.7 ± 1.1 | 91.6 | 95.6 | 68.90 ± 7.58 |
| mattcl-py | input-pting | 97.4 ± 2.6 | 93.9 | 105.4 | 71.68 ± 8.07 |
| kcen | input-kcen | 230.6 ± 3.9 | 224.3 | 236.1 | 169.64 ± 18.79 |
| kcen | input-pting | 238.2 ± 4.9 | 233.7 | 247.8 | 175.20 ± 19.52 |
| kcen | input-mattcl | 256.9 ± 8.0 | 247.5 | 270.8 | 188.97 ± 21.52 |
| kcen | input-lanjian | 271.8 ± 3.6 | 266.6 | 277.5 | 199.92 ± 22.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|