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
| whyando | input-lanjian | 550.3 ± 176.7 | 0.0 | 1027.5 | 1.00 |
| whyando | input-mattcl | 563.0 ± 161.8 | 0.0 | 971.4 | 1.02 ± 0.44 |
| whyando | input-whyando | 596.0 ± 113.6 | 211.6 | 1027.3 | 1.08 ± 0.40 |
| kcen | input-whyando | 806.9 ± 164.2 | 0.0 | 1343.4 | 1.47 ± 0.56 |
| kcen | input-lanjian | 817.2 ± 115.4 | 336.1 | 1312.8 | 1.48 ± 0.52 |
| kcen | input-mattcl | 836.2 ± 175.3 | 0.0 | 1605.7 | 1.52 ± 0.58 |
| mattcl | input-mattcl | 993.0 ± 161.7 | 443.5 | 1640.7 | 1.80 ± 0.65 |
| mattcl | input-whyando | 1035.0 ± 177.3 | 413.6 | 1646.7 | 1.88 ± 0.68 |
| mattcl | input-lanjian | 1039.1 ± 184.2 | 379.4 | 1890.7 | 1.89 ± 0.69 |
| lanjian | input-whyando | 1132.2 ± 199.4 | 473.3 | 2163.3 | 2.06 ± 0.75 |
| lanjian | input-lanjian | 1172.8 ± 243.5 | 152.9 | 2061.8 | 2.13 ± 0.81 |
| lanjian | input-mattcl | 1191.0 ± 195.4 | 478.4 | 2014.0 | 2.16 ± 0.78 |
| mattcl-py | input-whyando | 20404.0 ± 512.4 | 19359.4 | 23672.7 | 37.07 ± 11.94 |
| mattcl-py | input-mattcl | 20674.8 ± 681.9 | 19349.5 | 23805.7 | 37.57 ± 12.12 |
| mattcl-py | input-lanjian | 20681.1 ± 562.0 | 19598.4 | 23369.7 | 37.58 ± 12.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|