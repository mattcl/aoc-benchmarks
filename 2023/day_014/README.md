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
| mattcl | input-pting | 3.0 ± 0.4 | 2.2 | 5.8 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.5 | 2.1 | 5.7 | 1.01 ± 0.21 |
| mattcl | input-kcen | 3.4 ± 0.3 | 3.0 | 5.1 | 1.12 ± 0.16 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.1 | 6.0 | 1.28 ± 0.21 |
| lanjian | input-pting | 18.3 ± 0.7 | 17.4 | 21.6 | 6.07 ± 0.79 |
| lanjian | input-lanjian | 19.3 ± 0.7 | 18.1 | 22.1 | 6.41 ± 0.83 |
| lanjian | input-kcen | 21.7 ± 0.9 | 20.6 | 24.5 | 7.21 ± 0.94 |
| lanjian | input-mattcl | 23.8 ± 0.9 | 22.7 | 26.7 | 7.89 ± 1.02 |
| mattcl-py | input-pting | 156.8 ± 7.7 | 150.9 | 187.8 | 52.06 ± 6.96 |
| mattcl-py | input-lanjian | 167.9 ± 1.8 | 163.5 | 170.5 | 55.76 ± 6.95 |
| pting | input-pting | 176.7 ± 2.1 | 172.9 | 180.3 | 58.69 ± 7.32 |
| mattcl-py | input-kcen | 195.8 ± 3.6 | 190.3 | 203.7 | 65.02 ± 8.16 |
| pting | input-lanjian | 196.6 ± 19.5 | 187.6 | 266.0 | 65.30 ± 10.37 |
| mattcl-py | input-mattcl | 203.0 ± 2.7 | 199.5 | 208.4 | 67.43 ± 8.42 |
| pting | input-kcen | 225.2 ± 4.1 | 215.7 | 230.7 | 74.80 ± 9.39 |
| pting | input-mattcl | 237.1 ± 2.9 | 232.1 | 241.9 | 78.76 ± 9.83 |
| kcen | input-pting | 588.7 ± 7.0 | 576.2 | 593.0 | 195.52 ± 24.39 |
| kcen | input-lanjian | 645.1 ± 8.5 | 636.2 | 656.6 | 214.25 ± 26.76 |
| kcen | input-kcen | 761.2 ± 4.5 | 757.4 | 766.2 | 252.81 ± 31.43 |
| kcen | input-mattcl | 833.2 ± 2.4 | 831.6 | 836.1 | 276.75 ± 34.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|