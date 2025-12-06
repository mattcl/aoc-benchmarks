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
| kcen | input-whyando | 891.3 ± 153.1 | 341.0 | 1096.7 | 1.00 |
| kcen | input-lanjian | 897.7 ± 149.1 | 0.0 | 1125.5 | 1.01 ± 0.24 |
| whyando | input-mattcl | 1003.4 ± 176.8 | 300.1 | 1303.6 | 1.13 ± 0.28 |
| whyando | input-lanjian | 1035.7 ± 148.0 | 289.3 | 1358.2 | 1.16 ± 0.26 |
| mattcl | input-mattcl | 1038.9 ± 189.2 | 368.2 | 1684.8 | 1.17 ± 0.29 |
| mattcl | input-whyando | 1071.0 ± 161.8 | 475.1 | 1347.6 | 1.20 ± 0.27 |
| mattcl | input-lanjian | 1080.8 ± 162.0 | 435.5 | 1297.9 | 1.21 ± 0.28 |
| whyando | input-whyando | 1145.0 ± 1724.5 | 74.0 | 12278.0 | 1.28 ± 1.95 |
| lanjian | input-whyando | 1338.5 ± 239.6 | 304.8 | 1699.2 | 1.50 ± 0.37 |
| lanjian | input-lanjian | 1376.1 ± 112.9 | 532.4 | 1503.4 | 1.54 ± 0.29 |
| kcen | input-mattcl | 1787.9 ± 3353.2 | 0.0 | 18124.1 | 2.01 ± 3.78 |
| lanjian | input-mattcl | 1851.2 ± 2645.6 | 121.9 | 19009.1 | 2.08 ± 2.99 |
| mattcl-py | input-lanjian | 18644.6 ± 359.2 | 17716.6 | 20374.6 | 20.92 ± 3.62 |
| mattcl-py | input-mattcl | 18680.7 ± 574.7 | 17532.1 | 21586.8 | 20.96 ± 3.66 |
| mattcl-py | input-whyando | 18782.1 ± 478.7 | 17900.0 | 20874.2 | 21.07 ± 3.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|