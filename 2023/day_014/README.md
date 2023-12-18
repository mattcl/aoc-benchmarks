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
| mattcl | input-pting | 3.0 ± 0.4 | 2.0 | 5.7 | 1.00 |
| mattcl | input-lanjian | 3.0 ± 0.3 | 2.1 | 5.9 | 1.00 ± 0.16 |
| mattcl | input-kcen | 3.4 ± 0.5 | 2.6 | 6.3 | 1.13 ± 0.21 |
| mattcl | input-mattcl | 3.8 ± 0.4 | 3.0 | 6.2 | 1.27 ± 0.21 |
| lanjian | input-pting | 18.1 ± 0.8 | 17.1 | 21.5 | 6.06 ± 0.77 |
| lanjian | input-lanjian | 19.0 ± 0.9 | 18.0 | 23.0 | 6.37 ± 0.81 |
| lanjian | input-kcen | 21.3 ± 0.6 | 20.4 | 23.6 | 7.14 ± 0.87 |
| lanjian | input-mattcl | 23.5 ± 0.8 | 22.6 | 26.9 | 7.87 ± 0.97 |
| mattcl-py | input-pting | 156.0 ± 2.2 | 151.9 | 160.1 | 52.24 ± 6.24 |
| mattcl-py | input-lanjian | 169.9 ± 2.6 | 166.2 | 177.8 | 56.89 ± 6.81 |
| pting | input-pting | 177.1 ± 10.6 | 170.2 | 217.2 | 59.30 ± 7.88 |
| pting | input-lanjian | 191.9 ± 2.7 | 186.4 | 197.5 | 64.26 ± 7.68 |
| mattcl-py | input-kcen | 196.2 ± 2.5 | 193.1 | 202.5 | 65.72 ± 7.84 |
| mattcl-py | input-mattcl | 205.1 ± 2.6 | 202.1 | 209.4 | 68.70 ± 8.20 |
| pting | input-kcen | 230.3 ± 23.2 | 217.3 | 305.7 | 77.12 ± 12.01 |
| pting | input-mattcl | 239.4 ± 3.7 | 233.2 | 244.9 | 80.17 ± 9.59 |
| kcen | input-pting | 567.2 ± 3.7 | 562.0 | 570.9 | 189.96 ± 22.58 |
| kcen | input-lanjian | 619.6 ± 6.5 | 613.8 | 628.7 | 207.50 ± 24.72 |
| kcen | input-kcen | 733.8 ± 12.2 | 725.7 | 751.9 | 245.76 ± 29.45 |
| kcen | input-mattcl | 796.0 ± 2.0 | 793.9 | 797.8 | 266.58 ± 31.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|