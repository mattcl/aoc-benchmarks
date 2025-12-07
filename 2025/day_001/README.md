# Day 1 benchmarks

[link to problem](https://adventofcode.com/2025/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-mattcl | 514.9 ± 174.6 | 0.0 | 963.3 | 1.00 |
| whyando | input-whyando | 533.0 ± 142.6 | 0.0 | 798.9 | 1.04 ± 0.45 |
| mattcl | input-mattcl | 536.8 ± 166.1 | 0.0 | 975.5 | 1.04 ± 0.48 |
| whyando | input-lanjian | 546.0 ± 155.6 | 0.0 | 1072.3 | 1.06 ± 0.47 |
| mattcl | input-whyando | 561.2 ± 170.6 | 0.0 | 1049.4 | 1.09 ± 0.50 |
| mattcl | input-lanjian | 569.4 ± 150.8 | 107.9 | 1136.6 | 1.11 ± 0.48 |
| kcen | input-whyando | 842.3 ± 186.6 | 0.0 | 1422.7 | 1.64 ± 0.66 |
| kcen | input-lanjian | 855.7 ± 170.7 | 0.0 | 1352.1 | 1.66 ± 0.65 |
| kcen | input-mattcl | 897.9 ± 192.8 | 0.0 | 1482.9 | 1.74 ± 0.70 |
| lanjian | input-lanjian | 1091.4 ± 280.5 | 32.4 | 2308.9 | 2.12 ± 0.90 |
| lanjian | input-whyando | 1155.5 ± 202.4 | 441.4 | 1889.7 | 2.24 ± 0.86 |
| lanjian | input-mattcl | 1164.1 ± 230.1 | 427.4 | 2038.6 | 2.26 ± 0.89 |
| mattcl-py | input-whyando | 18259.5 ± 559.8 | 17262.8 | 21491.6 | 35.46 ± 12.08 |
| mattcl-py | input-mattcl | 18290.0 ± 728.8 | 17357.3 | 21773.2 | 35.52 ± 12.13 |
| mattcl-py | input-lanjian | 18320.6 ± 639.5 | 17303.2 | 21616.3 | 35.58 ± 12.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|