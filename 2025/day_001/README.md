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
| mattcl | input-whyando | 565.3 ± 346.9 | 0.0 | 1374.0 | 1.00 |
| whyando | input-mattcl | 639.8 ± 178.1 | 0.0 | 1390.3 | 1.13 ± 0.76 |
| whyando | input-lanjian | 641.7 ± 156.6 | 0.0 | 1187.6 | 1.14 ± 0.75 |
| whyando | input-whyando | 645.9 ± 163.8 | 0.0 | 1212.7 | 1.14 ± 0.76 |
| lanjian | input-whyando | 816.6 ± 435.5 | 121.4 | 2156.7 | 1.44 ± 1.17 |
| kcen | input-whyando | 827.4 ± 188.0 | 0.0 | 1386.1 | 1.46 ± 0.96 |
| kcen | input-mattcl | 829.0 ± 159.2 | 0.0 | 1337.7 | 1.47 ± 0.94 |
| kcen | input-lanjian | 832.6 ± 140.0 | 312.3 | 1340.1 | 1.47 ± 0.94 |
| mattcl | input-lanjian | 1007.0 ± 162.0 | 530.5 | 1664.8 | 1.78 ± 1.13 |
| mattcl | input-mattcl | 1035.7 ± 198.3 | 196.8 | 1708.7 | 1.83 ± 1.18 |
| lanjian | input-lanjian | 1350.8 ± 203.4 | 426.0 | 2428.5 | 2.39 ± 1.51 |
| lanjian | input-mattcl | 1377.2 ± 166.4 | 705.7 | 1890.4 | 2.44 ± 1.52 |
| mattcl-py | input-mattcl | 18224.0 ± 632.0 | 17010.4 | 22275.3 | 32.24 ± 19.81 |
| mattcl-py | input-lanjian | 18254.8 ± 685.8 | 16791.1 | 21133.8 | 32.29 ± 19.85 |
| mattcl-py | input-whyando | 18277.5 ± 730.4 | 16774.4 | 21384.1 | 32.33 ± 19.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|