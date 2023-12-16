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
| mattcl | input-pting | 3.0 ± 0.2 | 2.1 | 3.8 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.3 | 2.3 | 5.8 | 1.03 ± 0.14 |
| mattcl | input-kcen | 3.4 ± 0.4 | 2.6 | 5.6 | 1.14 ± 0.17 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.1 | 6.0 | 1.31 ± 0.17 |
| lanjian | input-pting | 18.3 ± 0.8 | 17.1 | 21.7 | 6.14 ± 0.54 |
| lanjian | input-lanjian | 19.3 ± 0.8 | 18.1 | 23.2 | 6.47 ± 0.56 |
| lanjian | input-kcen | 21.7 ± 0.8 | 20.5 | 24.9 | 7.25 ± 0.62 |
| lanjian | input-mattcl | 23.7 ± 0.7 | 22.8 | 26.6 | 7.92 ± 0.65 |
| mattcl-py | input-pting | 155.7 ± 3.1 | 152.7 | 162.1 | 52.14 ± 4.18 |
| mattcl-py | input-lanjian | 170.3 ± 3.1 | 166.3 | 178.6 | 57.01 ± 4.55 |
| pting | input-pting | 177.8 ± 5.2 | 170.1 | 192.4 | 59.52 ± 4.94 |
| pting | input-lanjian | 192.3 ± 2.3 | 187.6 | 195.9 | 64.40 ± 5.06 |
| mattcl-py | input-kcen | 194.6 ± 1.6 | 192.5 | 199.2 | 65.16 ± 5.09 |
| mattcl-py | input-mattcl | 204.6 ± 5.1 | 200.4 | 220.3 | 68.50 ± 5.58 |
| pting | input-kcen | 224.2 ± 4.2 | 219.9 | 232.9 | 75.08 ± 5.99 |
| pting | input-mattcl | 236.6 ± 4.2 | 229.7 | 243.8 | 79.23 ± 6.31 |
| kcen | input-pting | 590.6 ± 9.6 | 579.4 | 605.5 | 197.76 ± 15.68 |
| kcen | input-lanjian | 647.5 ± 7.0 | 640.0 | 656.4 | 216.81 ± 16.99 |
| kcen | input-kcen | 753.3 ± 8.8 | 743.3 | 760.0 | 252.25 ± 19.80 |
| kcen | input-mattcl | 838.0 ± 8.5 | 828.5 | 845.0 | 280.62 ± 21.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|