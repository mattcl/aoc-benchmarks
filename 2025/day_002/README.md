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
| whyando | input-mattcl | 551.2 ± 164.9 | 0.0 | 1104.2 | 1.00 |
| whyando | input-whyando | 564.1 ± 157.8 | 0.0 | 1067.4 | 1.02 ± 0.42 |
| whyando | input-lanjian | 572.0 ± 134.1 | 1.3 | 1041.0 | 1.04 ± 0.39 |
| kcen | input-whyando | 801.8 ± 155.8 | 0.0 | 1337.9 | 1.45 ± 0.52 |
| kcen | input-mattcl | 844.1 ± 167.1 | 362.2 | 1368.6 | 1.53 ± 0.55 |
| kcen | input-lanjian | 849.0 ± 212.4 | 275.0 | 2045.5 | 1.54 ± 0.60 |
| mattcl | input-lanjian | 935.4 ± 220.3 | 0.0 | 1580.2 | 1.70 ± 0.65 |
| mattcl | input-whyando | 997.2 ± 158.5 | 367.3 | 1637.9 | 1.81 ± 0.61 |
| mattcl | input-mattcl | 1013.1 ± 135.9 | 451.7 | 1604.4 | 1.84 ± 0.60 |
| lanjian | input-mattcl | 1131.1 ± 192.0 | 470.1 | 1824.8 | 2.05 ± 0.71 |
| lanjian | input-lanjian | 1144.3 ± 201.9 | 121.5 | 1776.3 | 2.08 ± 0.72 |
| lanjian | input-whyando | 1145.4 ± 206.3 | 646.6 | 1888.5 | 2.08 ± 0.73 |
| mattcl-py | input-whyando | 20399.5 ± 566.9 | 19257.2 | 23342.2 | 37.01 ± 11.12 |
| mattcl-py | input-mattcl | 20625.7 ± 615.0 | 19027.5 | 23644.7 | 37.42 ± 11.25 |
| mattcl-py | input-lanjian | 20841.1 ± 712.7 | 19607.7 | 23763.1 | 37.81 ± 11.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|