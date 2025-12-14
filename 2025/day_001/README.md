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
| mattcl | input-mattcl | 168.0 ± 178.7 | 0.0 | 579.8 | 1.00 |
| whyando | input-lanjian | 310.9 ± 230.4 | 0.0 | 969.3 | 1.85 ± 2.40 |
| mattcl | input-whyando | 397.2 ± 219.9 | 0.0 | 1073.3 | 2.36 ± 2.84 |
| mattcl | input-lanjian | 431.8 ± 183.1 | 0.0 | 982.9 | 2.57 ± 2.94 |
| lanjian | input-mattcl | 439.3 ± 275.4 | 0.0 | 1236.0 | 2.61 ± 3.23 |
| whyando | input-mattcl | 477.4 ± 171.2 | 0.0 | 1020.5 | 2.84 ± 3.19 |
| whyando | input-whyando | 503.1 ± 177.6 | 0.0 | 977.8 | 2.99 ± 3.36 |
| lanjian | input-whyando | 625.4 ± 292.3 | 0.0 | 1308.9 | 3.72 ± 4.33 |
| kcen | input-mattcl | 748.0 ± 227.1 | 0.0 | 1258.8 | 4.45 ± 4.93 |
| lanjian | input-lanjian | 808.7 ± 167.3 | 0.0 | 1421.4 | 4.81 ± 5.22 |
| kcen | input-lanjian | 812.0 ± 150.3 | 283.3 | 1287.4 | 4.83 ± 5.22 |
| kcen | input-whyando | 821.3 ± 120.0 | 266.2 | 1328.0 | 4.89 ± 5.25 |
| mattcl-py | input-whyando | 18215.9 ± 805.9 | 16883.0 | 21471.3 | 108.43 ± 115.43 |
| mattcl-py | input-lanjian | 18333.8 ± 660.0 | 17377.2 | 21275.2 | 109.13 ± 116.14 |
| mattcl-py | input-mattcl | 18451.4 ± 746.2 | 16918.4 | 22106.3 | 109.83 ± 116.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|