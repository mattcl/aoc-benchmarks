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
| mattcl | input-pting | 3.1 ± 0.3 | 2.3 | 5.3 | 1.00 |
| mattcl | input-lanjian | 3.2 ± 0.4 | 2.4 | 6.0 | 1.02 ± 0.16 |
| mattcl | input-kcen | 3.5 ± 0.3 | 3.0 | 5.2 | 1.13 ± 0.14 |
| mattcl | input-mattcl | 4.0 ± 0.4 | 3.2 | 6.3 | 1.30 ± 0.18 |
| lanjian | input-pting | 19.1 ± 0.8 | 18.1 | 22.3 | 6.16 ± 0.64 |
| lanjian | input-lanjian | 19.9 ± 0.6 | 18.8 | 22.6 | 6.40 ± 0.63 |
| lanjian | input-kcen | 22.6 ± 0.8 | 21.6 | 26.2 | 7.28 ± 0.74 |
| lanjian | input-mattcl | 24.8 ± 1.0 | 23.6 | 28.1 | 7.99 ± 0.81 |
| mattcl-py | input-pting | 158.6 ± 7.5 | 151.6 | 187.3 | 51.06 ± 5.38 |
| mattcl-py | input-lanjian | 167.8 ± 1.6 | 163.6 | 171.5 | 54.05 ± 5.12 |
| pting | input-pting | 177.7 ± 3.1 | 174.5 | 186.7 | 57.23 ± 5.48 |
| pting | input-lanjian | 192.9 ± 2.3 | 188.7 | 197.0 | 62.12 ± 5.90 |
| mattcl-py | input-kcen | 193.9 ± 2.1 | 191.0 | 198.7 | 62.44 ± 5.92 |
| mattcl-py | input-mattcl | 204.4 ± 4.3 | 200.2 | 217.8 | 65.82 ± 6.35 |
| pting | input-kcen | 225.7 ± 3.2 | 220.7 | 232.3 | 72.69 ± 6.93 |
| pting | input-mattcl | 240.2 ± 4.6 | 233.0 | 248.8 | 77.34 ± 7.44 |
| kcen | input-pting | 575.9 ± 9.7 | 564.5 | 585.7 | 185.44 ± 17.75 |
| kcen | input-lanjian | 635.9 ± 9.4 | 627.0 | 649.0 | 204.75 ± 19.53 |
| kcen | input-kcen | 729.2 ± 8.7 | 720.7 | 736.8 | 234.80 ± 22.30 |
| kcen | input-mattcl | 816.2 ± 13.9 | 803.4 | 831.0 | 262.82 ± 25.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|