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
| mattcl | input-pting | 3.1 ± 0.2 | 2.2 | 3.7 | 1.00 |
| mattcl | input-lanjian | 3.2 ± 0.4 | 2.4 | 5.7 | 1.03 ± 0.15 |
| mattcl | input-kcen | 3.5 ± 0.3 | 2.7 | 5.5 | 1.13 ± 0.13 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.2 | 6.6 | 1.28 ± 0.16 |
| lanjian | input-pting | 18.2 ± 0.9 | 17.3 | 22.2 | 5.91 ± 0.46 |
| lanjian | input-lanjian | 19.3 ± 2.6 | 18.1 | 45.3 | 6.25 ± 0.93 |
| lanjian | input-kcen | 21.8 ± 3.2 | 20.5 | 58.3 | 7.07 ± 1.12 |
| lanjian | input-mattcl | 23.6 ± 0.9 | 22.4 | 27.0 | 7.64 ± 0.53 |
| mattcl-py | input-pting | 156.8 ± 3.2 | 153.5 | 164.8 | 50.86 ± 3.18 |
| mattcl-py | input-lanjian | 169.3 ± 2.1 | 165.0 | 173.2 | 54.91 ± 3.32 |
| pting | input-pting | 176.6 ± 3.2 | 170.7 | 183.1 | 57.29 ± 3.54 |
| pting | input-lanjian | 192.2 ± 2.1 | 188.3 | 197.0 | 62.35 ± 3.75 |
| mattcl-py | input-kcen | 196.6 ± 2.4 | 192.4 | 200.3 | 63.77 ± 3.85 |
| mattcl-py | input-mattcl | 203.6 ± 1.6 | 201.2 | 207.7 | 66.04 ± 3.94 |
| pting | input-kcen | 223.9 ± 3.8 | 216.6 | 229.4 | 72.60 ± 4.47 |
| pting | input-mattcl | 238.4 ± 4.0 | 231.2 | 245.1 | 77.31 ± 4.76 |
| kcen | input-pting | 562.0 ± 3.0 | 558.8 | 565.7 | 182.27 ± 10.83 |
| kcen | input-lanjian | 624.2 ± 4.4 | 619.9 | 629.6 | 202.45 ± 12.06 |
| kcen | input-kcen | 734.3 ± 8.6 | 726.4 | 746.6 | 238.16 ± 14.37 |
| kcen | input-mattcl | 794.2 ± 4.0 | 790.1 | 798.0 | 257.59 ± 15.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|