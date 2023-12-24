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
| mattcl | input-pting | 3.0 ± 0.2 | 2.1 | 3.5 | 1.00 |
| mattcl | input-kcen | 3.4 ± 0.3 | 2.7 | 5.1 | 1.14 ± 0.13 |
| mattcl | input-mattcl | 3.9 ± 0.3 | 3.1 | 6.1 | 1.29 ± 0.14 |
| mattcl | input-lanjian | 4.8 ± 0.7 | 2.8 | 8.7 | 1.61 ± 0.26 |
| lanjian | input-pting | 18.9 ± 0.8 | 17.9 | 21.8 | 6.30 ± 0.49 |
| lanjian | input-kcen | 23.6 ± 3.6 | 21.5 | 34.3 | 7.86 ± 1.30 |
| lanjian | input-mattcl | 24.3 ± 0.4 | 23.5 | 26.2 | 8.12 ± 0.56 |
| lanjian | input-lanjian | 32.2 ± 0.7 | 29.1 | 34.3 | 10.75 ± 0.75 |
| mattcl-py | input-pting | 172.4 ± 33.4 | 156.2 | 280.8 | 57.57 ± 11.77 |
| pting | input-pting | 180.0 ± 4.3 | 175.2 | 189.0 | 60.10 ± 4.21 |
| mattcl-py | input-kcen | 202.4 ± 3.5 | 195.1 | 207.5 | 67.57 ± 4.59 |
| mattcl-py | input-mattcl | 213.3 ± 2.7 | 209.9 | 218.5 | 71.22 ± 4.77 |
| pting | input-kcen | 227.7 ± 4.7 | 220.5 | 234.8 | 76.02 ± 5.24 |
| pting | input-mattcl | 265.3 ± 40.1 | 241.4 | 355.9 | 88.58 ± 14.61 |
| mattcl-py | input-lanjian | 351.9 ± 3.0 | 347.8 | 356.7 | 117.48 ± 7.79 |
| pting | input-lanjian | 370.1 ± 5.6 | 358.5 | 375.1 | 123.57 ± 8.34 |
| kcen | input-pting | 577.0 ± 7.4 | 567.6 | 585.3 | 192.65 ± 12.91 |
| kcen | input-kcen | 758.2 ± 8.8 | 751.4 | 768.1 | 253.16 ± 16.91 |
| kcen | input-lanjian | 935.8 ± 343.3 | 633.9 | 1338.3 | 312.46 ± 116.46 |
| kcen | input-mattcl | 1616.0 ± 100.8 | 1500.9 | 1688.7 | 539.53 ± 48.92 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|