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
| mattcl | input-lanjian | 3.0 ± 0.2 | 2.3 | 4.4 | 1.00 |
| mattcl | input-pting | 3.0 ± 0.3 | 2.2 | 5.3 | 1.01 ± 0.12 |
| mattcl | input-kcen | 3.4 ± 0.4 | 2.5 | 5.0 | 1.12 ± 0.17 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.1 | 6.3 | 1.30 ± 0.18 |
| lanjian | input-pting | 18.9 ± 0.9 | 17.5 | 22.2 | 6.30 ± 0.57 |
| lanjian | input-lanjian | 19.6 ± 0.7 | 18.4 | 22.3 | 6.56 ± 0.56 |
| lanjian | input-kcen | 22.4 ± 2.8 | 20.9 | 53.2 | 7.49 ± 1.10 |
| lanjian | input-mattcl | 24.5 ± 0.9 | 23.0 | 27.4 | 8.17 ± 0.70 |
| mattcl-py | input-pting | 157.3 ± 3.1 | 152.1 | 164.2 | 52.54 ± 4.21 |
| mattcl-py | input-lanjian | 169.0 ± 2.0 | 165.3 | 173.6 | 56.43 ± 4.44 |
| pting | input-pting | 177.9 ± 3.2 | 171.0 | 182.9 | 59.42 ± 4.74 |
| pting | input-lanjian | 194.4 ± 4.9 | 185.8 | 202.8 | 64.90 ± 5.30 |
| mattcl-py | input-kcen | 195.4 ± 3.2 | 192.1 | 202.5 | 65.24 ± 5.18 |
| mattcl-py | input-mattcl | 207.4 ± 12.3 | 200.5 | 249.4 | 69.25 ± 6.77 |
| pting | input-kcen | 224.8 ± 4.4 | 217.9 | 232.9 | 75.08 ± 6.02 |
| pting | input-mattcl | 243.3 ± 10.1 | 236.0 | 273.5 | 81.23 ± 7.16 |
| kcen | input-pting | 571.3 ± 5.0 | 564.7 | 578.6 | 190.78 ± 14.92 |
| kcen | input-lanjian | 629.5 ± 12.0 | 612.7 | 640.3 | 210.20 ± 16.81 |
| kcen | input-kcen | 730.1 ± 5.6 | 724.3 | 736.8 | 243.80 ± 19.03 |
| kcen | input-mattcl | 806.1 ± 8.4 | 800.0 | 815.7 | 269.19 ± 21.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|