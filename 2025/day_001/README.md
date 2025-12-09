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
| whyando | input-lanjian | 506.0 ± 173.9 | 0.0 | 1105.4 | 1.00 |
| mattcl | input-mattcl | 512.5 ± 144.9 | 0.0 | 862.8 | 1.01 ± 0.45 |
| whyando | input-mattcl | 524.0 ± 148.4 | 0.0 | 996.0 | 1.04 ± 0.46 |
| whyando | input-whyando | 528.6 ± 137.9 | 0.0 | 957.0 | 1.04 ± 0.45 |
| mattcl | input-whyando | 532.4 ± 162.3 | 0.0 | 1284.2 | 1.05 ± 0.48 |
| mattcl | input-lanjian | 535.9 ± 156.5 | 0.0 | 992.3 | 1.06 ± 0.48 |
| kcen | input-lanjian | 844.1 ± 139.6 | 138.0 | 1283.6 | 1.67 ± 0.64 |
| kcen | input-whyando | 845.8 ± 172.6 | 0.0 | 1384.4 | 1.67 ± 0.67 |
| kcen | input-mattcl | 849.3 ± 144.5 | 0.0 | 1320.3 | 1.68 ± 0.64 |
| lanjian | input-mattcl | 856.7 ± 164.5 | 0.0 | 1333.2 | 1.69 ± 0.67 |
| lanjian | input-whyando | 869.2 ± 119.7 | 417.2 | 1325.2 | 1.72 ± 0.64 |
| lanjian | input-lanjian | 872.9 ± 158.4 | 0.0 | 1373.3 | 1.73 ± 0.67 |
| mattcl-py | input-mattcl | 18258.2 ± 486.6 | 17377.1 | 20780.4 | 36.09 ± 12.44 |
| mattcl-py | input-whyando | 18286.2 ± 683.2 | 17333.2 | 21442.3 | 36.14 ± 12.49 |
| mattcl-py | input-lanjian | 18329.6 ± 655.1 | 17222.3 | 21539.3 | 36.23 ± 12.52 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|