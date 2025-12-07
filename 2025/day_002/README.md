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
| whyando | input-lanjian | 391.2 ± 166.0 | 0.0 | 902.5 | 1.00 |
| whyando | input-whyando | 413.2 ± 151.7 | 0.0 | 864.5 | 1.06 ± 0.59 |
| whyando | input-mattcl | 420.9 ± 141.3 | 0.0 | 686.4 | 1.08 ± 0.58 |
| mattcl | input-lanjian | 440.7 ± 260.5 | 0.0 | 812.2 | 1.13 ± 0.82 |
| mattcl | input-whyando | 640.9 ± 145.7 | 170.4 | 1148.9 | 1.64 ± 0.79 |
| mattcl | input-mattcl | 671.2 ± 147.5 | 168.5 | 1323.9 | 1.72 ± 0.82 |
| kcen | input-whyando | 801.7 ± 129.7 | 356.0 | 1233.9 | 2.05 ± 0.93 |
| lanjian | input-whyando | 818.8 ± 179.2 | 86.3 | 1336.9 | 2.09 ± 1.00 |
| kcen | input-mattcl | 818.9 ± 159.0 | 0.0 | 1523.5 | 2.09 ± 0.98 |
| kcen | input-lanjian | 834.6 ± 124.8 | 296.3 | 1283.5 | 2.13 ± 0.96 |
| lanjian | input-mattcl | 856.7 ± 168.8 | 0.0 | 1500.9 | 2.19 ± 1.02 |
| lanjian | input-lanjian | 857.0 ± 141.2 | 427.8 | 1371.4 | 2.19 ± 1.00 |
| mattcl-py | input-whyando | 20454.8 ± 675.0 | 19085.1 | 23735.4 | 52.28 ± 22.26 |
| mattcl-py | input-mattcl | 20699.1 ± 640.3 | 19560.3 | 22896.1 | 52.91 ± 22.51 |
| mattcl-py | input-lanjian | 20797.3 ± 598.6 | 19512.9 | 23715.5 | 53.16 ± 22.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|