# Day 14 benchmarks

[link to problem](https://adventofcode.com/2023/day/14)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 14)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 3.0 ± 0.3 | 2.1 | 5.8 | 1.00 |
| mattcl | input-lanjian | 3.0 ± 0.3 | 2.2 | 4.9 | 1.01 ± 0.14 |
| mattcl | input-kcen | 3.4 ± 0.4 | 2.9 | 5.8 | 1.13 ± 0.18 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.3 | 6.0 | 1.32 ± 0.20 |
| lanjian | input-pting | 18.6 ± 1.0 | 17.2 | 22.0 | 6.23 ± 0.73 |
| lanjian | input-lanjian | 19.3 ± 0.9 | 17.9 | 23.5 | 6.46 ± 0.74 |
| lanjian | input-kcen | 21.6 ± 0.7 | 20.4 | 24.7 | 7.24 ± 0.80 |
| lanjian | input-mattcl | 23.9 ± 1.0 | 22.4 | 26.8 | 8.02 ± 0.90 |
| mattcl-py | input-pting | 155.0 ± 2.1 | 150.9 | 158.7 | 51.98 ± 5.48 |
| mattcl-py | input-lanjian | 167.9 ± 2.6 | 163.9 | 174.0 | 56.31 ± 5.95 |
| pting | input-pting | 176.8 ± 3.1 | 171.7 | 181.5 | 59.28 ± 6.29 |
| pting | input-lanjian | 191.1 ± 2.9 | 186.7 | 197.1 | 64.08 ± 6.77 |
| mattcl-py | input-kcen | 193.6 ± 2.3 | 190.4 | 197.6 | 64.90 ± 6.83 |
| mattcl-py | input-mattcl | 204.8 ± 2.6 | 199.9 | 209.9 | 68.68 ± 7.24 |
| pting | input-kcen | 222.5 ± 5.1 | 216.2 | 233.3 | 74.61 ± 7.99 |
| pting | input-mattcl | 245.8 ± 26.8 | 234.4 | 330.5 | 82.43 ± 12.46 |
| kcen | input-pting | 595.1 ± 10.8 | 584.4 | 610.9 | 199.53 ± 21.18 |
| kcen | input-lanjian | 644.0 ± 4.5 | 638.0 | 648.0 | 215.95 ± 22.64 |
| kcen | input-kcen | 752.7 ± 9.1 | 740.4 | 760.2 | 252.41 ± 26.57 |
| kcen | input-mattcl | 826.8 ± 4.7 | 822.0 | 831.3 | 277.23 ± 29.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|