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
| mattcl | input-pting | 3.1 ± 0.3 | 2.2 | 5.7 | 1.00 |
| mattcl | input-lanjian | 3.2 ± 0.4 | 2.5 | 4.8 | 1.05 ± 0.17 |
| mattcl | input-kcen | 3.5 ± 0.4 | 2.7 | 5.7 | 1.14 ± 0.18 |
| mattcl | input-mattcl | 4.0 ± 0.4 | 3.2 | 6.3 | 1.31 ± 0.19 |
| lanjian | input-pting | 18.9 ± 0.7 | 17.9 | 21.6 | 6.18 ± 0.72 |
| lanjian | input-lanjian | 19.7 ± 0.6 | 18.8 | 22.5 | 6.44 ± 0.74 |
| lanjian | input-kcen | 22.5 ± 1.0 | 21.3 | 25.9 | 7.34 ± 0.87 |
| lanjian | input-mattcl | 24.6 ± 0.8 | 23.5 | 27.7 | 8.04 ± 0.93 |
| mattcl-py | input-pting | 154.9 ± 1.7 | 151.9 | 158.0 | 50.59 ± 5.62 |
| mattcl-py | input-lanjian | 168.7 ± 1.7 | 165.9 | 173.1 | 55.10 ± 6.12 |
| pting | input-pting | 176.7 ± 2.7 | 170.5 | 183.4 | 57.72 ± 6.44 |
| pting | input-lanjian | 192.0 ± 3.2 | 186.8 | 197.4 | 62.71 ± 7.01 |
| mattcl-py | input-kcen | 196.8 ± 3.1 | 192.8 | 205.4 | 64.27 ± 7.18 |
| mattcl-py | input-mattcl | 205.2 ± 3.5 | 202.7 | 216.5 | 67.02 ± 7.50 |
| pting | input-kcen | 224.5 ± 3.1 | 219.2 | 229.5 | 73.33 ± 8.17 |
| pting | input-mattcl | 240.4 ± 5.6 | 232.5 | 251.3 | 78.54 ± 8.88 |
| kcen | input-pting | 575.8 ± 5.5 | 569.8 | 582.3 | 188.08 ± 20.87 |
| kcen | input-lanjian | 624.0 ± 5.4 | 618.5 | 630.4 | 203.83 ± 22.60 |
| kcen | input-kcen | 744.0 ± 3.8 | 738.3 | 746.8 | 243.03 ± 26.90 |
| kcen | input-mattcl | 810.4 ± 11.4 | 798.1 | 820.6 | 264.73 ± 29.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|