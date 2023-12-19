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
| mattcl | input-pting | 3.0 ± 0.3 | 2.2 | 5.1 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.4 | 2.2 | 6.0 | 1.03 ± 0.17 |
| mattcl | input-kcen | 3.4 ± 0.4 | 2.6 | 6.5 | 1.12 ± 0.17 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.0 | 6.3 | 1.28 ± 0.19 |
| lanjian | input-pting | 18.8 ± 0.9 | 17.8 | 22.0 | 6.23 ± 0.64 |
| lanjian | input-lanjian | 19.5 ± 0.7 | 18.5 | 22.6 | 6.45 ± 0.63 |
| lanjian | input-kcen | 22.2 ± 1.0 | 21.0 | 26.1 | 7.34 ± 0.73 |
| lanjian | input-mattcl | 24.3 ± 1.0 | 23.1 | 27.2 | 8.04 ± 0.80 |
| mattcl-py | input-pting | 156.9 ± 2.0 | 153.8 | 161.8 | 51.91 ± 4.73 |
| mattcl-py | input-lanjian | 171.6 ± 4.6 | 167.9 | 187.0 | 56.78 ± 5.34 |
| pting | input-pting | 177.3 ± 3.5 | 172.9 | 185.2 | 58.68 ± 5.41 |
| pting | input-lanjian | 194.9 ± 3.5 | 190.3 | 205.2 | 64.50 ± 5.93 |
| mattcl-py | input-kcen | 200.6 ± 6.2 | 195.2 | 218.6 | 66.37 ± 6.33 |
| mattcl-py | input-mattcl | 207.1 ± 3.5 | 203.5 | 217.4 | 68.54 ± 6.29 |
| pting | input-kcen | 227.9 ± 3.3 | 221.6 | 233.1 | 75.41 ± 6.88 |
| pting | input-mattcl | 242.2 ± 3.0 | 239.0 | 247.9 | 80.14 ± 7.29 |
| kcen | input-pting | 573.8 ± 3.6 | 570.6 | 579.1 | 189.88 ± 17.15 |
| kcen | input-lanjian | 628.0 ± 8.2 | 616.8 | 635.5 | 207.83 ± 18.92 |
| kcen | input-kcen | 756.7 ± 12.3 | 742.7 | 766.0 | 250.40 ± 22.93 |
| kcen | input-mattcl | 820.6 ± 15.4 | 808.6 | 837.9 | 271.55 ± 24.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|