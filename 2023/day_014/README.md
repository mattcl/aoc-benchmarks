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
| mattcl | input-pting | 3.0 ± 0.3 | 2.2 | 5.6 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.2 | 2.3 | 4.8 | 1.01 ± 0.13 |
| mattcl | input-kcen | 3.4 ± 0.4 | 2.7 | 5.9 | 1.13 ± 0.18 |
| mattcl | input-mattcl | 3.9 ± 0.5 | 3.2 | 6.6 | 1.30 ± 0.20 |
| lanjian | input-pting | 18.9 ± 3.7 | 17.1 | 52.6 | 6.23 ± 1.37 |
| lanjian | input-lanjian | 19.2 ± 0.6 | 18.0 | 21.7 | 6.36 ± 0.69 |
| lanjian | input-kcen | 21.6 ± 0.7 | 20.5 | 24.4 | 7.13 ± 0.77 |
| lanjian | input-mattcl | 23.9 ± 1.0 | 22.5 | 27.4 | 7.90 ± 0.88 |
| mattcl-py | input-pting | 155.8 ± 3.5 | 152.6 | 169.3 | 51.46 ± 5.44 |
| mattcl-py | input-lanjian | 168.3 ± 5.7 | 163.7 | 186.8 | 55.61 ± 6.04 |
| pting | input-pting | 178.3 ± 2.6 | 174.5 | 183.2 | 58.91 ± 6.14 |
| pting | input-lanjian | 191.7 ± 4.3 | 185.0 | 202.2 | 63.34 ± 6.68 |
| mattcl-py | input-kcen | 194.7 ± 3.5 | 188.9 | 204.5 | 64.31 ± 6.73 |
| mattcl-py | input-mattcl | 203.7 ± 3.0 | 198.9 | 210.7 | 67.28 ± 7.01 |
| pting | input-kcen | 224.1 ± 5.7 | 215.0 | 233.7 | 74.02 ± 7.86 |
| pting | input-mattcl | 238.7 ± 4.2 | 232.7 | 245.8 | 78.83 ± 8.25 |
| kcen | input-pting | 590.6 ± 7.4 | 583.6 | 599.1 | 195.09 ± 20.27 |
| kcen | input-lanjian | 649.7 ± 13.7 | 632.9 | 666.2 | 214.62 ± 22.59 |
| kcen | input-kcen | 748.7 ± 11.9 | 738.0 | 762.2 | 247.31 ± 25.81 |
| kcen | input-mattcl | 823.7 ± 4.4 | 819.0 | 827.7 | 272.10 ± 28.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|