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
| mattcl | input-lanjian | 3.2 ± 0.2 | 2.3 | 3.9 | 1.00 |
| mattcl | input-pting | 3.2 ± 0.3 | 2.3 | 5.8 | 1.01 ± 0.12 |
| mattcl | input-kcen | 3.5 ± 0.3 | 2.7 | 5.7 | 1.12 ± 0.13 |
| mattcl | input-mattcl | 4.0 ± 0.5 | 3.1 | 7.9 | 1.27 ± 0.18 |
| lanjian | input-pting | 18.2 ± 0.7 | 17.4 | 21.5 | 5.75 ± 0.45 |
| lanjian | input-lanjian | 19.2 ± 0.9 | 18.3 | 22.5 | 6.08 ± 0.49 |
| lanjian | input-kcen | 21.4 ± 0.6 | 20.5 | 24.5 | 6.77 ± 0.49 |
| lanjian | input-mattcl | 23.5 ± 0.7 | 22.6 | 26.3 | 7.43 ± 0.54 |
| mattcl-py | input-pting | 155.2 ± 1.5 | 153.0 | 158.4 | 49.06 ± 3.33 |
| mattcl-py | input-lanjian | 168.0 ± 2.7 | 164.6 | 176.1 | 53.10 ± 3.66 |
| pting | input-pting | 177.1 ± 2.4 | 171.5 | 180.3 | 56.00 ± 3.83 |
| pting | input-lanjian | 194.7 ± 4.2 | 188.1 | 201.0 | 61.55 ± 4.34 |
| mattcl-py | input-kcen | 196.1 ± 3.6 | 191.9 | 204.8 | 61.99 ± 4.31 |
| mattcl-py | input-mattcl | 203.2 ± 2.1 | 199.4 | 206.8 | 64.24 ± 4.36 |
| pting | input-kcen | 225.0 ± 2.8 | 219.6 | 230.1 | 71.14 ± 4.85 |
| pting | input-mattcl | 248.1 ± 13.7 | 235.9 | 275.9 | 78.43 ± 6.82 |
| kcen | input-pting | 566.4 ± 8.9 | 558.9 | 581.6 | 179.05 ± 12.33 |
| kcen | input-lanjian | 621.3 ± 2.3 | 619.2 | 624.2 | 196.40 ± 13.19 |
| kcen | input-kcen | 742.0 ± 13.1 | 733.1 | 757.1 | 234.56 ± 16.27 |
| kcen | input-mattcl | 802.6 ± 9.5 | 793.0 | 812.0 | 253.73 ± 17.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|