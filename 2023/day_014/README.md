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
| mattcl | input-pting | 3.0 ± 0.3 | 2.2 | 5.1 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.2 | 2.3 | 4.3 | 1.01 ± 0.12 |
| mattcl | input-kcen | 3.4 ± 0.5 | 2.6 | 7.4 | 1.11 ± 0.21 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.1 | 5.9 | 1.27 ± 0.18 |
| lanjian | input-pting | 18.2 ± 1.0 | 17.3 | 21.8 | 6.03 ± 0.68 |
| lanjian | input-lanjian | 18.8 ± 0.6 | 17.9 | 22.2 | 6.23 ± 0.64 |
| lanjian | input-kcen | 21.3 ± 0.7 | 20.4 | 24.4 | 7.04 ± 0.73 |
| lanjian | input-mattcl | 23.3 ± 0.8 | 22.2 | 26.2 | 7.72 ± 0.80 |
| mattcl-py | input-pting | 154.5 ± 1.5 | 152.4 | 158.0 | 51.13 ± 5.05 |
| mattcl-py | input-lanjian | 167.7 ± 2.4 | 164.4 | 172.3 | 55.49 ± 5.51 |
| pting | input-pting | 175.0 ± 2.0 | 171.9 | 179.9 | 57.90 ± 5.73 |
| pting | input-lanjian | 192.2 ± 2.5 | 187.6 | 196.9 | 63.59 ± 6.31 |
| mattcl-py | input-kcen | 195.8 ± 3.1 | 191.3 | 201.3 | 64.78 ± 6.45 |
| mattcl-py | input-mattcl | 205.6 ± 6.0 | 200.5 | 223.9 | 68.03 ± 6.98 |
| pting | input-kcen | 222.0 ± 2.7 | 218.0 | 226.0 | 73.48 ± 7.28 |
| pting | input-mattcl | 239.3 ± 4.7 | 230.1 | 247.8 | 79.20 ± 7.94 |
| kcen | input-pting | 571.4 ± 10.5 | 559.9 | 585.5 | 189.10 ± 18.91 |
| kcen | input-lanjian | 617.1 ± 3.7 | 612.1 | 620.0 | 204.20 ± 20.11 |
| kcen | input-kcen | 722.4 ± 12.3 | 714.8 | 740.5 | 239.06 ± 23.85 |
| kcen | input-mattcl | 810.9 ± 8.6 | 801.1 | 817.2 | 268.34 ± 26.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|