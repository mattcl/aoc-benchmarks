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
| mattcl | input-pting | 3.1 ± 0.3 | 2.3 | 5.7 | 1.00 |
| mattcl | input-lanjian | 3.2 ± 0.3 | 2.4 | 5.0 | 1.01 ± 0.13 |
| mattcl | input-kcen | 3.6 ± 0.3 | 2.8 | 5.2 | 1.13 ± 0.14 |
| mattcl | input-mattcl | 4.1 ± 0.4 | 3.3 | 6.4 | 1.31 ± 0.19 |
| lanjian | input-pting | 19.1 ± 0.6 | 18.3 | 22.1 | 6.06 ± 0.63 |
| lanjian | input-lanjian | 20.1 ± 0.7 | 19.2 | 23.3 | 6.37 ± 0.66 |
| lanjian | input-kcen | 22.6 ± 0.9 | 21.4 | 25.7 | 7.18 ± 0.76 |
| lanjian | input-mattcl | 24.9 ± 1.0 | 23.3 | 28.5 | 7.90 ± 0.83 |
| mattcl-py | input-pting | 154.8 ± 1.8 | 151.4 | 157.5 | 49.13 ± 4.85 |
| mattcl-py | input-lanjian | 172.2 ± 16.2 | 165.2 | 234.2 | 54.68 ± 7.44 |
| pting | input-pting | 175.9 ± 3.4 | 171.2 | 181.5 | 55.84 ± 5.58 |
| mattcl-py | input-kcen | 195.1 ± 1.8 | 192.0 | 198.7 | 61.96 ± 6.10 |
| pting | input-lanjian | 195.9 ± 7.6 | 187.6 | 220.2 | 62.21 ± 6.56 |
| mattcl-py | input-mattcl | 204.4 ± 2.5 | 200.3 | 208.1 | 64.89 ± 6.42 |
| pting | input-kcen | 231.7 ± 23.7 | 221.0 | 309.3 | 73.56 ± 10.42 |
| pting | input-mattcl | 238.2 ± 3.6 | 232.6 | 246.5 | 75.62 ± 7.51 |
| kcen | input-pting | 606.6 ± 6.4 | 599.9 | 613.1 | 192.58 ± 19.00 |
| kcen | input-lanjian | 664.6 ± 6.7 | 656.8 | 672.9 | 210.99 ± 20.81 |
| kcen | input-kcen | 777.2 ± 13.2 | 762.7 | 788.5 | 246.74 ± 24.57 |
| kcen | input-mattcl | 858.4 ± 13.0 | 843.5 | 866.9 | 272.52 ± 27.05 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|