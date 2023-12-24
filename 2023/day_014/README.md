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
| mattcl | input-lanjian | 3.1 ± 0.3 | 2.4 | 4.7 | 1.00 |
| mattcl | input-pting | 3.2 ± 0.4 | 2.3 | 5.7 | 1.02 ± 0.16 |
| mattcl | input-kcen | 3.5 ± 0.4 | 2.9 | 5.1 | 1.12 ± 0.17 |
| mattcl | input-mattcl | 4.0 ± 0.5 | 3.2 | 7.7 | 1.29 ± 0.20 |
| lanjian | input-pting | 18.8 ± 0.7 | 17.5 | 21.6 | 6.01 ± 0.62 |
| lanjian | input-lanjian | 19.6 ± 0.7 | 18.6 | 23.1 | 6.27 ± 0.64 |
| lanjian | input-kcen | 22.2 ± 1.0 | 20.8 | 25.9 | 7.10 ± 0.75 |
| lanjian | input-mattcl | 24.5 ± 0.8 | 23.4 | 27.9 | 7.83 ± 0.80 |
| mattcl-py | input-pting | 156.6 ± 8.0 | 151.6 | 188.8 | 50.11 ± 5.45 |
| mattcl-py | input-lanjian | 167.0 ± 2.1 | 164.1 | 170.5 | 53.46 ± 5.17 |
| pting | input-pting | 175.4 ± 2.5 | 170.5 | 179.6 | 56.13 ± 5.44 |
| pting | input-lanjian | 191.7 ± 4.1 | 185.3 | 200.5 | 61.34 ± 6.03 |
| mattcl-py | input-kcen | 193.4 ± 1.9 | 189.9 | 197.2 | 61.88 ± 5.97 |
| mattcl-py | input-mattcl | 202.6 ± 2.6 | 199.1 | 209.3 | 64.82 ± 6.27 |
| pting | input-kcen | 222.1 ± 3.9 | 214.1 | 227.2 | 71.08 ± 6.94 |
| pting | input-mattcl | 241.5 ± 7.4 | 232.5 | 259.3 | 77.27 ± 7.78 |
| kcen | input-pting | 568.3 ± 6.8 | 557.8 | 574.4 | 181.86 ± 17.58 |
| kcen | input-lanjian | 624.2 ± 23.9 | 607.9 | 659.7 | 199.77 ± 20.64 |
| kcen | input-kcen | 733.7 ± 11.6 | 717.9 | 744.3 | 234.82 ± 22.83 |
| kcen | input-mattcl | 814.0 ± 4.0 | 809.9 | 818.0 | 260.49 ± 25.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|