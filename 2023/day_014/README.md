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
| mattcl | input-pting | 3.0 ± 0.3 | 2.3 | 4.4 | 1.00 |
| mattcl | input-lanjian | 3.5 ± 1.4 | 2.4 | 18.5 | 1.16 ± 0.49 |
| mattcl | input-kcen | 3.5 ± 0.3 | 2.7 | 4.7 | 1.18 ± 0.15 |
| mattcl | input-mattcl | 4.1 ± 0.3 | 3.1 | 5.2 | 1.35 ± 0.16 |
| lanjian | input-pting | 18.9 ± 0.6 | 18.1 | 22.1 | 6.29 ± 0.59 |
| lanjian | input-lanjian | 20.0 ± 0.7 | 19.1 | 23.4 | 6.68 ± 0.63 |
| lanjian | input-kcen | 22.6 ± 0.7 | 21.5 | 25.3 | 7.53 ± 0.71 |
| lanjian | input-mattcl | 24.8 ± 0.7 | 23.5 | 27.2 | 8.27 ± 0.76 |
| mattcl-py | input-pting | 171.0 ± 33.8 | 156.0 | 277.5 | 57.03 ± 12.34 |
| mattcl-py | input-lanjian | 173.1 ± 9.1 | 168.6 | 207.2 | 57.72 ± 5.91 |
| pting | input-pting | 179.2 ± 3.1 | 172.9 | 185.1 | 59.76 ± 5.36 |
| pting | input-lanjian | 194.0 ± 3.5 | 189.1 | 202.6 | 64.69 ± 5.81 |
| mattcl-py | input-kcen | 201.3 ± 3.7 | 197.1 | 208.9 | 67.15 ± 6.04 |
| mattcl-py | input-mattcl | 208.8 ± 3.1 | 204.1 | 217.0 | 69.64 ± 6.22 |
| pting | input-kcen | 246.6 ± 47.3 | 222.1 | 376.7 | 82.23 ± 17.36 |
| pting | input-mattcl | 261.8 ± 49.9 | 234.9 | 400.0 | 87.32 ± 18.32 |
| kcen | input-pting | 577.4 ± 2.7 | 573.4 | 580.3 | 192.58 ± 16.97 |
| kcen | input-lanjian | 645.0 ± 8.9 | 636.5 | 652.8 | 215.10 ± 19.17 |
| kcen | input-kcen | 821.1 ± 144.4 | 747.3 | 1037.7 | 273.85 ± 53.86 |
| kcen | input-mattcl | 910.0 ± 161.4 | 816.6 | 1096.3 | 303.49 ± 60.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|