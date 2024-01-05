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
| mattcl | input-lanjian | 3.0 ± 0.3 | 2.2 | 5.2 | 1.00 |
| mattcl | input-pting | 3.0 ± 0.3 | 2.2 | 5.6 | 1.00 ± 0.15 |
| mattcl | input-kcen | 3.3 ± 0.4 | 2.7 | 5.6 | 1.08 ± 0.17 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.1 | 5.7 | 1.29 ± 0.20 |
| lanjian | input-pting | 18.0 ± 0.9 | 17.2 | 21.9 | 5.93 ± 0.69 |
| lanjian | input-lanjian | 18.9 ± 0.7 | 18.1 | 22.1 | 6.23 ± 0.70 |
| lanjian | input-kcen | 21.4 ± 0.8 | 20.5 | 24.8 | 7.05 ± 0.79 |
| lanjian | input-mattcl | 23.5 ± 0.8 | 22.4 | 26.1 | 7.72 ± 0.85 |
| mattcl-py | input-pting | 154.7 ± 3.7 | 152.2 | 168.8 | 50.92 ± 5.51 |
| mattcl-py | input-lanjian | 168.3 ± 2.0 | 165.2 | 173.3 | 55.38 ± 5.88 |
| pting | input-pting | 174.0 ± 2.7 | 168.7 | 178.7 | 57.27 ± 6.11 |
| pting | input-lanjian | 191.2 ± 2.6 | 187.0 | 196.7 | 62.91 ± 6.69 |
| mattcl-py | input-kcen | 197.2 ± 4.2 | 193.3 | 206.8 | 64.91 ± 6.98 |
| mattcl-py | input-mattcl | 203.9 ± 2.1 | 200.5 | 207.7 | 67.11 ± 7.11 |
| pting | input-kcen | 223.6 ± 3.4 | 217.6 | 231.1 | 73.59 ± 7.84 |
| pting | input-mattcl | 237.0 ± 3.0 | 231.7 | 242.5 | 77.99 ± 8.29 |
| kcen | input-pting | 565.2 ± 2.6 | 561.7 | 568.8 | 186.01 ± 19.64 |
| kcen | input-lanjian | 623.0 ± 4.9 | 616.3 | 627.9 | 205.04 ± 21.69 |
| kcen | input-kcen | 727.4 ± 5.5 | 724.3 | 735.7 | 239.40 ± 25.32 |
| kcen | input-mattcl | 790.2 ± 9.3 | 780.9 | 799.5 | 260.05 ± 27.60 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|