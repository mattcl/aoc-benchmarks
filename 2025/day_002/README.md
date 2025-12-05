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
| whyando | input-mattcl | 127.7 ± 211.5 | 0.0 | 1530.6 | 1.00 |
| kcen | input-whyando | 499.5 ± 295.8 | 0.0 | 1094.4 | 3.91 ± 6.88 |
| whyando | input-lanjian | 528.4 ± 187.2 | 0.0 | 1258.2 | 4.14 ± 7.01 |
| whyando | input-whyando | 560.3 ± 172.6 | 0.0 | 1123.7 | 4.39 ± 7.39 |
| mattcl | input-whyando | 574.6 ± 418.1 | 0.0 | 1567.7 | 4.50 ± 8.14 |
| kcen | input-lanjian | 797.8 ± 149.8 | 0.0 | 1432.0 | 6.25 ± 10.42 |
| kcen | input-mattcl | 856.2 ± 186.5 | 0.0 | 1484.9 | 6.71 ± 11.20 |
| mattcl | input-lanjian | 985.7 ± 163.1 | 443.3 | 1776.4 | 7.72 ± 12.85 |
| mattcl | input-mattcl | 1043.1 ± 182.5 | 355.4 | 1654.7 | 8.17 ± 13.61 |
| lanjian | input-whyando | 1080.8 ± 316.5 | 81.4 | 2039.2 | 8.46 ± 14.24 |
| lanjian | input-lanjian | 1108.4 ± 174.2 | 569.0 | 1838.5 | 8.68 ± 14.44 |
| lanjian | input-mattcl | 1108.6 ± 174.4 | 420.9 | 2046.1 | 8.68 ± 14.45 |
| mattcl-py | input-whyando | 20468.9 ± 683.3 | 19136.8 | 23298.2 | 160.31 ± 265.62 |
| mattcl-py | input-lanjian | 20532.8 ± 603.6 | 19637.2 | 23816.1 | 160.81 ± 266.43 |
| mattcl-py | input-mattcl | 20792.9 ± 738.6 | 19533.7 | 24305.5 | 162.84 ± 269.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|