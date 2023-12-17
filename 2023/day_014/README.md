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
| mattcl | input-pting | 3.1 ± 0.3 | 2.3 | 5.3 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.2 | 2.4 | 4.5 | 1.01 ± 0.11 |
| mattcl | input-kcen | 3.4 ± 0.5 | 2.6 | 6.5 | 1.09 ± 0.18 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.1 | 5.8 | 1.27 ± 0.17 |
| lanjian | input-pting | 18.0 ± 0.7 | 17.0 | 21.4 | 5.80 ± 0.55 |
| lanjian | input-lanjian | 19.1 ± 0.8 | 18.2 | 22.7 | 6.13 ± 0.59 |
| lanjian | input-kcen | 21.6 ± 0.9 | 20.6 | 24.7 | 6.94 ± 0.67 |
| lanjian | input-mattcl | 23.6 ± 0.6 | 22.8 | 26.1 | 7.58 ± 0.70 |
| mattcl-py | input-pting | 154.8 ± 2.2 | 151.5 | 159.4 | 49.80 ± 4.44 |
| mattcl-py | input-lanjian | 168.4 ± 1.4 | 165.4 | 170.5 | 54.18 ± 4.79 |
| pting | input-pting | 177.5 ± 2.0 | 174.5 | 180.3 | 57.10 ± 5.07 |
| pting | input-lanjian | 195.5 ± 6.9 | 187.7 | 216.5 | 62.91 ± 5.97 |
| mattcl-py | input-kcen | 196.1 ± 3.1 | 191.9 | 203.1 | 63.10 ± 5.64 |
| mattcl-py | input-mattcl | 207.0 ± 11.7 | 200.2 | 246.8 | 66.61 ± 6.96 |
| pting | input-kcen | 227.2 ± 4.3 | 218.6 | 234.9 | 73.10 ± 6.58 |
| pting | input-mattcl | 241.3 ± 4.0 | 235.4 | 248.0 | 77.64 ± 6.96 |
| kcen | input-pting | 581.1 ± 33.8 | 563.4 | 641.3 | 186.96 ± 19.74 |
| kcen | input-lanjian | 630.6 ± 14.0 | 617.4 | 647.6 | 202.90 ± 18.43 |
| kcen | input-kcen | 731.1 ± 10.0 | 721.4 | 742.9 | 235.22 ± 20.96 |
| kcen | input-mattcl | 801.8 ± 5.2 | 796.5 | 807.0 | 257.99 ± 22.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|