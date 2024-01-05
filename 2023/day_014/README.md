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
| mattcl | input-pting | 3.0 ± 0.2 | 2.2 | 4.3 | 1.00 |
| mattcl | input-lanjian | 3.0 ± 0.4 | 2.2 | 5.9 | 1.00 ± 0.16 |
| mattcl | input-kcen | 3.4 ± 0.5 | 2.7 | 6.0 | 1.12 ± 0.18 |
| mattcl | input-mattcl | 3.9 ± 0.5 | 3.0 | 6.9 | 1.29 ± 0.19 |
| lanjian | input-pting | 18.0 ± 0.8 | 17.1 | 21.5 | 5.95 ± 0.53 |
| lanjian | input-lanjian | 18.9 ± 0.7 | 17.9 | 21.9 | 6.24 ± 0.54 |
| lanjian | input-kcen | 21.4 ± 0.6 | 20.4 | 23.9 | 7.05 ± 0.58 |
| lanjian | input-mattcl | 23.4 ± 0.6 | 22.5 | 26.2 | 7.73 ± 0.64 |
| mattcl-py | input-pting | 154.9 ± 1.8 | 152.1 | 158.6 | 51.07 ± 4.03 |
| mattcl-py | input-lanjian | 168.3 ± 1.9 | 164.8 | 172.4 | 55.47 ± 4.37 |
| pting | input-pting | 175.8 ± 2.7 | 170.7 | 180.2 | 57.96 ± 4.61 |
| pting | input-lanjian | 192.4 ± 3.2 | 187.6 | 197.0 | 63.42 ± 5.06 |
| mattcl-py | input-kcen | 196.7 ± 2.5 | 191.9 | 202.0 | 64.83 ± 5.12 |
| mattcl-py | input-mattcl | 205.1 ± 2.5 | 200.6 | 208.4 | 67.59 ± 5.34 |
| pting | input-kcen | 223.4 ± 3.5 | 217.3 | 229.7 | 73.65 ± 5.86 |
| pting | input-mattcl | 238.6 ± 4.0 | 232.2 | 246.0 | 78.64 ± 6.28 |
| kcen | input-pting | 565.6 ± 3.7 | 560.2 | 569.1 | 186.44 ± 14.60 |
| kcen | input-lanjian | 627.8 ± 12.0 | 615.1 | 644.0 | 206.94 ± 16.63 |
| kcen | input-kcen | 732.2 ± 9.6 | 723.3 | 745.8 | 241.33 ± 19.10 |
| kcen | input-mattcl | 800.7 ± 11.2 | 790.2 | 812.4 | 263.92 ± 20.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|