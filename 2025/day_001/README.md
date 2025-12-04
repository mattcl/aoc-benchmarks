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
| whyando | input-whyando | 755.1 ± 139.1 | 0.0 | 1165.8 | 1.00 |
| whyando | input-lanjian | 767.8 ± 139.2 | 0.0 | 1275.6 | 1.02 ± 0.26 |
| whyando | input-mattcl | 773.4 ± 139.2 | 0.0 | 1147.0 | 1.02 ± 0.26 |
| kcen | input-whyando | 881.5 ± 105.9 | 388.6 | 1286.8 | 1.17 ± 0.26 |
| kcen | input-mattcl | 885.6 ± 139.4 | 440.3 | 1541.2 | 1.17 ± 0.28 |
| kcen | input-lanjian | 915.1 ± 183.5 | 263.2 | 1617.6 | 1.21 ± 0.33 |
| mattcl | input-whyando | 1041.9 ± 154.6 | 428.0 | 1793.9 | 1.38 ± 0.33 |
| mattcl | input-mattcl | 1058.5 ± 179.0 | 571.6 | 1758.6 | 1.40 ± 0.35 |
| mattcl | input-lanjian | 1058.9 ± 143.2 | 570.6 | 1746.8 | 1.40 ± 0.32 |
| lanjian | input-whyando | 1364.2 ± 182.7 | 669.9 | 2068.3 | 1.81 ± 0.41 |
| lanjian | input-mattcl | 1365.4 ± 218.9 | 572.7 | 2641.0 | 1.81 ± 0.44 |
| lanjian | input-lanjian | 1369.7 ± 205.9 | 482.9 | 2160.6 | 1.81 ± 0.43 |
| mattcl-py | input-whyando | 18228.5 ± 585.4 | 16931.1 | 21053.3 | 24.14 ± 4.51 |
| mattcl-py | input-mattcl | 18253.2 ± 674.1 | 17320.6 | 21449.8 | 24.17 ± 4.54 |
| mattcl-py | input-lanjian | 18389.8 ± 766.6 | 17057.6 | 22139.1 | 24.35 ± 4.60 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|