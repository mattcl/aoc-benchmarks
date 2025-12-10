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
| whyando | input-lanjian | 267.1 ± 202.2 | 0.0 | 1061.3 | 1.00 |
| whyando | input-whyando | 404.6 ± 160.5 | 0.0 | 830.2 | 1.51 ± 1.29 |
| whyando | input-mattcl | 409.6 ± 177.4 | 0.0 | 848.2 | 1.53 ± 1.34 |
| lanjian | input-mattcl | 661.7 ± 207.0 | 0.0 | 951.0 | 2.48 ± 2.03 |
| mattcl | input-whyando | 671.8 ± 147.1 | 133.7 | 1266.0 | 2.52 ± 1.98 |
| mattcl | input-mattcl | 677.0 ± 157.2 | 0.0 | 1174.4 | 2.53 ± 2.01 |
| mattcl | input-lanjian | 687.5 ± 139.6 | 0.0 | 1173.5 | 2.57 ± 2.02 |
| lanjian | input-lanjian | 690.8 ± 157.9 | 150.5 | 1139.4 | 2.59 ± 2.05 |
| lanjian | input-whyando | 693.8 ± 160.6 | 0.0 | 1129.1 | 2.60 ± 2.06 |
| kcen | input-mattcl | 785.1 ± 224.8 | 0.0 | 1089.4 | 2.94 ± 2.38 |
| kcen | input-lanjian | 813.4 ± 166.7 | 278.7 | 1523.2 | 3.05 ± 2.39 |
| kcen | input-whyando | 914.7 ± 184.8 | 320.6 | 1462.4 | 3.42 ± 2.68 |
| mattcl-py | input-whyando | 20448.8 ± 550.0 | 19361.9 | 23396.0 | 76.56 ± 58.01 |
| mattcl-py | input-lanjian | 20686.4 ± 638.1 | 19646.7 | 24097.2 | 77.45 ± 58.69 |
| mattcl-py | input-mattcl | 20720.5 ± 523.5 | 19795.6 | 23589.7 | 77.58 ± 58.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|