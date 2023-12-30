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
| mattcl | input-pting | 3.1 ± 0.3 | 2.2 | 4.7 | 1.00 |
| mattcl | input-lanjian | 3.2 ± 0.3 | 2.3 | 4.6 | 1.01 ± 0.13 |
| mattcl | input-kcen | 3.5 ± 0.4 | 2.8 | 5.1 | 1.13 ± 0.16 |
| mattcl | input-mattcl | 4.1 ± 0.5 | 3.3 | 6.0 | 1.32 ± 0.18 |
| lanjian | input-pting | 18.9 ± 0.8 | 17.9 | 22.3 | 6.06 ± 0.58 |
| lanjian | input-lanjian | 19.9 ± 1.3 | 18.7 | 33.3 | 6.38 ± 0.70 |
| lanjian | input-kcen | 22.3 ± 0.8 | 21.2 | 25.8 | 7.14 ± 0.67 |
| lanjian | input-mattcl | 24.7 ± 0.9 | 23.2 | 27.8 | 7.91 ± 0.74 |
| mattcl-py | input-pting | 154.7 ± 1.3 | 152.5 | 157.8 | 49.66 ± 4.28 |
| mattcl-py | input-lanjian | 169.0 ± 2.6 | 164.1 | 173.5 | 54.25 ± 4.74 |
| pting | input-pting | 177.6 ± 3.4 | 171.6 | 183.0 | 57.00 ± 5.01 |
| mattcl-py | input-kcen | 194.3 ± 1.7 | 191.1 | 198.8 | 62.38 ± 5.38 |
| pting | input-lanjian | 196.8 ± 18.9 | 187.0 | 264.2 | 63.16 ± 8.14 |
| mattcl-py | input-mattcl | 202.7 ± 2.1 | 198.9 | 207.2 | 65.06 ± 5.63 |
| pting | input-kcen | 222.9 ± 3.6 | 217.0 | 227.8 | 71.53 ± 6.25 |
| pting | input-mattcl | 238.0 ± 2.5 | 234.1 | 243.6 | 76.40 ± 6.61 |
| kcen | input-pting | 595.1 ± 8.1 | 582.0 | 604.3 | 191.00 ± 16.61 |
| kcen | input-lanjian | 655.2 ± 7.7 | 646.4 | 665.1 | 210.30 ± 18.22 |
| kcen | input-kcen | 775.2 ± 1.3 | 774.1 | 776.6 | 248.81 ± 21.37 |
| kcen | input-mattcl | 852.7 ± 6.9 | 847.7 | 860.5 | 273.69 ± 23.60 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|