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
| mattcl | input-pting | 3.2 ± 0.4 | 2.3 | 5.6 | 1.00 |
| mattcl | input-lanjian | 3.2 ± 0.4 | 2.2 | 5.6 | 1.01 ± 0.17 |
| mattcl | input-kcen | 3.5 ± 0.4 | 2.7 | 5.7 | 1.10 ± 0.18 |
| mattcl | input-mattcl | 4.0 ± 0.5 | 3.2 | 7.4 | 1.26 ± 0.23 |
| lanjian | input-pting | 18.5 ± 0.8 | 17.5 | 22.3 | 5.85 ± 0.80 |
| lanjian | input-lanjian | 19.4 ± 3.4 | 18.0 | 60.1 | 6.13 ± 1.32 |
| lanjian | input-kcen | 21.7 ± 0.8 | 20.7 | 24.8 | 6.87 ± 0.92 |
| lanjian | input-mattcl | 23.8 ± 0.9 | 22.4 | 26.8 | 7.53 ± 1.01 |
| mattcl-py | input-pting | 155.8 ± 1.4 | 152.7 | 158.3 | 49.24 ± 6.32 |
| mattcl-py | input-lanjian | 167.7 ± 1.5 | 164.9 | 171.4 | 53.01 ± 6.81 |
| pting | input-pting | 176.7 ± 2.6 | 172.9 | 183.3 | 55.84 ± 7.20 |
| pting | input-lanjian | 191.7 ± 4.3 | 182.1 | 197.3 | 60.58 ± 7.88 |
| mattcl-py | input-kcen | 194.2 ± 2.4 | 190.6 | 199.5 | 61.37 ± 7.90 |
| mattcl-py | input-mattcl | 204.4 ± 2.6 | 199.9 | 208.9 | 64.60 ± 8.32 |
| pting | input-kcen | 223.5 ± 5.2 | 215.2 | 229.5 | 70.62 ± 9.20 |
| pting | input-mattcl | 243.4 ± 13.0 | 234.2 | 279.0 | 76.93 ± 10.68 |
| kcen | input-pting | 580.6 ± 11.1 | 566.0 | 597.0 | 183.49 ± 23.77 |
| kcen | input-lanjian | 622.2 ± 5.2 | 615.1 | 627.5 | 196.66 ± 25.24 |
| kcen | input-kcen | 729.5 ± 9.6 | 718.8 | 741.9 | 230.55 ± 29.69 |
| kcen | input-mattcl | 798.3 ± 4.7 | 792.9 | 801.5 | 252.30 ± 32.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|