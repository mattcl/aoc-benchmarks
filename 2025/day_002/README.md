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
| whyando | input-whyando | 305.4 ± 281.7 | 0.0 | 1568.4 | 1.00 |
| whyando | input-mattcl | 532.3 ± 181.7 | 0.0 | 1044.4 | 1.74 ± 1.71 |
| whyando | input-lanjian | 544.6 ± 156.8 | 0.0 | 951.6 | 1.78 ± 1.72 |
| kcen | input-whyando | 761.3 ± 172.4 | 223.5 | 1531.6 | 2.49 ± 2.37 |
| kcen | input-mattcl | 772.5 ± 147.1 | 160.0 | 1206.9 | 2.53 ± 2.38 |
| kcen | input-lanjian | 782.9 ± 144.7 | 0.0 | 1388.5 | 2.56 ± 2.41 |
| mattcl | input-whyando | 837.9 ± 292.6 | 0.0 | 1705.8 | 2.74 ± 2.71 |
| mattcl | input-mattcl | 979.5 ± 131.4 | 436.7 | 1513.9 | 3.21 ± 2.99 |
| mattcl | input-lanjian | 985.0 ± 113.3 | 404.0 | 1622.4 | 3.23 ± 3.00 |
| lanjian | input-mattcl | 1074.2 ± 257.3 | 124.8 | 1903.5 | 3.52 ± 3.35 |
| lanjian | input-whyando | 1164.8 ± 232.4 | 356.9 | 1882.7 | 3.81 ± 3.60 |
| lanjian | input-lanjian | 1166.9 ± 235.6 | 588.2 | 1890.1 | 3.82 ± 3.61 |
| mattcl-py | input-whyando | 20481.5 ± 661.5 | 19474.1 | 23692.6 | 67.06 ± 61.89 |
| mattcl-py | input-mattcl | 20497.1 ± 553.3 | 19220.9 | 23641.2 | 67.11 ± 61.93 |
| mattcl-py | input-lanjian | 20670.1 ± 616.9 | 19596.7 | 23382.8 | 67.68 ± 62.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|