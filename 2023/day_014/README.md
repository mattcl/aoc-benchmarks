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
| mattcl | input-pting | 3.0 ± 0.3 | 2.2 | 5.0 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.3 | 2.2 | 4.6 | 1.01 ± 0.13 |
| mattcl | input-kcen | 3.5 ± 0.4 | 2.7 | 6.6 | 1.14 ± 0.18 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.1 | 6.6 | 1.29 ± 0.18 |
| lanjian | input-pting | 18.9 ± 0.9 | 17.6 | 22.6 | 6.22 ± 0.62 |
| lanjian | input-lanjian | 19.8 ± 0.8 | 18.8 | 23.1 | 6.51 ± 0.63 |
| lanjian | input-kcen | 22.3 ± 0.8 | 21.1 | 26.5 | 7.34 ± 0.70 |
| lanjian | input-mattcl | 24.6 ± 0.9 | 23.3 | 27.6 | 8.08 ± 0.77 |
| mattcl-py | input-pting | 156.0 ± 2.0 | 152.0 | 159.2 | 51.34 ± 4.57 |
| mattcl-py | input-lanjian | 168.1 ± 2.1 | 164.8 | 172.7 | 55.32 ± 4.92 |
| pting | input-pting | 177.4 ± 3.2 | 171.2 | 183.0 | 58.38 ± 5.25 |
| pting | input-lanjian | 194.2 ± 6.8 | 188.8 | 217.1 | 63.89 ± 6.06 |
| mattcl-py | input-kcen | 197.7 ± 6.0 | 191.3 | 213.4 | 65.07 ± 6.06 |
| mattcl-py | input-mattcl | 206.9 ± 5.7 | 199.6 | 222.4 | 68.09 ± 6.28 |
| pting | input-kcen | 225.0 ± 3.3 | 219.4 | 231.4 | 74.03 ± 6.61 |
| pting | input-mattcl | 237.9 ± 5.0 | 232.7 | 246.4 | 78.28 ± 7.08 |
| kcen | input-pting | 563.8 ± 3.2 | 558.3 | 566.3 | 185.53 ± 16.36 |
| kcen | input-lanjian | 623.6 ± 13.4 | 612.5 | 640.9 | 205.18 ± 18.59 |
| kcen | input-kcen | 732.4 ± 6.4 | 725.5 | 739.2 | 241.00 ± 21.31 |
| kcen | input-mattcl | 802.2 ± 4.5 | 797.2 | 805.8 | 263.97 ± 23.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|