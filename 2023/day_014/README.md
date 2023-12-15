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

| Participant | Input | Mean [s] | Min [s] | Max [s] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 0.005 ± 0.000 | 0.004 | 0.008 | 1.00 |
| mattcl | input-lanjian | 0.006 ± 0.000 | 0.005 | 0.006 | 1.08 ± 0.09 |
| mattcl | input-mattcl | 0.006 ± 0.000 | 0.005 | 0.009 | 1.21 ± 0.13 |
| mattcl | input-kcen | 0.006 ± 0.000 | 0.006 | 0.007 | 1.23 ± 0.10 |
| lanjian | input-pting | 0.019 ± 0.001 | 0.018 | 0.022 | 3.66 ± 0.29 |
| lanjian | input-lanjian | 0.025 ± 0.003 | 0.019 | 0.033 | 4.75 ± 0.70 |
| lanjian | input-mattcl | 0.025 ± 0.003 | 0.024 | 0.048 | 4.91 ± 0.61 |
| lanjian | input-kcen | 0.027 ± 0.001 | 0.025 | 0.028 | 5.16 ± 0.39 |
| mattcl-py | input-pting | 0.161 ± 0.004 | 0.156 | 0.170 | 31.15 ± 2.35 |
| pting | input-pting | 0.183 ± 0.004 | 0.179 | 0.196 | 35.52 ± 2.68 |
| mattcl-py | input-mattcl | 0.231 ± 0.044 | 0.206 | 0.366 | 44.85 ± 9.13 |
| mattcl-py | input-lanjian | 0.241 ± 0.003 | 0.237 | 0.248 | 46.78 ± 3.43 |
| pting | input-mattcl | 0.251 ± 0.006 | 0.240 | 0.259 | 48.76 ± 3.68 |
| pting | input-lanjian | 0.258 ± 0.047 | 0.197 | 0.344 | 50.03 ± 9.85 |
| pting | input-kcen | 0.261 ± 0.010 | 0.252 | 0.276 | 50.66 ± 4.11 |
| mattcl-py | input-kcen | 0.263 ± 0.045 | 0.219 | 0.355 | 51.07 ± 9.51 |
| kcen | input-pting | 0.636 ± 0.117 | 0.576 | 0.846 | 123.35 ± 24.45 |
| kcen | input-lanjian | 0.753 ± 0.038 | 0.723 | 0.807 | 146.09 ± 12.81 |
| kcen | input-mattcl | 0.829 ± 0.002 | 0.826 | 0.830 | 160.68 ± 11.59 |
| kcen | input-kcen | 1.025 ± 0.048 | 0.993 | 1.080 | 198.70 ± 17.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|