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
| whyando | input-mattcl | 628.8 ± 164.8 | 0.0 | 1022.6 | 1.00 |
| whyando | input-whyando | 643.3 ± 140.3 | 146.1 | 1187.6 | 1.02 ± 0.35 |
| whyando | input-lanjian | 652.6 ± 162.5 | 0.0 | 1110.9 | 1.04 ± 0.38 |
| mattcl | input-lanjian | 761.4 ± 383.2 | 0.0 | 1764.6 | 1.21 ± 0.69 |
| kcen | input-mattcl | 842.8 ± 143.5 | 0.0 | 1276.6 | 1.34 ± 0.42 |
| kcen | input-whyando | 858.4 ± 162.8 | 253.2 | 1575.0 | 1.37 ± 0.44 |
| kcen | input-lanjian | 886.5 ± 216.2 | 0.0 | 1525.2 | 1.41 ± 0.50 |
| mattcl | input-mattcl | 998.4 ± 166.9 | 0.0 | 1654.9 | 1.59 ± 0.49 |
| mattcl | input-whyando | 1030.4 ± 162.8 | 429.7 | 1677.0 | 1.64 ± 0.50 |
| lanjian | input-lanjian | 1152.7 ± 357.2 | 123.8 | 2548.2 | 1.83 ± 0.74 |
| lanjian | input-whyando | 1315.8 ± 220.7 | 288.1 | 2030.5 | 2.09 ± 0.65 |
| lanjian | input-mattcl | 1348.9 ± 209.7 | 653.1 | 2097.5 | 2.15 ± 0.65 |
| mattcl-py | input-whyando | 18201.3 ± 555.1 | 17362.8 | 21481.5 | 28.95 ± 7.64 |
| mattcl-py | input-lanjian | 18233.1 ± 666.8 | 17280.7 | 21661.7 | 29.00 ± 7.67 |
| mattcl-py | input-mattcl | 18247.7 ± 547.0 | 17330.1 | 21274.4 | 29.02 ± 7.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|