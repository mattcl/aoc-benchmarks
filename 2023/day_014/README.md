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
| mattcl | input-lanjian | 3.0 ± 0.3 | 2.2 | 4.7 | 1.00 |
| mattcl | input-pting | 3.0 ± 0.3 | 2.3 | 5.6 | 1.01 ± 0.14 |
| mattcl | input-kcen | 3.4 ± 0.4 | 2.6 | 5.6 | 1.13 ± 0.17 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.1 | 6.8 | 1.30 ± 0.18 |
| lanjian | input-pting | 18.4 ± 0.8 | 17.1 | 21.6 | 6.09 ± 0.58 |
| lanjian | input-lanjian | 19.2 ± 0.7 | 18.1 | 22.6 | 6.37 ± 0.58 |
| lanjian | input-kcen | 21.9 ± 2.3 | 20.8 | 45.5 | 7.28 ± 0.98 |
| lanjian | input-mattcl | 23.8 ± 0.8 | 22.7 | 26.4 | 7.89 ± 0.72 |
| mattcl-py | input-pting | 156.9 ± 1.7 | 154.3 | 161.1 | 52.08 ± 4.45 |
| mattcl-py | input-lanjian | 170.8 ± 2.7 | 167.0 | 176.5 | 56.69 ± 4.89 |
| pting | input-pting | 177.8 ± 2.7 | 172.6 | 181.8 | 59.01 ± 5.08 |
| pting | input-lanjian | 193.8 ± 3.3 | 188.9 | 200.7 | 64.35 ± 5.56 |
| mattcl-py | input-kcen | 198.0 ± 3.0 | 195.0 | 203.8 | 65.72 ± 5.66 |
| mattcl-py | input-mattcl | 206.1 ± 4.0 | 201.4 | 216.7 | 68.41 ± 5.95 |
| pting | input-kcen | 233.3 ± 23.2 | 219.4 | 307.7 | 77.44 ± 10.13 |
| pting | input-mattcl | 243.4 ± 13.5 | 234.6 | 285.3 | 80.78 ± 8.18 |
| kcen | input-pting | 581.3 ± 3.9 | 575.8 | 584.9 | 192.97 ± 16.41 |
| kcen | input-lanjian | 634.5 ± 18.4 | 617.1 | 659.5 | 210.62 ± 18.86 |
| kcen | input-kcen | 756.7 ± 17.5 | 736.6 | 767.8 | 251.18 ± 22.06 |
| kcen | input-mattcl | 813.3 ± 1.8 | 812.1 | 815.3 | 269.95 ± 22.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|