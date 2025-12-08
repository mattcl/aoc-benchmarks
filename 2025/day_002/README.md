# Day 2 benchmarks

[link to problem](https://adventofcode.com/2025/day/2)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 2)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 390.6 ± 162.0 | 0.0 | 929.3 | 1.00 |
| whyando | input-whyando | 395.3 ± 158.1 | 0.0 | 860.3 | 1.01 ± 0.58 |
| whyando | input-mattcl | 430.7 ± 144.4 | 0.0 | 1020.9 | 1.10 ± 0.59 |
| mattcl | input-mattcl | 728.0 ± 172.4 | 135.0 | 1304.2 | 1.86 ± 0.89 |
| mattcl | input-lanjian | 754.3 ± 220.0 | 175.2 | 2570.8 | 1.93 ± 0.98 |
| mattcl | input-whyando | 776.9 ± 196.5 | 118.5 | 1505.3 | 1.99 ± 0.97 |
| kcen | input-lanjian | 806.3 ± 133.1 | 49.1 | 1241.2 | 2.06 ± 0.92 |
| lanjian | input-whyando | 825.2 ± 158.6 | 185.0 | 1284.9 | 2.11 ± 0.97 |
| kcen | input-mattcl | 830.0 ± 145.6 | 179.6 | 1281.7 | 2.12 ± 0.96 |
| lanjian | input-mattcl | 837.9 ± 147.7 | 0.0 | 1267.1 | 2.14 ± 0.97 |
| kcen | input-whyando | 844.3 ± 196.4 | 209.3 | 1522.9 | 2.16 ± 1.03 |
| lanjian | input-lanjian | 891.0 ± 180.9 | 211.5 | 1556.8 | 2.28 ± 1.05 |
| mattcl-py | input-whyando | 20598.4 ± 780.3 | 19494.2 | 24117.0 | 52.73 ± 21.96 |
| mattcl-py | input-lanjian | 20661.5 ± 625.3 | 19248.8 | 24031.6 | 52.89 ± 21.99 |
| mattcl-py | input-mattcl | 20725.6 ± 548.5 | 19569.6 | 24328.9 | 53.06 ± 22.05 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|