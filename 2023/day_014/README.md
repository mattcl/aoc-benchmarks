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
| mattcl | input-pting | 3.2 ± 0.4 | 2.3 | 5.8 | 1.00 |
| mattcl | input-lanjian | 3.2 ± 0.4 | 2.8 | 5.9 | 1.00 ± 0.17 |
| mattcl | input-kcen | 3.6 ± 0.4 | 3.1 | 6.7 | 1.11 ± 0.18 |
| mattcl | input-mattcl | 4.1 ± 0.5 | 3.3 | 7.6 | 1.27 ± 0.22 |
| lanjian | input-pting | 18.6 ± 0.7 | 17.5 | 21.9 | 5.79 ± 0.75 |
| lanjian | input-lanjian | 19.4 ± 0.7 | 18.3 | 21.9 | 6.05 ± 0.77 |
| lanjian | input-kcen | 22.0 ± 0.9 | 20.5 | 26.6 | 6.84 ± 0.89 |
| lanjian | input-mattcl | 23.9 ± 0.7 | 22.9 | 26.8 | 7.44 ± 0.94 |
| mattcl-py | input-pting | 156.2 ± 2.0 | 152.1 | 160.5 | 48.69 ± 6.04 |
| mattcl-py | input-lanjian | 170.8 ± 6.8 | 166.0 | 193.6 | 53.26 ± 6.91 |
| pting | input-pting | 176.8 ± 2.8 | 171.9 | 180.8 | 55.12 ± 6.85 |
| pting | input-lanjian | 190.3 ± 2.5 | 186.5 | 197.1 | 59.34 ± 7.36 |
| mattcl-py | input-kcen | 195.5 ± 2.0 | 193.5 | 201.8 | 60.95 ± 7.54 |
| mattcl-py | input-mattcl | 204.7 ± 1.7 | 201.7 | 208.1 | 63.81 ± 7.89 |
| pting | input-kcen | 223.9 ± 2.7 | 219.9 | 229.1 | 69.80 ± 8.65 |
| pting | input-mattcl | 240.4 ± 5.5 | 228.6 | 251.1 | 74.96 ± 9.40 |
| kcen | input-pting | 582.9 ± 8.8 | 578.3 | 598.5 | 181.71 ± 22.58 |
| kcen | input-lanjian | 631.7 ± 5.0 | 626.4 | 638.2 | 196.93 ± 24.34 |
| kcen | input-kcen | 738.8 ± 4.8 | 733.2 | 744.3 | 230.33 ± 28.45 |
| kcen | input-mattcl | 810.4 ± 14.8 | 793.7 | 822.1 | 252.65 ± 31.50 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|