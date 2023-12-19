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
| mattcl | input-pting | 3.1 ± 0.2 | 2.4 | 4.7 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.4 | 2.3 | 5.2 | 1.02 ± 0.14 |
| mattcl | input-kcen | 3.5 ± 0.3 | 2.9 | 5.0 | 1.14 ± 0.13 |
| mattcl | input-mattcl | 4.0 ± 0.4 | 3.2 | 7.8 | 1.30 ± 0.18 |
| lanjian | input-pting | 18.9 ± 0.7 | 17.9 | 21.9 | 6.13 ± 0.54 |
| lanjian | input-lanjian | 19.9 ± 0.9 | 18.5 | 23.3 | 6.46 ± 0.60 |
| lanjian | input-kcen | 22.4 ± 0.8 | 21.1 | 26.1 | 7.27 ± 0.63 |
| lanjian | input-mattcl | 24.5 ± 0.8 | 23.3 | 27.3 | 7.96 ± 0.68 |
| mattcl-py | input-pting | 156.5 ± 2.2 | 153.9 | 161.3 | 50.87 ± 4.13 |
| mattcl-py | input-lanjian | 170.3 ± 1.6 | 167.5 | 174.0 | 55.34 ± 4.46 |
| pting | input-pting | 181.2 ± 10.8 | 171.9 | 220.1 | 58.87 ± 5.87 |
| pting | input-lanjian | 193.0 ± 3.6 | 188.1 | 199.2 | 62.71 ± 5.15 |
| mattcl-py | input-kcen | 198.3 ± 3.5 | 194.5 | 205.3 | 64.46 ± 5.28 |
| mattcl-py | input-mattcl | 205.8 ± 2.7 | 201.6 | 211.4 | 66.87 ± 5.42 |
| pting | input-kcen | 226.8 ± 3.7 | 219.1 | 232.2 | 73.69 ± 6.02 |
| pting | input-mattcl | 239.1 ± 4.4 | 232.5 | 247.1 | 77.71 ± 6.38 |
| kcen | input-pting | 570.5 ± 8.3 | 561.2 | 578.6 | 185.39 ± 15.07 |
| kcen | input-lanjian | 629.6 ± 6.1 | 622.2 | 636.5 | 204.63 ± 16.48 |
| kcen | input-kcen | 740.7 ± 8.4 | 732.7 | 752.4 | 240.71 ± 19.44 |
| kcen | input-mattcl | 798.1 ± 12.2 | 784.1 | 806.0 | 259.38 ± 21.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|