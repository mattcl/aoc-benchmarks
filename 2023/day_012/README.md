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
| lanjian | input-kcen | 2.2 ± 0.2 | 1.8 | 2.7 | 1.00 |
| lanjian | input-lanjian | 2.2 ± 0.2 | 1.9 | 2.6 | 1.02 ± 0.12 |
| lanjian | input-pting | 2.7 ± 0.5 | 2.1 | 7.4 | 1.23 ± 0.26 |
| mattcl | input-kcen | 2.7 ± 0.2 | 2.2 | 4.2 | 1.25 ± 0.16 |
| mattcl | input-lanjian | 2.8 ± 0.5 | 2.2 | 7.6 | 1.28 ± 0.26 |
| mattcl | input-pting | 3.3 ± 0.8 | 2.5 | 10.0 | 1.52 ± 0.40 |
| lanjian | input-mattcl | 3.8 ± 0.9 | 2.7 | 11.4 | 1.75 ± 0.43 |
| mattcl | input-mattcl | 5.5 ± 1.5 | 3.3 | 9.6 | 2.51 ± 0.74 |
| pting | input-pting | 71.8 ± 1.3 | 69.5 | 75.4 | 32.91 ± 3.18 |
| pting | input-kcen | 78.8 ± 25.3 | 68.5 | 168.4 | 36.13 ± 12.09 |
| pting | input-mattcl | 81.0 ± 3.9 | 74.3 | 88.7 | 37.13 ± 3.95 |
| pting | input-lanjian | 87.2 ± 26.4 | 69.5 | 173.9 | 39.97 ± 12.70 |
| mattcl-py | input-lanjian | 98.6 ± 1.8 | 95.6 | 102.8 | 45.20 ± 4.37 |
| mattcl-py | input-kcen | 98.7 ± 6.9 | 94.8 | 134.6 | 45.25 ± 5.33 |
| mattcl-py | input-pting | 126.1 ± 34.2 | 99.4 | 247.5 | 57.79 ± 16.62 |
| mattcl-py | input-mattcl | 129.9 ± 34.9 | 106.1 | 239.7 | 59.54 ± 16.96 |
| kcen | input-kcen | 247.1 ± 4.0 | 241.1 | 252.0 | 113.27 ± 10.91 |
| kcen | input-pting | 290.6 ± 8.6 | 276.8 | 300.6 | 133.21 ± 13.25 |
| kcen | input-lanjian | 293.2 ± 3.8 | 286.6 | 298.8 | 134.43 ± 12.88 |
| kcen | input-mattcl | 303.2 ± 7.8 | 290.2 | 319.0 | 139.01 ± 13.68 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|