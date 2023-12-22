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
| mattcl | input-lanjian | 3.1 ± 0.2 | 2.3 | 3.7 | 1.00 |
| mattcl | input-pting | 3.1 ± 0.2 | 2.2 | 5.4 | 1.01 ± 0.10 |
| mattcl | input-kcen | 3.4 ± 0.3 | 2.7 | 5.1 | 1.12 ± 0.12 |
| mattcl | input-mattcl | 3.9 ± 0.4 | 3.3 | 6.1 | 1.27 ± 0.16 |
| lanjian | input-pting | 18.8 ± 0.7 | 17.7 | 21.6 | 6.15 ± 0.44 |
| lanjian | input-lanjian | 19.9 ± 1.0 | 18.8 | 23.1 | 6.50 ± 0.50 |
| lanjian | input-kcen | 22.2 ± 0.8 | 21.4 | 25.5 | 7.26 ± 0.51 |
| lanjian | input-mattcl | 24.6 ± 1.0 | 23.5 | 27.5 | 8.05 ± 0.58 |
| mattcl-py | input-pting | 155.8 ± 2.1 | 153.0 | 160.5 | 50.93 ± 3.15 |
| mattcl-py | input-lanjian | 168.8 ± 1.8 | 166.4 | 171.6 | 55.18 ± 3.38 |
| pting | input-pting | 174.8 ± 2.2 | 171.0 | 179.4 | 57.16 ± 3.53 |
| pting | input-lanjian | 192.6 ± 2.8 | 188.5 | 198.3 | 62.97 ± 3.91 |
| mattcl-py | input-kcen | 195.6 ± 2.2 | 191.7 | 198.8 | 63.94 ± 3.93 |
| mattcl-py | input-mattcl | 204.4 ± 3.7 | 200.8 | 214.3 | 66.81 ± 4.21 |
| pting | input-kcen | 225.4 ± 10.5 | 218.7 | 258.2 | 73.68 ± 5.62 |
| pting | input-mattcl | 241.0 ± 3.6 | 235.4 | 248.3 | 78.78 ± 4.90 |
| kcen | input-pting | 567.1 ± 6.1 | 561.1 | 573.8 | 185.39 ± 11.38 |
| kcen | input-lanjian | 625.1 ± 8.4 | 617.2 | 636.9 | 204.39 ± 12.65 |
| kcen | input-kcen | 751.7 ± 41.4 | 721.9 | 811.4 | 245.76 ± 20.08 |
| kcen | input-mattcl | 796.3 ± 12.5 | 783.2 | 808.2 | 260.34 ± 16.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|