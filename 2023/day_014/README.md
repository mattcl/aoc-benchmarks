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
| mattcl | input-pting | 3.1 ± 0.2 | 2.1 | 3.9 | 1.00 |
| mattcl | input-lanjian | 3.2 ± 0.4 | 2.4 | 5.8 | 1.02 ± 0.14 |
| mattcl | input-kcen | 3.5 ± 0.5 | 2.7 | 6.8 | 1.13 ± 0.18 |
| mattcl | input-mattcl | 4.0 ± 0.4 | 3.2 | 5.4 | 1.30 ± 0.15 |
| lanjian | input-pting | 18.6 ± 0.8 | 17.6 | 22.4 | 6.00 ± 0.54 |
| lanjian | input-lanjian | 19.3 ± 0.9 | 18.1 | 22.7 | 6.24 ± 0.56 |
| lanjian | input-kcen | 21.8 ± 0.7 | 20.3 | 24.6 | 7.03 ± 0.58 |
| lanjian | input-mattcl | 23.8 ± 0.8 | 22.8 | 26.6 | 7.68 ± 0.64 |
| mattcl-py | input-pting | 155.6 ± 1.9 | 151.9 | 159.9 | 50.22 ± 3.90 |
| mattcl-py | input-lanjian | 169.0 ± 3.3 | 164.8 | 176.1 | 54.54 ± 4.32 |
| pting | input-pting | 177.1 ± 2.9 | 172.8 | 182.2 | 57.15 ± 4.48 |
| mattcl-py | input-kcen | 194.2 ± 3.9 | 190.2 | 205.2 | 62.67 ± 4.97 |
| pting | input-lanjian | 194.8 ± 17.8 | 183.9 | 258.4 | 62.89 ± 7.51 |
| mattcl-py | input-mattcl | 203.3 ± 1.5 | 200.7 | 205.1 | 65.62 ± 5.06 |
| pting | input-kcen | 224.9 ± 5.5 | 216.4 | 236.4 | 72.58 ± 5.85 |
| pting | input-mattcl | 238.3 ± 3.6 | 232.3 | 243.0 | 76.91 ± 6.02 |
| kcen | input-pting | 604.0 ± 33.4 | 587.2 | 663.7 | 194.96 ± 18.45 |
| kcen | input-lanjian | 640.0 ± 6.0 | 631.7 | 645.7 | 206.56 ± 15.98 |
| kcen | input-kcen | 757.2 ± 4.0 | 752.6 | 760.2 | 244.41 ± 18.81 |
| kcen | input-mattcl | 825.9 ± 16.6 | 812.3 | 844.4 | 266.56 ± 21.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|