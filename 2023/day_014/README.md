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
| mattcl | input-lanjian | 3.2 ± 0.4 | 2.2 | 5.8 | 1.04 ± 0.17 |
| mattcl | input-kcen | 3.5 ± 0.4 | 2.6 | 5.0 | 1.14 ± 0.16 |
| mattcl | input-mattcl | 4.0 ± 0.5 | 3.2 | 7.6 | 1.30 ± 0.20 |
| lanjian | input-pting | 18.9 ± 0.8 | 17.6 | 22.1 | 6.20 ± 0.62 |
| lanjian | input-lanjian | 19.7 ± 0.7 | 18.7 | 22.5 | 6.48 ± 0.63 |
| lanjian | input-kcen | 22.2 ± 0.7 | 21.2 | 25.4 | 7.30 ± 0.70 |
| lanjian | input-mattcl | 24.7 ± 0.9 | 23.1 | 27.5 | 8.10 ± 0.79 |
| mattcl-py | input-pting | 156.1 ± 1.6 | 153.8 | 159.4 | 51.24 ± 4.66 |
| mattcl-py | input-lanjian | 168.8 ± 2.2 | 165.3 | 172.8 | 55.40 ± 5.06 |
| pting | input-pting | 176.2 ± 2.7 | 171.2 | 180.3 | 57.84 ± 5.31 |
| pting | input-lanjian | 191.1 ± 4.1 | 185.1 | 197.6 | 62.71 ± 5.83 |
| mattcl-py | input-kcen | 195.3 ± 2.3 | 191.1 | 201.2 | 64.09 ± 5.85 |
| mattcl-py | input-mattcl | 205.6 ± 3.1 | 200.8 | 212.9 | 67.47 ± 6.19 |
| pting | input-kcen | 222.3 ± 4.0 | 213.7 | 230.4 | 72.96 ± 6.73 |
| pting | input-mattcl | 237.0 ± 5.3 | 228.3 | 248.1 | 77.79 ± 7.25 |
| kcen | input-pting | 608.5 ± 5.1 | 602.4 | 614.3 | 199.74 ± 18.15 |
| kcen | input-lanjian | 671.4 ± 3.9 | 667.2 | 676.7 | 220.38 ± 19.98 |
| kcen | input-kcen | 778.9 ± 6.1 | 772.2 | 784.3 | 255.67 ± 23.22 |
| kcen | input-mattcl | 860.0 ± 19.0 | 848.9 | 882.0 | 282.28 ± 26.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|