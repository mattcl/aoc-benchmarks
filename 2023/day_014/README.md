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
| mattcl | input-pting | 5.4 ± 0.4 | 4.4 | 7.2 | 1.00 |
| mattcl | input-lanjian | 5.4 ± 0.2 | 4.5 | 6.3 | 1.01 ± 0.09 |
| mattcl | input-kcen | 5.8 ± 0.4 | 5.0 | 9.3 | 1.08 ± 0.12 |
| mattcl | input-mattcl | 6.1 ± 0.5 | 5.2 | 9.8 | 1.13 ± 0.12 |
| lanjian | input-pting | 18.5 ± 0.9 | 17.5 | 21.8 | 3.43 ± 0.31 |
| lanjian | input-lanjian | 19.2 ± 0.7 | 18.4 | 22.8 | 3.56 ± 0.30 |
| lanjian | input-kcen | 21.5 ± 0.6 | 20.5 | 24.5 | 4.00 ± 0.32 |
| lanjian | input-mattcl | 23.8 ± 0.9 | 22.9 | 27.8 | 4.42 ± 0.37 |
| pting | input-pting | 213.7 ± 4.5 | 209.5 | 227.4 | 39.70 ± 3.09 |
| pting | input-lanjian | 233.1 ± 4.6 | 225.6 | 239.1 | 43.30 ± 3.36 |
| mattcl-py | input-pting | 254.8 ± 11.9 | 248.6 | 290.4 | 47.33 ± 4.18 |
| mattcl-py | input-lanjian | 263.3 ± 1.7 | 261.1 | 266.3 | 48.91 ± 3.68 |
| pting | input-kcen | 272.6 ± 7.7 | 263.1 | 293.8 | 50.64 ± 4.06 |
| pting | input-mattcl | 291.0 ± 4.0 | 284.7 | 297.7 | 54.06 ± 4.12 |
| mattcl-py | input-kcen | 318.6 ± 81.3 | 287.8 | 549.8 | 59.20 ± 15.74 |
| mattcl-py | input-mattcl | 337.6 ± 59.1 | 312.8 | 494.9 | 62.72 ± 11.94 |
| kcen | input-pting | 578.5 ± 7.6 | 572.8 | 591.5 | 107.48 ± 8.18 |
| kcen | input-lanjian | 625.5 ± 6.4 | 618.0 | 631.1 | 116.20 ± 8.79 |
| kcen | input-kcen | 734.1 ± 7.6 | 728.1 | 744.8 | 136.38 ± 10.32 |
| kcen | input-mattcl | 811.0 ± 1.5 | 809.8 | 812.6 | 150.66 ± 11.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|