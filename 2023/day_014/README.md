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
| mattcl | input-lanjian | 3.1 ± 0.4 | 2.3 | 5.6 | 1.00 |
| mattcl | input-pting | 3.1 ± 0.4 | 2.3 | 4.7 | 1.02 ± 0.18 |
| mattcl | input-kcen | 3.5 ± 0.4 | 2.7 | 5.8 | 1.12 ± 0.20 |
| mattcl | input-mattcl | 4.0 ± 0.5 | 3.1 | 6.5 | 1.30 ± 0.23 |
| lanjian | input-pting | 18.9 ± 0.9 | 17.8 | 22.0 | 6.13 ± 0.82 |
| lanjian | input-lanjian | 19.8 ± 0.8 | 18.6 | 23.1 | 6.41 ± 0.85 |
| lanjian | input-kcen | 22.3 ± 0.9 | 20.9 | 26.1 | 7.24 ± 0.95 |
| lanjian | input-mattcl | 24.4 ± 1.0 | 23.0 | 27.8 | 7.90 ± 1.04 |
| mattcl-py | input-pting | 156.2 ± 5.7 | 152.2 | 179.1 | 50.66 ± 6.62 |
| mattcl-py | input-lanjian | 170.1 ± 2.7 | 166.4 | 176.6 | 55.17 ± 6.97 |
| pting | input-pting | 177.0 ± 1.7 | 173.4 | 180.7 | 57.42 ± 7.22 |
| pting | input-lanjian | 192.8 ± 3.9 | 186.8 | 199.6 | 62.54 ± 7.94 |
| mattcl-py | input-kcen | 197.7 ± 3.3 | 194.9 | 206.1 | 64.12 ± 8.11 |
| mattcl-py | input-mattcl | 204.3 ± 3.0 | 199.4 | 211.8 | 66.25 ± 8.36 |
| pting | input-kcen | 223.5 ± 3.2 | 219.8 | 229.7 | 72.48 ± 9.15 |
| pting | input-mattcl | 239.4 ± 2.4 | 236.9 | 244.8 | 77.66 ± 9.77 |
| kcen | input-pting | 571.3 ± 16.8 | 559.0 | 600.3 | 185.30 ± 23.86 |
| kcen | input-lanjian | 630.7 ± 12.8 | 614.9 | 643.0 | 204.56 ± 25.98 |
| kcen | input-kcen | 732.1 ± 4.2 | 728.4 | 738.1 | 237.47 ± 29.80 |
| kcen | input-mattcl | 811.8 ± 8.8 | 804.2 | 821.5 | 263.33 ± 33.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|