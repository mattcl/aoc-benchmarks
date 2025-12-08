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
| whyando | input-whyando | 487.0 ± 180.1 | 0.0 | 1267.2 | 1.00 |
| whyando | input-lanjian | 519.4 ± 146.4 | 35.4 | 1100.3 | 1.07 ± 0.50 |
| whyando | input-mattcl | 524.2 ± 130.7 | 0.0 | 959.2 | 1.08 ± 0.48 |
| mattcl | input-mattcl | 723.8 ± 144.8 | 139.2 | 1097.0 | 1.49 ± 0.62 |
| mattcl | input-lanjian | 765.5 ± 101.1 | 394.5 | 1118.5 | 1.57 ± 0.62 |
| mattcl | input-whyando | 779.8 ± 164.3 | 166.7 | 1435.6 | 1.60 ± 0.68 |
| kcen | input-whyando | 821.9 ± 147.3 | 0.0 | 1130.3 | 1.69 ± 0.69 |
| kcen | input-mattcl | 848.6 ± 145.1 | 322.5 | 1346.0 | 1.74 ± 0.71 |
| kcen | input-lanjian | 867.6 ± 133.5 | 324.6 | 1348.0 | 1.78 ± 0.71 |
| lanjian | input-whyando | 1107.0 ± 229.5 | 399.7 | 2972.9 | 2.27 ± 0.96 |
| lanjian | input-mattcl | 1149.0 ± 236.9 | 486.1 | 2243.8 | 2.36 ± 1.00 |
| lanjian | input-lanjian | 1188.3 ± 223.5 | 469.8 | 2643.8 | 2.44 ± 1.01 |
| mattcl-py | input-whyando | 18324.1 ± 655.9 | 17477.7 | 21991.1 | 37.62 ± 13.98 |
| mattcl-py | input-mattcl | 18361.0 ± 679.7 | 17356.4 | 21863.8 | 37.70 ± 14.01 |
| mattcl-py | input-lanjian | 18423.3 ± 846.9 | 17207.4 | 22226.1 | 37.83 ± 14.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|