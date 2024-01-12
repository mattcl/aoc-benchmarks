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
| mattcl | input-lanjian | 3.0 ± 0.2 | 2.2 | 3.7 | 1.00 |
| mattcl | input-pting | 3.1 ± 0.4 | 2.3 | 5.9 | 1.00 ± 0.14 |
| mattcl | input-kcen | 3.4 ± 0.3 | 2.6 | 5.1 | 1.11 ± 0.13 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.0 | 6.5 | 1.27 ± 0.17 |
| lanjian | input-pting | 18.5 ± 0.9 | 17.6 | 21.3 | 6.10 ± 0.50 |
| lanjian | input-lanjian | 19.2 ± 0.7 | 18.4 | 22.4 | 6.33 ± 0.49 |
| lanjian | input-kcen | 21.8 ± 0.8 | 20.9 | 25.4 | 7.18 ± 0.56 |
| lanjian | input-mattcl | 23.9 ± 0.9 | 22.9 | 27.0 | 7.86 ± 0.61 |
| mattcl-py | input-pting | 154.1 ± 1.9 | 152.1 | 159.1 | 50.68 ± 3.50 |
| mattcl-py | input-lanjian | 167.6 ± 1.6 | 164.8 | 170.3 | 55.11 ± 3.78 |
| pting | input-pting | 174.9 ± 3.0 | 170.3 | 180.8 | 57.52 ± 4.03 |
| pting | input-lanjian | 191.0 ± 3.1 | 186.4 | 196.6 | 62.83 ± 4.39 |
| mattcl-py | input-kcen | 195.4 ± 2.2 | 192.8 | 201.6 | 64.26 ± 4.42 |
| mattcl-py | input-mattcl | 204.0 ± 3.2 | 199.5 | 211.4 | 67.11 ± 4.67 |
| pting | input-kcen | 223.9 ± 4.2 | 218.0 | 232.7 | 73.64 ± 5.19 |
| pting | input-mattcl | 236.6 ± 2.4 | 233.8 | 241.4 | 77.82 ± 5.34 |
| kcen | input-pting | 597.0 ± 2.9 | 592.8 | 600.6 | 196.35 ± 13.36 |
| kcen | input-lanjian | 651.1 ± 12.8 | 635.5 | 665.0 | 214.15 ± 15.13 |
| kcen | input-kcen | 772.6 ± 10.6 | 766.0 | 784.8 | 254.11 ± 17.60 |
| kcen | input-mattcl | 855.2 ± 5.9 | 848.5 | 859.0 | 281.30 ± 19.19 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|