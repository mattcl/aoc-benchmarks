# Day 2 benchmarks

[link to problem](https://adventofcode.com/2025/day/2)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 2)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 167.4 ± 196.9 | 0.0 | 692.7 | 1.00 |
| whyando | input-mattcl | 439.2 ± 152.3 | 0.0 | 946.5 | 2.62 ± 3.22 |
| whyando | input-whyando | 453.5 ± 136.4 | 0.0 | 940.6 | 2.71 ± 3.29 |
| mattcl | input-whyando | 648.4 ± 167.5 | 0.0 | 1068.0 | 3.87 ± 4.66 |
| lanjian | input-whyando | 664.9 ± 173.3 | 0.0 | 1113.3 | 3.97 ± 4.78 |
| mattcl | input-lanjian | 666.9 ± 226.0 | 0.0 | 2593.2 | 3.98 ± 4.87 |
| mattcl | input-mattcl | 671.7 ± 121.4 | 86.8 | 1080.7 | 4.01 ± 4.77 |
| kcen | input-mattcl | 691.4 ± 267.2 | 0.0 | 1034.2 | 4.13 ± 5.11 |
| lanjian | input-mattcl | 702.7 ± 137.1 | 0.0 | 1082.9 | 4.20 ± 5.00 |
| lanjian | input-lanjian | 720.9 ± 153.0 | 121.4 | 1383.6 | 4.31 ± 5.14 |
| kcen | input-whyando | 799.3 ± 168.4 | 0.0 | 1308.0 | 4.77 ± 5.70 |
| kcen | input-lanjian | 839.5 ± 160.9 | 330.7 | 1376.0 | 5.01 ± 5.97 |
| mattcl-py | input-whyando | 20562.7 ± 850.8 | 19055.1 | 24076.1 | 122.81 ± 144.50 |
| mattcl-py | input-lanjian | 20685.0 ± 516.3 | 19773.8 | 23088.8 | 123.54 ± 145.30 |
| mattcl-py | input-mattcl | 20708.1 ± 548.3 | 19849.5 | 24662.3 | 123.67 ± 145.47 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|