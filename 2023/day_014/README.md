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
| mattcl | input-lanjian | 3.0 ± 0.2 | 2.2 | 4.0 | 1.00 |
| mattcl | input-pting | 3.0 ± 0.3 | 2.3 | 4.5 | 1.01 ± 0.12 |
| mattcl | input-kcen | 3.4 ± 0.4 | 2.6 | 6.1 | 1.13 ± 0.16 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.1 | 6.2 | 1.31 ± 0.15 |
| lanjian | input-pting | 18.3 ± 0.7 | 17.4 | 21.8 | 6.11 ± 0.45 |
| lanjian | input-lanjian | 19.3 ± 0.7 | 18.1 | 22.2 | 6.45 ± 0.47 |
| lanjian | input-kcen | 21.6 ± 0.6 | 20.6 | 24.6 | 7.22 ± 0.51 |
| lanjian | input-mattcl | 23.7 ± 0.8 | 22.5 | 26.8 | 7.92 ± 0.58 |
| mattcl-py | input-pting | 155.5 ± 2.6 | 151.5 | 162.9 | 52.03 ± 3.43 |
| mattcl-py | input-lanjian | 169.2 ± 2.6 | 164.9 | 176.8 | 56.59 ± 3.71 |
| pting | input-pting | 176.8 ± 3.0 | 171.0 | 180.7 | 59.13 ± 3.90 |
| pting | input-lanjian | 193.4 ± 4.2 | 186.6 | 201.4 | 64.69 ± 4.36 |
| mattcl-py | input-kcen | 194.1 ± 1.6 | 192.1 | 197.6 | 64.95 ± 4.17 |
| mattcl-py | input-mattcl | 205.0 ± 3.8 | 201.1 | 213.5 | 68.58 ± 4.55 |
| pting | input-kcen | 223.3 ± 3.2 | 215.2 | 228.2 | 74.72 ± 4.89 |
| pting | input-mattcl | 247.6 ± 27.3 | 235.6 | 333.9 | 82.83 ± 10.55 |
| kcen | input-pting | 570.7 ± 6.8 | 566.3 | 582.6 | 190.92 ± 12.38 |
| kcen | input-lanjian | 622.5 ± 10.5 | 611.4 | 632.2 | 208.24 ± 13.73 |
| kcen | input-kcen | 734.7 ± 10.0 | 721.1 | 744.6 | 245.80 ± 16.02 |
| kcen | input-mattcl | 794.1 ± 8.3 | 784.8 | 800.6 | 265.67 ± 17.16 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|