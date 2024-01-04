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
| mattcl | input-lanjian | 3.1 ± 0.2 | 2.7 | 4.2 | 1.00 |
| mattcl | input-pting | 3.1 ± 0.4 | 2.3 | 5.7 | 1.01 ± 0.15 |
| mattcl | input-kcen | 3.5 ± 0.5 | 2.8 | 6.8 | 1.14 ± 0.17 |
| mattcl | input-mattcl | 4.0 ± 0.5 | 3.2 | 7.5 | 1.31 ± 0.19 |
| lanjian | input-pting | 18.4 ± 0.8 | 17.3 | 21.3 | 5.96 ± 0.49 |
| lanjian | input-lanjian | 19.2 ± 0.7 | 18.2 | 21.6 | 6.21 ± 0.48 |
| lanjian | input-kcen | 21.7 ± 0.8 | 20.5 | 25.8 | 7.04 ± 0.55 |
| lanjian | input-mattcl | 23.8 ± 0.9 | 22.6 | 27.1 | 7.69 ± 0.60 |
| mattcl-py | input-pting | 156.0 ± 2.6 | 151.6 | 160.1 | 50.51 ± 3.58 |
| mattcl-py | input-lanjian | 168.1 ± 1.9 | 164.3 | 171.5 | 54.42 ± 3.80 |
| pting | input-pting | 178.3 ± 4.0 | 172.8 | 189.1 | 57.73 ± 4.18 |
| pting | input-lanjian | 192.7 ± 3.9 | 186.7 | 199.5 | 62.40 ± 4.49 |
| mattcl-py | input-kcen | 201.1 ± 8.0 | 192.4 | 220.0 | 65.11 ± 5.18 |
| mattcl-py | input-mattcl | 204.7 ± 3.2 | 198.6 | 210.6 | 66.28 ± 4.68 |
| pting | input-kcen | 226.0 ± 8.6 | 219.5 | 253.0 | 73.18 ± 5.76 |
| pting | input-mattcl | 239.2 ± 4.8 | 229.8 | 245.6 | 77.45 ± 5.56 |
| kcen | input-pting | 566.4 ± 5.3 | 559.7 | 572.0 | 183.38 ± 12.76 |
| kcen | input-lanjian | 629.5 ± 6.9 | 619.9 | 636.1 | 203.81 ± 14.23 |
| kcen | input-kcen | 739.0 ± 1.6 | 737.1 | 740.7 | 239.25 ± 16.50 |
| kcen | input-mattcl | 809.9 ± 8.7 | 799.9 | 815.5 | 262.20 ± 18.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|