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
| whyando | input-mattcl | 534.2 ± 158.5 | 0.0 | 1067.0 | 1.00 |
| whyando | input-whyando | 559.3 ± 162.6 | 0.0 | 1180.4 | 1.05 ± 0.43 |
| whyando | input-lanjian | 560.0 ± 225.7 | 0.0 | 2817.3 | 1.05 ± 0.52 |
| kcen | input-lanjian | 797.6 ± 146.0 | 23.1 | 1307.8 | 1.49 ± 0.52 |
| kcen | input-whyando | 841.2 ± 120.8 | 373.8 | 1275.7 | 1.57 ± 0.52 |
| kcen | input-mattcl | 858.3 ± 150.6 | 458.2 | 1475.1 | 1.61 ± 0.55 |
| mattcl | input-lanjian | 978.8 ± 146.9 | 389.7 | 1578.2 | 1.83 ± 0.61 |
| mattcl | input-whyando | 986.8 ± 177.9 | 283.2 | 1632.9 | 1.85 ± 0.64 |
| mattcl | input-mattcl | 994.0 ± 161.4 | 358.6 | 1658.7 | 1.86 ± 0.63 |
| lanjian | input-mattcl | 1058.0 ± 210.3 | 71.5 | 1856.6 | 1.98 ± 0.71 |
| lanjian | input-whyando | 1085.8 ± 212.1 | 523.4 | 2516.0 | 2.03 ± 0.72 |
| lanjian | input-lanjian | 1110.2 ± 189.5 | 135.7 | 1831.7 | 2.08 ± 0.71 |
| mattcl-py | input-whyando | 20260.5 ± 644.0 | 19361.1 | 23141.5 | 37.92 ± 11.32 |
| mattcl-py | input-lanjian | 20501.1 ± 719.2 | 19097.8 | 24020.5 | 38.37 ± 11.47 |
| mattcl-py | input-mattcl | 20563.6 ± 786.9 | 19088.4 | 23799.2 | 38.49 ± 11.52 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|