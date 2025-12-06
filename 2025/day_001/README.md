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
| whyando | input-mattcl | 500.7 ± 255.3 | 0.0 | 1149.0 | 1.00 |
| whyando | input-whyando | 584.2 ± 163.8 | 0.0 | 992.2 | 1.17 ± 0.68 |
| whyando | input-lanjian | 610.5 ± 142.2 | 0.0 | 1028.7 | 1.22 ± 0.68 |
| kcen | input-mattcl | 768.8 ± 183.3 | 0.0 | 1282.5 | 1.54 ± 0.86 |
| kcen | input-whyando | 821.7 ± 124.0 | 286.0 | 1252.8 | 1.64 ± 0.87 |
| kcen | input-lanjian | 903.5 ± 203.7 | 227.3 | 1831.7 | 1.80 ± 1.01 |
| mattcl | input-whyando | 984.8 ± 160.6 | 440.5 | 1700.8 | 1.97 ± 1.05 |
| mattcl | input-lanjian | 1014.7 ± 161.5 | 427.5 | 1731.0 | 2.03 ± 1.08 |
| mattcl | input-mattcl | 1045.9 ± 215.4 | 458.3 | 1854.3 | 2.09 ± 1.15 |
| lanjian | input-whyando | 1323.2 ± 175.3 | 478.9 | 2076.1 | 2.64 ± 1.39 |
| lanjian | input-mattcl | 1332.8 ± 159.9 | 633.1 | 2174.2 | 2.66 ± 1.39 |
| lanjian | input-lanjian | 1336.6 ± 190.6 | 612.8 | 2559.4 | 2.67 ± 1.41 |
| mattcl-py | input-mattcl | 18239.6 ± 527.3 | 16988.3 | 21220.6 | 36.43 ± 18.61 |
| mattcl-py | input-whyando | 18245.1 ± 702.6 | 17199.2 | 21510.4 | 36.44 ± 18.64 |
| mattcl-py | input-lanjian | 18276.3 ± 680.6 | 17149.4 | 21494.3 | 36.50 ± 18.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|