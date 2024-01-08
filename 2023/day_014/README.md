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
| mattcl | input-pting | 3.0 ± 0.4 | 2.0 | 5.8 | 1.00 |
| mattcl | input-lanjian | 3.0 ± 0.3 | 2.1 | 4.8 | 1.01 ± 0.15 |
| mattcl | input-kcen | 3.4 ± 0.4 | 2.8 | 5.6 | 1.12 ± 0.20 |
| mattcl | input-mattcl | 3.8 ± 0.5 | 3.0 | 7.0 | 1.29 ± 0.23 |
| lanjian | input-pting | 18.0 ± 0.7 | 17.2 | 21.3 | 6.02 ± 0.79 |
| lanjian | input-lanjian | 18.9 ± 0.7 | 18.1 | 21.8 | 6.33 ± 0.83 |
| lanjian | input-kcen | 21.4 ± 0.7 | 20.5 | 24.5 | 7.16 ± 0.93 |
| lanjian | input-mattcl | 23.8 ± 3.5 | 22.5 | 62.5 | 7.97 ± 1.55 |
| mattcl-py | input-pting | 154.2 ± 1.4 | 151.9 | 156.3 | 51.65 ± 6.48 |
| mattcl-py | input-lanjian | 171.2 ± 6.5 | 166.3 | 192.2 | 57.35 ± 7.50 |
| pting | input-pting | 177.9 ± 8.0 | 170.8 | 198.9 | 59.60 ± 7.93 |
| pting | input-lanjian | 190.5 ± 2.6 | 186.0 | 194.0 | 63.82 ± 8.03 |
| mattcl-py | input-kcen | 197.5 ± 5.2 | 194.1 | 215.3 | 66.17 ± 8.46 |
| mattcl-py | input-mattcl | 204.1 ± 2.3 | 201.9 | 210.7 | 68.35 ± 8.59 |
| pting | input-kcen | 226.2 ± 7.5 | 219.1 | 247.2 | 75.76 ± 9.81 |
| pting | input-mattcl | 237.6 ± 2.7 | 234.0 | 241.8 | 79.57 ± 10.00 |
| kcen | input-pting | 574.5 ± 17.0 | 556.3 | 601.5 | 192.43 ± 24.75 |
| kcen | input-lanjian | 630.4 ± 7.8 | 621.6 | 640.1 | 211.17 ± 26.56 |
| kcen | input-kcen | 735.5 ± 4.0 | 731.1 | 740.3 | 246.38 ± 30.87 |
| kcen | input-mattcl | 807.4 ± 13.3 | 794.4 | 821.1 | 270.45 ± 34.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|