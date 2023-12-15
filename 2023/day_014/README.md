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
| mattcl | input-pting | 5.0 ± 0.4 | 4.3 | 7.1 | 1.00 |
| mattcl | input-lanjian | 5.4 ± 0.5 | 4.4 | 8.8 | 1.08 ± 0.14 |
| mattcl | input-kcen | 5.8 ± 0.6 | 5.1 | 9.2 | 1.16 ± 0.16 |
| mattcl | input-mattcl | 6.2 ± 5.1 | 5.1 | 78.0 | 1.24 ± 1.03 |
| lanjian | input-pting | 18.2 ± 0.8 | 17.3 | 21.4 | 3.64 ± 0.36 |
| lanjian | input-lanjian | 19.0 ± 0.7 | 18.0 | 22.2 | 3.80 ± 0.36 |
| lanjian | input-kcen | 21.4 ± 0.8 | 20.4 | 24.7 | 4.29 ± 0.41 |
| lanjian | input-mattcl | 24.0 ± 4.1 | 22.7 | 66.9 | 4.81 ± 0.93 |
| mattcl-py | input-pting | 157.0 ± 2.8 | 152.1 | 164.7 | 31.42 ± 2.82 |
| mattcl-py | input-lanjian | 169.7 ± 3.0 | 166.2 | 176.3 | 33.97 ± 3.05 |
| pting | input-pting | 177.2 ± 2.7 | 173.7 | 182.9 | 35.48 ± 3.16 |
| pting | input-lanjian | 194.8 ± 3.7 | 189.7 | 202.6 | 38.99 ± 3.50 |
| mattcl-py | input-kcen | 196.6 ± 2.4 | 193.1 | 201.8 | 39.37 ± 3.49 |
| mattcl-py | input-mattcl | 206.5 ± 2.8 | 202.4 | 212.4 | 41.34 ± 3.67 |
| pting | input-kcen | 225.4 ± 2.7 | 221.1 | 230.9 | 45.13 ± 4.00 |
| pting | input-mattcl | 242.0 ± 3.5 | 237.8 | 249.5 | 48.44 ± 4.31 |
| kcen | input-pting | 570.2 ± 9.4 | 555.1 | 579.5 | 114.14 ± 10.20 |
| kcen | input-lanjian | 628.0 ± 4.3 | 624.1 | 632.4 | 125.72 ± 11.08 |
| kcen | input-kcen | 743.2 ± 15.4 | 727.7 | 764.5 | 148.79 ± 13.43 |
| kcen | input-mattcl | 823.0 ± 37.3 | 790.8 | 863.9 | 164.76 ± 16.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|