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
| mattcl | input-lanjian | 3.0 ± 0.3 | 2.2 | 4.3 | 1.00 |
| mattcl | input-pting | 3.1 ± 0.4 | 2.2 | 5.8 | 1.01 ± 0.17 |
| mattcl | input-kcen | 3.4 ± 0.4 | 2.6 | 6.4 | 1.13 ± 0.18 |
| mattcl | input-mattcl | 4.0 ± 0.5 | 3.4 | 7.8 | 1.30 ± 0.21 |
| lanjian | input-pting | 19.1 ± 0.8 | 18.2 | 21.9 | 6.26 ± 0.67 |
| lanjian | input-lanjian | 20.0 ± 0.8 | 18.8 | 23.5 | 6.57 ± 0.70 |
| lanjian | input-kcen | 22.4 ± 0.9 | 21.4 | 26.0 | 7.37 ± 0.78 |
| lanjian | input-mattcl | 24.7 ± 1.0 | 23.1 | 28.2 | 8.11 ± 0.86 |
| mattcl-py | input-pting | 155.4 ± 1.1 | 152.0 | 157.1 | 51.05 ± 5.05 |
| mattcl-py | input-lanjian | 167.5 ± 1.8 | 163.9 | 171.3 | 55.02 ± 5.46 |
| pting | input-pting | 177.9 ± 2.5 | 173.2 | 182.8 | 58.43 ± 5.82 |
| pting | input-lanjian | 193.6 ± 5.4 | 183.9 | 201.9 | 63.58 ± 6.51 |
| mattcl-py | input-kcen | 195.6 ± 3.1 | 190.7 | 202.1 | 64.23 ± 6.42 |
| mattcl-py | input-mattcl | 204.0 ± 2.5 | 201.2 | 209.3 | 66.99 ± 6.66 |
| pting | input-kcen | 221.1 ± 2.5 | 216.4 | 224.8 | 72.62 ± 7.21 |
| pting | input-mattcl | 242.1 ± 4.0 | 236.7 | 247.4 | 79.52 ± 7.95 |
| kcen | input-pting | 572.0 ± 7.7 | 563.0 | 584.1 | 187.86 ± 18.70 |
| kcen | input-lanjian | 626.3 ± 4.5 | 622.1 | 632.5 | 205.68 ± 20.34 |
| kcen | input-kcen | 729.3 ± 7.5 | 718.7 | 735.9 | 239.50 ± 23.75 |
| kcen | input-mattcl | 805.5 ± 4.7 | 800.3 | 809.3 | 264.56 ± 26.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|