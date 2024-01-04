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
| mattcl | input-lanjian | 3.2 ± 0.3 | 2.3 | 5.8 | 1.00 |
| mattcl | input-pting | 3.2 ± 0.3 | 2.3 | 5.7 | 1.01 ± 0.14 |
| mattcl | input-kcen | 3.5 ± 0.3 | 3.0 | 5.7 | 1.11 ± 0.15 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.1 | 7.0 | 1.24 ± 0.18 |
| lanjian | input-pting | 18.1 ± 0.7 | 16.9 | 20.4 | 5.73 ± 0.59 |
| lanjian | input-lanjian | 19.1 ± 0.7 | 18.1 | 22.7 | 6.06 ± 0.63 |
| lanjian | input-kcen | 21.3 ± 0.7 | 20.4 | 24.5 | 6.77 ± 0.69 |
| lanjian | input-mattcl | 23.5 ± 0.7 | 22.6 | 26.5 | 7.45 ± 0.76 |
| mattcl-py | input-pting | 154.0 ± 1.4 | 151.6 | 157.7 | 48.89 ± 4.77 |
| mattcl-py | input-lanjian | 168.8 ± 1.7 | 166.3 | 171.4 | 53.58 ± 5.23 |
| pting | input-pting | 174.4 ± 1.6 | 172.3 | 177.8 | 55.36 ± 5.40 |
| pting | input-lanjian | 192.3 ± 7.4 | 185.3 | 216.9 | 61.05 ± 6.38 |
| mattcl-py | input-kcen | 194.8 ± 1.4 | 192.2 | 196.7 | 61.83 ± 6.02 |
| mattcl-py | input-mattcl | 205.1 ± 3.7 | 200.5 | 212.7 | 65.09 ± 6.43 |
| pting | input-kcen | 222.1 ± 3.8 | 217.3 | 229.7 | 70.50 ± 6.95 |
| pting | input-mattcl | 235.1 ± 3.1 | 230.5 | 240.1 | 74.63 ± 7.31 |
| kcen | input-pting | 569.3 ± 4.9 | 563.9 | 573.7 | 180.69 ± 17.62 |
| kcen | input-lanjian | 629.1 ± 13.5 | 617.2 | 648.3 | 199.66 ± 19.86 |
| kcen | input-kcen | 733.2 ± 7.4 | 724.9 | 741.9 | 232.70 ± 22.72 |
| kcen | input-mattcl | 798.6 ± 3.6 | 794.8 | 802.0 | 253.45 ± 24.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|