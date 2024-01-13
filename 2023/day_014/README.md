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
| mattcl | input-pting | 3.1 ± 0.3 | 2.2 | 4.9 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.3 | 2.3 | 5.8 | 1.01 ± 0.14 |
| mattcl | input-kcen | 3.4 ± 0.4 | 2.8 | 6.0 | 1.11 ± 0.17 |
| mattcl | input-mattcl | 4.0 ± 0.5 | 3.2 | 6.4 | 1.30 ± 0.19 |
| lanjian | input-pting | 18.6 ± 0.8 | 17.5 | 21.7 | 5.99 ± 0.60 |
| lanjian | input-lanjian | 19.8 ± 2.7 | 18.4 | 51.1 | 6.36 ± 1.04 |
| lanjian | input-kcen | 22.2 ± 1.0 | 20.9 | 25.7 | 7.12 ± 0.72 |
| lanjian | input-mattcl | 24.1 ± 0.9 | 23.2 | 27.0 | 7.76 ± 0.74 |
| mattcl-py | input-pting | 157.4 ± 5.6 | 154.1 | 180.2 | 50.62 ± 4.86 |
| mattcl-py | input-lanjian | 172.5 ± 6.6 | 166.3 | 193.8 | 55.48 ± 5.37 |
| pting | input-pting | 176.1 ± 2.3 | 172.9 | 179.4 | 56.63 ± 5.10 |
| pting | input-lanjian | 193.3 ± 3.9 | 189.5 | 200.7 | 62.15 ± 5.68 |
| mattcl-py | input-kcen | 197.9 ± 2.4 | 194.4 | 203.2 | 63.64 ± 5.72 |
| mattcl-py | input-mattcl | 205.3 ± 2.4 | 202.2 | 211.5 | 66.01 ± 5.93 |
| pting | input-kcen | 224.4 ± 3.7 | 218.9 | 232.2 | 72.17 ± 6.54 |
| pting | input-mattcl | 239.7 ± 10.4 | 230.2 | 270.9 | 77.08 ± 7.64 |
| kcen | input-pting | 599.8 ± 9.7 | 587.6 | 610.4 | 192.89 ± 17.47 |
| kcen | input-lanjian | 664.3 ± 9.9 | 654.5 | 673.4 | 213.64 ± 19.30 |
| kcen | input-kcen | 776.9 ± 6.2 | 771.4 | 783.5 | 249.82 ± 22.34 |
| kcen | input-mattcl | 855.7 ± 13.2 | 845.2 | 870.5 | 275.17 ± 24.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|