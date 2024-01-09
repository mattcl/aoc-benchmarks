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
| mattcl | input-lanjian | 3.4 ± 0.4 | 2.6 | 6.8 | 1.00 |
| mattcl | input-pting | 3.4 ± 0.5 | 2.5 | 6.0 | 1.01 ± 0.19 |
| mattcl | input-kcen | 3.7 ± 0.4 | 3.3 | 5.4 | 1.11 ± 0.20 |
| mattcl | input-mattcl | 4.2 ± 0.5 | 3.4 | 7.2 | 1.24 ± 0.21 |
| lanjian | input-pting | 19.2 ± 0.8 | 18.1 | 22.3 | 5.66 ± 0.78 |
| lanjian | input-lanjian | 20.1 ± 0.8 | 19.0 | 23.5 | 5.92 ± 0.82 |
| lanjian | input-kcen | 22.6 ± 0.9 | 21.3 | 26.5 | 6.65 ± 0.91 |
| lanjian | input-mattcl | 24.7 ± 1.0 | 23.4 | 27.9 | 7.27 ± 1.00 |
| mattcl-py | input-pting | 154.6 ± 1.8 | 150.8 | 158.6 | 45.59 ± 6.02 |
| mattcl-py | input-lanjian | 167.6 ± 1.5 | 164.8 | 170.9 | 49.42 ± 6.51 |
| pting | input-pting | 175.5 ± 3.2 | 169.9 | 182.0 | 51.73 ± 6.86 |
| pting | input-lanjian | 193.4 ± 7.3 | 187.0 | 219.0 | 57.02 ± 7.80 |
| mattcl-py | input-kcen | 197.9 ± 3.8 | 193.2 | 204.6 | 58.35 ± 7.75 |
| mattcl-py | input-mattcl | 208.2 ± 7.0 | 203.3 | 224.9 | 61.38 ± 8.33 |
| pting | input-kcen | 224.7 ± 3.9 | 218.9 | 230.7 | 66.24 ± 8.78 |
| pting | input-mattcl | 240.0 ± 4.4 | 232.2 | 246.7 | 70.78 ± 9.39 |
| kcen | input-pting | 574.6 ± 1.9 | 572.6 | 576.5 | 169.42 ± 22.28 |
| kcen | input-lanjian | 628.4 ± 14.9 | 610.7 | 646.8 | 185.29 ± 24.75 |
| kcen | input-kcen | 733.7 ± 8.5 | 725.5 | 744.2 | 216.34 ± 28.55 |
| kcen | input-mattcl | 813.8 ± 11.4 | 801.2 | 823.5 | 239.96 ± 31.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|