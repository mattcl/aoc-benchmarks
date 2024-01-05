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
| mattcl | input-pting | 3.1 ± 0.3 | 2.2 | 6.0 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.3 | 2.3 | 5.9 | 1.01 ± 0.14 |
| mattcl | input-kcen | 3.5 ± 0.4 | 3.0 | 5.1 | 1.13 ± 0.17 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.2 | 6.0 | 1.26 ± 0.17 |
| lanjian | input-pting | 18.3 ± 1.0 | 17.3 | 22.2 | 5.95 ± 0.63 |
| lanjian | input-lanjian | 19.1 ± 0.8 | 18.2 | 22.3 | 6.19 ± 0.61 |
| lanjian | input-kcen | 21.4 ± 0.7 | 20.6 | 24.3 | 6.93 ± 0.66 |
| lanjian | input-mattcl | 23.7 ± 0.9 | 22.4 | 27.2 | 7.68 ± 0.75 |
| mattcl-py | input-pting | 156.0 ± 6.5 | 151.5 | 181.0 | 50.65 ± 5.01 |
| mattcl-py | input-lanjian | 169.6 ± 2.6 | 166.3 | 175.6 | 55.06 ± 5.01 |
| pting | input-pting | 174.9 ± 2.0 | 172.7 | 180.0 | 56.79 ± 5.14 |
| pting | input-lanjian | 191.0 ± 4.1 | 184.6 | 201.9 | 62.03 ± 5.72 |
| mattcl-py | input-kcen | 195.8 ± 2.7 | 192.4 | 202.9 | 63.57 ± 5.77 |
| mattcl-py | input-mattcl | 203.0 ± 3.0 | 198.9 | 210.9 | 65.91 ± 5.99 |
| pting | input-kcen | 222.4 ± 3.6 | 217.1 | 227.8 | 72.22 ± 6.59 |
| pting | input-mattcl | 235.2 ± 3.4 | 229.2 | 241.0 | 76.38 ± 6.94 |
| kcen | input-pting | 570.3 ± 13.5 | 557.7 | 585.9 | 185.20 ± 17.19 |
| kcen | input-lanjian | 615.6 ± 3.2 | 611.6 | 619.4 | 199.89 ± 17.97 |
| kcen | input-kcen | 729.8 ± 7.5 | 723.7 | 740.7 | 236.98 ± 21.41 |
| kcen | input-mattcl | 800.2 ± 10.0 | 791.5 | 811.1 | 259.84 ± 23.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|