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
| mattcl | input-pting | 3.1 ± 0.4 | 2.1 | 5.7 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.3 | 2.3 | 4.8 | 1.01 ± 0.16 |
| mattcl | input-kcen | 3.4 ± 0.3 | 2.7 | 4.9 | 1.12 ± 0.18 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.0 | 6.3 | 1.28 ± 0.20 |
| lanjian | input-pting | 18.6 ± 0.5 | 17.9 | 22.1 | 6.06 ± 0.78 |
| lanjian | input-lanjian | 19.7 ± 0.7 | 18.7 | 22.7 | 6.41 ± 0.84 |
| lanjian | input-kcen | 22.1 ± 0.8 | 20.9 | 25.8 | 7.18 ± 0.93 |
| lanjian | input-mattcl | 24.4 ± 0.7 | 23.2 | 27.4 | 7.92 ± 1.02 |
| mattcl-py | input-pting | 158.2 ± 14.1 | 151.9 | 215.7 | 51.42 ± 7.91 |
| mattcl-py | input-lanjian | 169.4 ± 2.5 | 165.6 | 175.9 | 55.08 ± 6.94 |
| pting | input-pting | 176.7 ± 2.7 | 171.7 | 180.4 | 57.44 ± 7.24 |
| pting | input-lanjian | 194.5 ± 7.8 | 188.0 | 218.1 | 63.23 ± 8.30 |
| mattcl-py | input-kcen | 196.2 ± 2.4 | 192.6 | 202.8 | 63.79 ± 8.02 |
| mattcl-py | input-mattcl | 204.9 ± 2.1 | 201.2 | 208.4 | 66.59 ± 8.36 |
| pting | input-kcen | 226.9 ± 12.0 | 216.3 | 259.1 | 73.77 ± 10.02 |
| pting | input-mattcl | 250.3 ± 28.5 | 234.2 | 330.6 | 81.38 ± 13.77 |
| kcen | input-pting | 572.5 ± 6.4 | 561.2 | 577.5 | 186.09 ± 23.37 |
| kcen | input-lanjian | 631.2 ± 15.9 | 616.0 | 653.7 | 205.21 ± 26.19 |
| kcen | input-kcen | 748.0 ± 26.5 | 727.2 | 786.4 | 243.16 ± 31.62 |
| kcen | input-mattcl | 808.1 ± 7.5 | 799.7 | 813.6 | 262.71 ± 32.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|