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
| mattcl | input-pting | 3.0 ± 0.2 | 2.1 | 4.9 | 1.00 |
| mattcl | input-lanjian | 3.0 ± 0.3 | 2.2 | 5.5 | 1.01 ± 0.12 |
| mattcl | input-kcen | 3.4 ± 0.4 | 2.6 | 5.9 | 1.13 ± 0.15 |
| mattcl | input-mattcl | 3.9 ± 0.5 | 3.1 | 7.5 | 1.29 ± 0.20 |
| lanjian | input-pting | 18.1 ± 0.9 | 17.0 | 21.7 | 6.00 ± 0.57 |
| lanjian | input-lanjian | 18.9 ± 0.7 | 18.1 | 22.2 | 6.27 ± 0.56 |
| lanjian | input-kcen | 21.4 ± 0.8 | 20.4 | 24.5 | 7.08 ± 0.63 |
| lanjian | input-mattcl | 23.6 ± 0.8 | 22.6 | 26.7 | 7.80 ± 0.69 |
| mattcl-py | input-pting | 154.1 ± 1.9 | 151.9 | 158.2 | 51.00 ± 4.17 |
| mattcl-py | input-lanjian | 168.5 ± 1.5 | 165.8 | 170.7 | 55.79 ± 4.54 |
| pting | input-pting | 177.4 ± 2.8 | 172.1 | 181.5 | 58.72 ± 4.84 |
| pting | input-lanjian | 193.5 ± 6.5 | 188.8 | 214.8 | 64.06 ± 5.61 |
| mattcl-py | input-kcen | 197.3 ± 2.3 | 191.5 | 200.7 | 65.31 ± 5.33 |
| mattcl-py | input-mattcl | 204.7 ± 2.6 | 201.0 | 210.5 | 67.77 ± 5.55 |
| pting | input-kcen | 225.8 ± 4.0 | 220.8 | 232.5 | 74.76 ± 6.19 |
| pting | input-mattcl | 238.0 ± 2.4 | 234.7 | 240.7 | 78.80 ± 6.42 |
| kcen | input-pting | 570.0 ± 3.2 | 566.0 | 573.0 | 188.70 ± 15.29 |
| kcen | input-lanjian | 627.6 ± 6.8 | 622.0 | 637.4 | 207.77 ± 16.95 |
| kcen | input-kcen | 735.3 ± 6.4 | 728.9 | 744.0 | 243.45 ± 19.80 |
| kcen | input-mattcl | 801.5 ± 8.5 | 792.0 | 808.1 | 265.36 ± 21.63 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|