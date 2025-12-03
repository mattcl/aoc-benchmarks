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
| whyando | input-lanjian | 444.8 ± 191.6 | 0.0 | 1111.0 | 1.00 |
| whyando | input-whyando | 521.4 ± 168.4 | 0.0 | 1021.2 | 1.17 ± 0.63 |
| whyando | input-mattcl | 530.8 ± 152.2 | 0.0 | 1040.1 | 1.19 ± 0.62 |
| kcen | input-lanjian | 763.4 ± 139.4 | 135.8 | 1263.3 | 1.72 ± 0.80 |
| kcen | input-whyando | 770.9 ± 137.7 | 221.8 | 1322.0 | 1.73 ± 0.81 |
| kcen | input-mattcl | 802.2 ± 114.9 | 411.6 | 1312.6 | 1.80 ± 0.82 |
| mattcl | input-lanjian | 929.3 ± 158.3 | 376.2 | 1535.6 | 2.09 ± 0.97 |
| mattcl | input-mattcl | 932.9 ± 145.3 | 332.2 | 1531.2 | 2.10 ± 0.96 |
| mattcl | input-whyando | 946.8 ± 141.1 | 369.8 | 1542.3 | 2.13 ± 0.97 |
| lanjian | input-mattcl | 1018.8 ± 235.9 | 0.0 | 1862.4 | 2.29 ± 1.12 |
| lanjian | input-lanjian | 1029.5 ± 185.8 | 461.8 | 1717.3 | 2.31 ± 1.08 |
| lanjian | input-whyando | 1097.0 ± 206.2 | 524.5 | 1809.8 | 2.47 ± 1.16 |
| mattcl-py | input-whyando | 20197.5 ± 425.3 | 19356.3 | 22294.1 | 45.41 ± 19.58 |
| mattcl-py | input-lanjian | 20369.2 ± 549.2 | 19366.6 | 23501.0 | 45.79 ± 19.76 |
| mattcl-py | input-mattcl | 20521.5 ± 666.1 | 19041.3 | 23989.5 | 46.14 ± 19.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|