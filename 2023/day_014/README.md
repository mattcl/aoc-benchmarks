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
| mattcl | input-pting | 5.0 ± 0.5 | 4.2 | 7.9 | 1.00 |
| mattcl | input-lanjian | 5.3 ± 0.4 | 4.4 | 6.4 | 1.05 ± 0.14 |
| mattcl | input-kcen | 5.8 ± 0.6 | 4.9 | 9.6 | 1.14 ± 0.17 |
| mattcl | input-mattcl | 6.0 ± 2.6 | 5.0 | 42.1 | 1.19 ± 0.53 |
| lanjian | input-pting | 18.1 ± 0.7 | 17.0 | 21.0 | 3.59 ± 0.40 |
| lanjian | input-lanjian | 19.1 ± 0.9 | 17.9 | 22.5 | 3.79 ± 0.44 |
| lanjian | input-kcen | 21.3 ± 0.8 | 20.5 | 24.4 | 4.23 ± 0.47 |
| lanjian | input-mattcl | 23.5 ± 0.8 | 22.5 | 27.4 | 4.66 ± 0.52 |
| mattcl-py | input-pting | 156.0 ± 1.7 | 152.8 | 159.9 | 30.93 ± 3.29 |
| mattcl-py | input-lanjian | 172.1 ± 7.2 | 167.2 | 194.6 | 34.12 ± 3.88 |
| pting | input-pting | 181.5 ± 16.5 | 174.3 | 243.0 | 35.98 ± 5.03 |
| pting | input-lanjian | 193.1 ± 3.4 | 188.5 | 200.2 | 38.28 ± 4.11 |
| mattcl-py | input-kcen | 195.8 ± 1.9 | 192.5 | 199.2 | 38.81 ± 4.13 |
| mattcl-py | input-mattcl | 206.6 ± 3.3 | 201.7 | 213.1 | 40.97 ± 4.39 |
| pting | input-kcen | 225.5 ± 2.0 | 222.1 | 229.1 | 44.72 ± 4.75 |
| pting | input-mattcl | 240.2 ± 3.5 | 232.9 | 246.2 | 47.62 ± 5.09 |
| kcen | input-pting | 566.0 ± 6.0 | 559.2 | 573.8 | 112.22 ± 11.94 |
| kcen | input-lanjian | 630.4 ± 8.1 | 621.9 | 640.4 | 125.00 ± 13.33 |
| kcen | input-kcen | 728.4 ± 6.6 | 719.7 | 735.2 | 144.42 ± 15.35 |
| kcen | input-mattcl | 799.8 ± 3.5 | 795.8 | 801.9 | 158.58 ± 16.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|