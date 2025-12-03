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
| whyando | input-lanjian | 517.0 ± 155.5 | 0.0 | 1141.7 | 1.00 |
| whyando | input-mattcl | 544.8 ± 144.5 | 0.0 | 1012.0 | 1.05 ± 0.42 |
| whyando | input-whyando | 546.7 ± 165.8 | 0.0 | 1228.4 | 1.06 ± 0.45 |
| kcen | input-lanjian | 668.2 ± 263.8 | 0.0 | 1045.7 | 1.29 ± 0.64 |
| kcen | input-whyando | 787.5 ± 127.0 | 53.7 | 1166.5 | 1.52 ± 0.52 |
| kcen | input-mattcl | 813.3 ± 166.3 | 80.2 | 1286.3 | 1.57 ± 0.57 |
| mattcl | input-whyando | 949.2 ± 163.3 | 461.0 | 1547.9 | 1.84 ± 0.64 |
| mattcl | input-lanjian | 949.3 ± 143.0 | 483.1 | 1715.5 | 1.84 ± 0.62 |
| mattcl | input-mattcl | 990.8 ± 166.4 | 340.9 | 1657.5 | 1.92 ± 0.66 |
| lanjian | input-lanjian | 998.9 ± 264.4 | 57.3 | 1403.2 | 1.93 ± 0.77 |
| lanjian | input-whyando | 1028.8 ± 168.9 | 473.3 | 1712.8 | 1.99 ± 0.68 |
| lanjian | input-mattcl | 1080.0 ± 212.1 | 346.7 | 1922.6 | 2.09 ± 0.75 |
| mattcl-py | input-whyando | 20081.6 ± 606.5 | 19111.7 | 23791.8 | 38.84 ± 11.74 |
| mattcl-py | input-lanjian | 20420.5 ± 678.9 | 18963.0 | 23753.1 | 39.50 ± 11.96 |
| mattcl-py | input-mattcl | 20548.8 ± 598.8 | 19624.8 | 23039.5 | 39.75 ± 12.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|