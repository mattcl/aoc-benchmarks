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
| mattcl | input-pting | 3.1 ± 0.2 | 2.3 | 4.2 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.3 | 2.3 | 4.9 | 1.01 ± 0.12 |
| mattcl | input-kcen | 3.4 ± 0.5 | 2.4 | 6.6 | 1.11 ± 0.19 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.0 | 5.1 | 1.25 ± 0.15 |
| lanjian | input-pting | 18.2 ± 0.8 | 17.3 | 21.6 | 5.90 ± 0.51 |
| lanjian | input-lanjian | 19.0 ± 0.7 | 18.1 | 22.0 | 6.17 ± 0.51 |
| lanjian | input-kcen | 21.4 ± 0.8 | 20.5 | 24.5 | 6.96 ± 0.57 |
| lanjian | input-mattcl | 23.6 ± 0.9 | 22.5 | 27.0 | 7.66 ± 0.63 |
| mattcl-py | input-pting | 161.9 ± 29.0 | 151.9 | 281.2 | 52.53 ± 10.16 |
| mattcl-py | input-lanjian | 169.2 ± 2.8 | 165.7 | 176.7 | 54.90 ± 4.11 |
| pting | input-pting | 178.8 ± 2.9 | 175.0 | 184.1 | 58.02 ± 4.34 |
| pting | input-lanjian | 194.1 ± 3.6 | 189.1 | 199.8 | 63.00 ± 4.75 |
| mattcl-py | input-kcen | 195.4 ± 2.4 | 193.2 | 203.0 | 63.40 ± 4.70 |
| mattcl-py | input-mattcl | 206.2 ± 5.8 | 201.4 | 223.2 | 66.91 ± 5.23 |
| pting | input-kcen | 226.8 ± 2.1 | 222.5 | 230.3 | 73.59 ± 5.42 |
| pting | input-mattcl | 240.4 ± 3.1 | 234.2 | 245.6 | 78.01 ± 5.79 |
| kcen | input-pting | 566.8 ± 3.0 | 562.3 | 569.8 | 183.93 ± 13.47 |
| kcen | input-lanjian | 623.9 ± 3.6 | 618.9 | 627.4 | 202.47 ± 14.84 |
| kcen | input-kcen | 739.4 ± 10.0 | 733.5 | 750.9 | 239.94 ± 17.83 |
| kcen | input-mattcl | 800.4 ± 4.2 | 797.0 | 805.0 | 259.72 ± 19.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|