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
| mattcl | input-lanjian | 3.1 ± 0.3 | 2.4 | 4.9 | 1.00 |
| mattcl | input-pting | 3.1 ± 0.3 | 2.3 | 5.6 | 1.00 ± 0.12 |
| mattcl | input-kcen | 3.5 ± 0.3 | 2.8 | 5.5 | 1.12 ± 0.14 |
| mattcl | input-mattcl | 4.3 ± 4.3 | 3.1 | 64.4 | 1.38 ± 1.38 |
| lanjian | input-pting | 18.5 ± 0.9 | 17.2 | 21.8 | 5.93 ± 0.56 |
| lanjian | input-lanjian | 19.3 ± 0.7 | 18.3 | 22.8 | 6.19 ± 0.55 |
| lanjian | input-kcen | 21.8 ± 0.9 | 20.7 | 25.6 | 6.99 ± 0.63 |
| lanjian | input-mattcl | 24.0 ± 2.6 | 22.4 | 51.3 | 7.70 ± 1.04 |
| mattcl-py | input-pting | 153.9 ± 2.1 | 150.9 | 158.3 | 49.35 ± 4.02 |
| mattcl-py | input-lanjian | 169.2 ± 2.4 | 165.3 | 173.9 | 54.25 ± 4.42 |
| pting | input-pting | 179.3 ± 2.9 | 174.3 | 186.6 | 57.48 ± 4.70 |
| mattcl-py | input-kcen | 196.0 ± 2.4 | 193.2 | 201.3 | 62.82 ± 5.10 |
| pting | input-lanjian | 197.2 ± 4.0 | 190.1 | 202.4 | 63.22 ± 5.23 |
| mattcl-py | input-mattcl | 204.0 ± 2.0 | 201.4 | 208.5 | 65.41 ± 5.29 |
| pting | input-kcen | 227.2 ± 7.9 | 220.0 | 250.5 | 72.83 ± 6.37 |
| pting | input-mattcl | 243.4 ± 4.4 | 236.6 | 251.0 | 78.02 ± 6.42 |
| kcen | input-pting | 569.3 ± 6.7 | 561.8 | 577.7 | 182.49 ± 14.80 |
| kcen | input-lanjian | 628.3 ± 6.4 | 623.2 | 637.5 | 201.42 ± 16.29 |
| kcen | input-kcen | 740.5 ± 13.3 | 723.7 | 752.5 | 237.38 ± 19.52 |
| kcen | input-mattcl | 793.8 ± 10.6 | 783.9 | 804.9 | 254.46 ± 20.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|