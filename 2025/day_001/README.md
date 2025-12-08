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
| mattcl | input-mattcl | 521.5 ± 202.9 | 0.0 | 1044.1 | 1.00 |
| whyando | input-mattcl | 543.6 ± 145.0 | 0.0 | 906.7 | 1.04 ± 0.49 |
| whyando | input-lanjian | 546.2 ± 173.9 | 0.0 | 1078.7 | 1.05 ± 0.53 |
| mattcl | input-whyando | 563.0 ± 189.9 | 0.0 | 1124.9 | 1.08 ± 0.56 |
| whyando | input-whyando | 571.7 ± 136.2 | 0.0 | 898.8 | 1.10 ± 0.50 |
| mattcl | input-lanjian | 599.8 ± 173.2 | 0.0 | 1267.0 | 1.15 ± 0.56 |
| lanjian | input-lanjian | 889.4 ± 198.9 | 0.0 | 1470.2 | 1.71 ± 0.77 |
| kcen | input-whyando | 891.0 ± 139.0 | 3.3 | 1410.9 | 1.71 ± 0.72 |
| lanjian | input-whyando | 904.0 ± 152.4 | 0.0 | 1511.7 | 1.73 ± 0.74 |
| lanjian | input-mattcl | 911.3 ± 138.2 | 183.7 | 1393.4 | 1.75 ± 0.73 |
| kcen | input-lanjian | 913.7 ± 154.4 | 362.7 | 1451.4 | 1.75 ± 0.74 |
| kcen | input-mattcl | 917.4 ± 170.6 | 316.4 | 1442.7 | 1.76 ± 0.76 |
| mattcl-py | input-whyando | 18238.2 ± 533.8 | 17340.7 | 21487.6 | 34.97 ± 13.65 |
| mattcl-py | input-mattcl | 18291.3 ± 708.4 | 17290.2 | 21541.0 | 35.07 ± 13.71 |
| mattcl-py | input-lanjian | 18320.1 ± 707.4 | 17027.5 | 21807.7 | 35.13 ± 13.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|