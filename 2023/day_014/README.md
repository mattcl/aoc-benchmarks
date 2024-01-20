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
| mattcl | input-pting | 3.1 ± 0.3 | 2.3 | 5.6 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.4 | 2.3 | 5.7 | 1.01 ± 0.16 |
| mattcl | input-kcen | 3.5 ± 0.3 | 2.8 | 5.5 | 1.14 ± 0.16 |
| mattcl | input-mattcl | 4.0 ± 0.4 | 3.1 | 6.3 | 1.30 ± 0.19 |
| lanjian | input-pting | 18.7 ± 1.0 | 17.3 | 21.8 | 6.05 ± 0.69 |
| lanjian | input-lanjian | 19.5 ± 0.7 | 18.4 | 21.8 | 6.29 ± 0.68 |
| lanjian | input-kcen | 22.1 ± 0.8 | 20.6 | 25.2 | 7.14 ± 0.77 |
| lanjian | input-mattcl | 23.8 ± 0.8 | 22.8 | 27.5 | 7.69 ± 0.82 |
| mattcl-py | input-pting | 155.1 ± 2.0 | 152.5 | 160.7 | 50.11 ± 5.14 |
| mattcl-py | input-lanjian | 168.9 ± 2.7 | 166.0 | 176.2 | 54.57 ± 5.62 |
| pting | input-pting | 176.0 ± 3.3 | 169.8 | 182.0 | 56.86 ± 5.89 |
| pting | input-lanjian | 193.1 ± 3.3 | 189.2 | 200.2 | 62.37 ± 6.44 |
| mattcl-py | input-kcen | 195.7 ± 1.9 | 191.8 | 200.1 | 63.23 ± 6.47 |
| mattcl-py | input-mattcl | 205.5 ± 2.0 | 202.5 | 210.1 | 66.39 ± 6.79 |
| pting | input-kcen | 226.3 ± 4.5 | 218.1 | 231.7 | 73.10 ± 7.58 |
| pting | input-mattcl | 238.1 ± 5.3 | 231.1 | 245.2 | 76.90 ± 8.01 |
| kcen | input-pting | 570.4 ± 0.9 | 568.9 | 571.1 | 184.24 ± 18.76 |
| kcen | input-lanjian | 628.0 ± 4.5 | 621.7 | 631.9 | 202.85 ± 20.70 |
| kcen | input-kcen | 748.8 ± 6.1 | 740.3 | 753.8 | 241.88 ± 24.70 |
| kcen | input-mattcl | 803.6 ± 3.5 | 799.9 | 806.8 | 259.57 ± 26.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|