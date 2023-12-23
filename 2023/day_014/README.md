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
| mattcl | input-lanjian | 3.0 ± 0.2 | 2.2 | 3.8 | 1.00 |
| mattcl | input-pting | 3.1 ± 0.3 | 2.6 | 5.9 | 1.01 ± 0.13 |
| mattcl | input-kcen | 3.4 ± 0.3 | 2.7 | 5.5 | 1.13 ± 0.14 |
| mattcl | input-mattcl | 3.9 ± 0.5 | 3.0 | 7.0 | 1.30 ± 0.18 |
| lanjian | input-pting | 19.0 ± 0.8 | 18.1 | 22.2 | 6.26 ± 0.54 |
| lanjian | input-lanjian | 20.0 ± 0.8 | 19.0 | 23.2 | 6.58 ± 0.57 |
| lanjian | input-kcen | 22.4 ± 0.8 | 21.4 | 25.7 | 7.38 ± 0.63 |
| lanjian | input-mattcl | 24.9 ± 0.9 | 23.6 | 27.9 | 8.19 ± 0.69 |
| mattcl-py | input-pting | 157.3 ± 8.4 | 151.7 | 191.0 | 51.74 ± 4.84 |
| mattcl-py | input-lanjian | 168.5 ± 3.0 | 164.2 | 175.2 | 55.43 ± 4.37 |
| pting | input-pting | 178.1 ± 3.6 | 170.7 | 184.2 | 58.61 ± 4.65 |
| pting | input-lanjian | 191.4 ± 3.9 | 184.9 | 197.4 | 62.96 ± 5.00 |
| mattcl-py | input-kcen | 193.8 ± 2.7 | 189.9 | 198.8 | 63.77 ± 4.97 |
| mattcl-py | input-mattcl | 205.4 ± 2.9 | 202.2 | 212.8 | 67.58 ± 5.27 |
| pting | input-kcen | 224.9 ± 3.5 | 218.0 | 231.2 | 73.98 ± 5.79 |
| pting | input-mattcl | 238.4 ± 4.7 | 232.3 | 246.8 | 78.44 ± 6.22 |
| kcen | input-pting | 567.3 ± 9.6 | 558.2 | 582.0 | 186.64 ± 14.66 |
| kcen | input-lanjian | 623.7 ± 7.8 | 616.8 | 633.1 | 205.21 ± 15.95 |
| kcen | input-kcen | 733.1 ± 2.8 | 730.5 | 736.7 | 241.21 ± 18.53 |
| kcen | input-mattcl | 805.6 ± 0.8 | 804.8 | 806.5 | 265.05 ± 20.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|