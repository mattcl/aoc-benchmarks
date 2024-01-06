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
| mattcl | input-pting | 3.1 ± 0.3 | 2.3 | 4.6 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.3 | 2.4 | 5.9 | 1.02 ± 0.13 |
| mattcl | input-kcen | 3.5 ± 0.3 | 3.0 | 5.2 | 1.14 ± 0.15 |
| mattcl | input-mattcl | 4.1 ± 0.4 | 3.5 | 6.3 | 1.33 ± 0.18 |
| lanjian | input-pting | 18.7 ± 0.9 | 17.6 | 22.3 | 6.04 ± 0.62 |
| lanjian | input-lanjian | 19.5 ± 0.7 | 18.4 | 22.5 | 6.29 ± 0.61 |
| lanjian | input-kcen | 22.1 ± 0.8 | 21.0 | 24.9 | 7.13 ± 0.69 |
| lanjian | input-mattcl | 23.9 ± 1.9 | 22.5 | 43.1 | 7.72 ± 0.93 |
| mattcl-py | input-pting | 156.3 ± 4.9 | 151.5 | 174.0 | 50.51 ± 4.84 |
| pting | input-pting | 176.8 ± 2.7 | 170.7 | 181.4 | 57.12 ± 5.24 |
| mattcl-py | input-lanjian | 178.0 ± 37.8 | 165.5 | 324.4 | 57.50 ± 13.28 |
| pting | input-lanjian | 191.5 ± 2.6 | 186.6 | 195.8 | 61.87 ± 5.67 |
| mattcl-py | input-kcen | 195.6 ± 2.7 | 192.7 | 201.5 | 63.20 ± 5.79 |
| mattcl-py | input-mattcl | 206.2 ± 4.6 | 201.3 | 219.0 | 66.63 ± 6.21 |
| pting | input-kcen | 224.3 ± 3.3 | 219.6 | 229.4 | 72.47 ± 6.65 |
| pting | input-mattcl | 239.5 ± 5.6 | 231.6 | 249.9 | 77.37 ± 7.23 |
| kcen | input-pting | 573.0 ± 3.5 | 569.5 | 578.5 | 185.10 ± 16.80 |
| kcen | input-lanjian | 631.6 ± 6.3 | 624.6 | 639.0 | 204.06 ± 18.60 |
| kcen | input-kcen | 737.4 ± 10.3 | 724.7 | 749.3 | 238.22 ± 21.83 |
| kcen | input-mattcl | 805.0 ± 3.0 | 801.9 | 808.0 | 260.06 ± 23.57 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|