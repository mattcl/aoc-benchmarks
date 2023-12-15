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
| mattcl | input-pting | 4.8 ± 0.6 | 4.1 | 8.1 | 1.00 |
| mattcl | input-lanjian | 5.1 ± 0.5 | 4.2 | 8.8 | 1.07 ± 0.18 |
| mattcl | input-kcen | 5.5 ± 0.5 | 4.7 | 8.2 | 1.15 ± 0.18 |
| mattcl | input-mattcl | 5.6 ± 0.3 | 4.9 | 8.9 | 1.16 ± 0.17 |
| lanjian | input-pting | 18.2 ± 0.8 | 17.3 | 21.3 | 3.79 ± 0.51 |
| lanjian | input-lanjian | 19.4 ± 3.2 | 18.1 | 44.9 | 4.03 ± 0.84 |
| lanjian | input-kcen | 21.8 ± 3.2 | 20.5 | 46.4 | 4.55 ± 0.89 |
| lanjian | input-mattcl | 23.5 ± 0.8 | 22.4 | 26.8 | 4.90 ± 0.65 |
| mattcl-py | input-pting | 154.9 ± 3.6 | 151.4 | 168.1 | 32.25 ± 4.21 |
| mattcl-py | input-lanjian | 167.2 ± 1.6 | 164.3 | 170.5 | 34.81 ± 4.48 |
| pting | input-pting | 177.8 ± 5.9 | 172.5 | 199.0 | 37.01 ± 4.91 |
| pting | input-lanjian | 194.4 ± 3.0 | 190.3 | 200.4 | 40.47 ± 5.23 |
| mattcl-py | input-kcen | 196.3 ± 2.9 | 191.9 | 201.9 | 40.87 ± 5.28 |
| mattcl-py | input-mattcl | 204.5 ± 3.4 | 200.9 | 213.7 | 42.56 ± 5.51 |
| pting | input-kcen | 226.1 ± 2.9 | 220.7 | 229.8 | 47.06 ± 6.07 |
| pting | input-mattcl | 238.4 ± 3.4 | 234.4 | 243.3 | 49.63 ± 6.41 |
| kcen | input-pting | 569.2 ± 6.8 | 560.8 | 579.3 | 118.50 ± 15.28 |
| kcen | input-lanjian | 618.9 ± 4.3 | 613.2 | 623.3 | 128.84 ± 16.57 |
| kcen | input-kcen | 731.8 ± 6.5 | 723.5 | 738.5 | 152.33 ± 19.60 |
| kcen | input-mattcl | 801.2 ± 17.6 | 781.3 | 815.0 | 166.79 ± 21.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|