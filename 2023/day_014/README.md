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
| mattcl | input-pting | 3.1 ± 0.3 | 2.3 | 5.6 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.3 | 2.4 | 4.7 | 1.01 ± 0.14 |
| mattcl | input-kcen | 3.5 ± 0.5 | 2.7 | 6.6 | 1.13 ± 0.19 |
| mattcl | input-mattcl | 4.0 ± 0.5 | 3.1 | 7.1 | 1.27 ± 0.20 |
| lanjian | input-pting | 18.6 ± 0.9 | 17.3 | 22.2 | 5.97 ± 0.64 |
| lanjian | input-lanjian | 19.3 ± 0.9 | 18.3 | 22.7 | 6.22 ± 0.66 |
| lanjian | input-kcen | 21.8 ± 1.0 | 20.7 | 25.5 | 7.01 ± 0.74 |
| lanjian | input-mattcl | 23.9 ± 0.9 | 22.7 | 27.0 | 7.68 ± 0.79 |
| mattcl-py | input-pting | 156.6 ± 2.4 | 153.4 | 165.1 | 50.36 ± 4.86 |
| mattcl-py | input-lanjian | 168.5 ± 1.8 | 165.2 | 171.8 | 54.19 ± 5.20 |
| pting | input-pting | 176.9 ± 2.8 | 172.9 | 182.3 | 56.87 ± 5.49 |
| pting | input-lanjian | 192.2 ± 3.3 | 187.7 | 199.9 | 61.81 ± 5.99 |
| mattcl-py | input-kcen | 194.4 ± 2.2 | 189.9 | 199.3 | 62.51 ± 6.00 |
| mattcl-py | input-mattcl | 204.6 ± 2.3 | 200.9 | 208.4 | 65.80 ± 6.32 |
| pting | input-kcen | 221.2 ± 2.8 | 216.6 | 227.6 | 71.14 ± 6.84 |
| pting | input-mattcl | 238.4 ± 4.8 | 232.9 | 245.8 | 76.68 ± 7.47 |
| kcen | input-pting | 586.6 ± 3.3 | 582.5 | 590.9 | 188.65 ± 18.01 |
| kcen | input-lanjian | 643.2 ± 9.9 | 633.8 | 655.9 | 206.85 ± 19.97 |
| kcen | input-kcen | 786.4 ± 37.9 | 758.0 | 829.4 | 252.91 ± 27.00 |
| kcen | input-mattcl | 820.8 ± 7.0 | 813.1 | 826.9 | 263.95 ± 25.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|