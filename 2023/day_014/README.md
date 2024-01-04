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
| mattcl | input-lanjian | 3.2 ± 0.2 | 2.4 | 5.6 | 1.00 |
| mattcl | input-pting | 3.2 ± 0.4 | 2.4 | 6.0 | 1.01 ± 0.15 |
| mattcl | input-kcen | 3.5 ± 0.4 | 2.7 | 5.5 | 1.10 ± 0.14 |
| mattcl | input-mattcl | 3.9 ± 0.5 | 3.1 | 6.6 | 1.24 ± 0.17 |
| lanjian | input-pting | 18.2 ± 0.9 | 17.3 | 21.6 | 5.74 ± 0.53 |
| lanjian | input-lanjian | 19.1 ± 0.9 | 18.1 | 22.4 | 6.01 ± 0.54 |
| lanjian | input-kcen | 21.6 ± 0.9 | 20.5 | 24.8 | 6.79 ± 0.59 |
| lanjian | input-mattcl | 23.6 ± 0.9 | 22.5 | 26.8 | 7.44 ± 0.64 |
| mattcl-py | input-pting | 154.4 ± 2.2 | 151.3 | 158.7 | 48.62 ± 3.81 |
| mattcl-py | input-lanjian | 170.3 ± 5.1 | 165.5 | 183.8 | 53.65 ± 4.43 |
| pting | input-pting | 174.2 ± 2.5 | 170.6 | 180.3 | 54.86 ± 4.30 |
| pting | input-lanjian | 191.7 ± 3.4 | 186.5 | 197.5 | 60.36 ± 4.78 |
| mattcl-py | input-kcen | 194.8 ± 2.1 | 191.9 | 198.8 | 61.36 ± 4.78 |
| mattcl-py | input-mattcl | 203.5 ± 2.4 | 200.5 | 208.6 | 64.11 ± 5.00 |
| pting | input-kcen | 219.9 ± 3.2 | 215.2 | 225.7 | 69.27 ± 5.44 |
| pting | input-mattcl | 237.1 ± 3.9 | 230.7 | 244.4 | 74.69 ± 5.89 |
| kcen | input-pting | 566.4 ± 4.2 | 559.0 | 569.8 | 178.38 ± 13.82 |
| kcen | input-lanjian | 616.2 ± 5.9 | 608.7 | 622.9 | 194.07 ± 15.08 |
| kcen | input-kcen | 721.5 ± 7.1 | 714.2 | 730.0 | 227.23 ± 17.66 |
| kcen | input-mattcl | 801.6 ± 2.2 | 799.1 | 803.3 | 252.48 ± 19.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|