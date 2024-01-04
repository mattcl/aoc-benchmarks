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
| mattcl | input-pting | 3.1 ± 0.3 | 2.4 | 6.1 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.3 | 2.3 | 5.8 | 1.00 ± 0.15 |
| mattcl | input-kcen | 3.4 ± 0.4 | 2.6 | 5.5 | 1.10 ± 0.17 |
| mattcl | input-mattcl | 3.9 ± 0.5 | 3.1 | 7.0 | 1.26 ± 0.20 |
| lanjian | input-pting | 18.1 ± 1.0 | 17.1 | 21.7 | 5.85 ± 0.69 |
| lanjian | input-lanjian | 18.9 ± 0.7 | 18.1 | 22.2 | 6.12 ± 0.67 |
| lanjian | input-kcen | 21.5 ± 0.8 | 20.5 | 24.6 | 6.94 ± 0.77 |
| lanjian | input-mattcl | 23.5 ± 0.8 | 22.5 | 26.4 | 7.58 ± 0.83 |
| mattcl-py | input-pting | 155.4 ± 1.7 | 153.3 | 158.4 | 50.19 ± 5.24 |
| mattcl-py | input-lanjian | 168.8 ± 1.9 | 166.0 | 173.2 | 54.51 ± 5.69 |
| pting | input-pting | 176.2 ± 2.5 | 172.6 | 180.2 | 56.91 ± 5.96 |
| pting | input-lanjian | 191.9 ± 3.3 | 186.2 | 197.2 | 61.99 ± 6.52 |
| mattcl-py | input-kcen | 197.3 ± 4.7 | 193.5 | 212.4 | 63.71 ± 6.79 |
| mattcl-py | input-mattcl | 205.1 ± 2.0 | 201.4 | 208.7 | 66.22 ± 6.90 |
| pting | input-kcen | 229.9 ± 22.6 | 219.4 | 304.4 | 74.25 ± 10.62 |
| pting | input-mattcl | 238.1 ± 4.6 | 230.7 | 245.4 | 76.91 ± 8.12 |
| kcen | input-pting | 566.4 ± 8.9 | 559.1 | 581.2 | 182.92 ± 19.21 |
| kcen | input-lanjian | 621.8 ± 3.6 | 619.1 | 626.7 | 200.82 ± 20.88 |
| kcen | input-kcen | 731.8 ± 3.2 | 728.5 | 734.7 | 236.33 ± 24.56 |
| kcen | input-mattcl | 793.8 ± 9.1 | 785.9 | 803.8 | 256.38 ± 26.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|