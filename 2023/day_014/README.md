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
| mattcl | input-lanjian | 3.0 ± 0.3 | 2.3 | 5.9 | 1.00 |
| mattcl | input-pting | 3.2 ± 2.6 | 2.0 | 39.2 | 1.04 ± 0.86 |
| mattcl | input-kcen | 3.4 ± 0.4 | 2.7 | 5.0 | 1.12 ± 0.18 |
| mattcl | input-mattcl | 4.0 ± 0.5 | 3.0 | 7.5 | 1.31 ± 0.22 |
| lanjian | input-pting | 18.8 ± 1.4 | 17.5 | 34.6 | 6.20 ± 0.81 |
| lanjian | input-lanjian | 19.6 ± 0.8 | 18.6 | 22.7 | 6.46 ± 0.73 |
| lanjian | input-kcen | 22.3 ± 0.9 | 20.8 | 26.2 | 7.37 ± 0.83 |
| lanjian | input-mattcl | 24.3 ± 0.8 | 23.3 | 28.0 | 8.03 ± 0.89 |
| mattcl-py | input-pting | 154.7 ± 2.4 | 151.1 | 161.4 | 51.04 ± 5.45 |
| mattcl-py | input-lanjian | 168.6 ± 2.4 | 164.6 | 175.9 | 55.61 ± 5.93 |
| pting | input-pting | 176.3 ± 3.2 | 171.9 | 185.1 | 58.15 ± 6.23 |
| pting | input-lanjian | 191.1 ± 3.4 | 186.2 | 197.9 | 63.02 ± 6.75 |
| mattcl-py | input-kcen | 195.8 ± 3.2 | 191.9 | 203.6 | 64.60 ± 6.91 |
| mattcl-py | input-mattcl | 204.8 ± 3.0 | 200.0 | 210.4 | 67.56 ± 7.21 |
| pting | input-kcen | 221.1 ± 4.4 | 214.9 | 228.9 | 72.95 ± 7.84 |
| pting | input-mattcl | 237.7 ± 4.1 | 231.0 | 244.1 | 78.41 ± 8.39 |
| kcen | input-pting | 571.9 ± 6.6 | 562.4 | 577.0 | 188.64 ± 20.05 |
| kcen | input-lanjian | 626.0 ± 5.9 | 618.1 | 630.9 | 206.50 ± 21.90 |
| kcen | input-kcen | 744.8 ± 17.5 | 734.6 | 765.0 | 245.69 ± 26.59 |
| kcen | input-mattcl | 804.8 ± 13.5 | 789.2 | 813.2 | 265.48 ± 28.40 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|