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
| whyando | input-mattcl | 687.7 ± 154.8 | 0.0 | 1087.1 | 1.00 |
| whyando | input-lanjian | 730.9 ± 152.9 | 0.0 | 1207.9 | 1.06 ± 0.33 |
| whyando | input-whyando | 769.1 ± 201.6 | 0.0 | 1713.5 | 1.12 ± 0.39 |
| kcen | input-whyando | 813.3 ± 157.0 | 0.0 | 1369.5 | 1.18 ± 0.35 |
| kcen | input-mattcl | 819.1 ± 164.8 | 233.0 | 1552.2 | 1.19 ± 0.36 |
| kcen | input-lanjian | 826.5 ± 102.4 | 265.3 | 1217.6 | 1.20 ± 0.31 |
| mattcl | input-lanjian | 1048.6 ± 196.7 | 267.8 | 1925.3 | 1.52 ± 0.45 |
| mattcl | input-mattcl | 1054.4 ± 178.0 | 448.6 | 1776.7 | 1.53 ± 0.43 |
| mattcl | input-whyando | 1067.7 ± 202.6 | 455.9 | 1970.3 | 1.55 ± 0.46 |
| lanjian | input-lanjian | 1288.1 ± 217.3 | 361.2 | 1975.9 | 1.87 ± 0.53 |
| lanjian | input-whyando | 1319.7 ± 194.1 | 445.2 | 2074.4 | 1.92 ± 0.52 |
| lanjian | input-mattcl | 1335.7 ± 224.3 | 616.8 | 2097.8 | 1.94 ± 0.55 |
| mattcl-py | input-whyando | 18094.5 ± 500.7 | 17144.2 | 21513.7 | 26.31 ± 5.97 |
| mattcl-py | input-mattcl | 18140.8 ± 405.2 | 17181.9 | 20187.1 | 26.38 ± 5.97 |
| mattcl-py | input-lanjian | 18166.2 ± 695.7 | 17217.0 | 21316.2 | 26.41 ± 6.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|