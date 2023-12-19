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
| mattcl | input-pting | 3.0 ± 0.3 | 2.2 | 5.6 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.4 | 2.1 | 6.2 | 1.03 ± 0.18 |
| mattcl | input-kcen | 3.5 ± 0.4 | 3.0 | 5.8 | 1.16 ± 0.18 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.0 | 7.1 | 1.30 ± 0.20 |
| lanjian | input-pting | 18.9 ± 0.8 | 17.9 | 22.6 | 6.35 ± 0.70 |
| lanjian | input-lanjian | 19.7 ± 0.7 | 18.4 | 22.7 | 6.60 ± 0.70 |
| lanjian | input-kcen | 22.1 ± 0.7 | 21.1 | 26.0 | 7.42 ± 0.78 |
| lanjian | input-mattcl | 24.5 ± 0.8 | 23.2 | 27.6 | 8.21 ± 0.87 |
| mattcl-py | input-pting | 156.4 ± 2.0 | 153.3 | 159.3 | 52.42 ± 5.32 |
| mattcl-py | input-lanjian | 169.6 ± 2.1 | 166.8 | 173.6 | 56.84 ± 5.77 |
| pting | input-pting | 178.7 ± 3.0 | 175.2 | 185.8 | 59.90 ± 6.11 |
| pting | input-lanjian | 194.8 ± 3.7 | 187.3 | 200.4 | 65.30 ± 6.69 |
| mattcl-py | input-kcen | 196.3 ± 2.2 | 193.4 | 200.6 | 65.79 ± 6.66 |
| mattcl-py | input-mattcl | 205.8 ± 1.8 | 202.3 | 209.6 | 68.99 ± 6.97 |
| pting | input-kcen | 227.8 ± 6.3 | 220.2 | 246.7 | 76.34 ± 7.97 |
| pting | input-mattcl | 241.5 ± 3.3 | 235.9 | 246.4 | 80.94 ± 8.22 |
| kcen | input-pting | 573.2 ± 5.6 | 563.8 | 578.0 | 192.14 ± 19.44 |
| kcen | input-lanjian | 634.5 ± 5.9 | 629.5 | 642.9 | 212.70 ± 21.50 |
| kcen | input-kcen | 736.8 ± 3.3 | 733.7 | 741.0 | 246.96 ± 24.89 |
| kcen | input-mattcl | 804.5 ± 8.7 | 796.3 | 813.7 | 269.66 ± 27.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|