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
| mattcl | input-pting | 3.1 ± 0.4 | 2.2 | 5.7 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.3 | 2.2 | 5.9 | 1.00 ± 0.16 |
| mattcl | input-kcen | 3.4 ± 0.5 | 2.6 | 6.0 | 1.11 ± 0.20 |
| mattcl | input-mattcl | 3.8 ± 0.4 | 3.0 | 5.4 | 1.23 ± 0.19 |
| lanjian | input-pting | 18.1 ± 0.7 | 17.1 | 21.1 | 5.82 ± 0.73 |
| lanjian | input-lanjian | 19.1 ± 0.9 | 18.2 | 23.2 | 6.14 ± 0.79 |
| lanjian | input-kcen | 21.4 ± 0.8 | 20.6 | 25.0 | 6.87 ± 0.86 |
| lanjian | input-mattcl | 23.6 ± 0.8 | 22.4 | 26.9 | 7.61 ± 0.95 |
| mattcl-py | input-pting | 157.7 ± 8.8 | 152.8 | 188.0 | 50.77 ± 6.69 |
| mattcl-py | input-lanjian | 168.5 ± 2.0 | 165.4 | 172.1 | 54.23 ± 6.50 |
| pting | input-pting | 177.8 ± 2.8 | 174.6 | 184.6 | 57.22 ± 6.89 |
| pting | input-lanjian | 195.6 ± 5.7 | 189.8 | 213.2 | 62.97 ± 7.73 |
| mattcl-py | input-kcen | 196.3 ± 1.7 | 192.6 | 198.8 | 63.20 ± 7.56 |
| mattcl-py | input-mattcl | 203.8 ± 2.5 | 201.0 | 209.7 | 65.60 ± 7.87 |
| pting | input-kcen | 225.4 ± 2.9 | 220.2 | 229.8 | 72.55 ± 8.71 |
| pting | input-mattcl | 245.6 ± 16.3 | 233.6 | 295.9 | 79.05 ± 10.79 |
| kcen | input-pting | 564.1 ± 4.6 | 560.3 | 572.1 | 181.59 ± 21.73 |
| kcen | input-lanjian | 624.4 ± 3.4 | 619.8 | 627.3 | 200.98 ± 24.01 |
| kcen | input-kcen | 735.4 ± 10.0 | 721.8 | 744.1 | 236.71 ± 28.44 |
| kcen | input-mattcl | 815.4 ± 7.6 | 806.9 | 821.7 | 262.48 ± 31.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|