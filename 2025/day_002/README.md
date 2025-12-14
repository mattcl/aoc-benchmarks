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
| whyando | input-lanjian | 394.8 ± 159.9 | 0.0 | 897.3 | 1.00 |
| whyando | input-whyando | 429.3 ± 180.6 | 0.0 | 1041.1 | 1.09 ± 0.64 |
| whyando | input-mattcl | 437.2 ± 130.3 | 0.0 | 954.1 | 1.11 ± 0.56 |
| lanjian | input-mattcl | 618.8 ± 194.4 | 0.0 | 1189.4 | 1.57 ± 0.80 |
| mattcl | input-lanjian | 646.6 ± 174.7 | 0.0 | 1155.9 | 1.64 ± 0.80 |
| mattcl | input-whyando | 648.8 ± 164.1 | 56.6 | 1126.5 | 1.64 ± 0.79 |
| mattcl | input-mattcl | 651.2 ± 140.8 | 0.0 | 1097.5 | 1.65 ± 0.76 |
| lanjian | input-whyando | 670.8 ± 128.8 | 210.7 | 1098.6 | 1.70 ± 0.76 |
| lanjian | input-lanjian | 671.4 ± 133.1 | 102.1 | 1188.7 | 1.70 ± 0.77 |
| kcen | input-mattcl | 768.0 ± 145.5 | 0.0 | 1277.6 | 1.95 ± 0.87 |
| kcen | input-whyando | 779.4 ± 136.6 | 230.3 | 1256.7 | 1.97 ± 0.87 |
| kcen | input-lanjian | 814.6 ± 174.3 | 253.3 | 1438.0 | 2.06 ± 0.95 |
| mattcl-py | input-whyando | 20407.1 ± 731.0 | 19417.4 | 23942.0 | 51.69 ± 21.03 |
| mattcl-py | input-lanjian | 20622.4 ± 635.4 | 19448.7 | 23744.3 | 52.24 ± 21.23 |
| mattcl-py | input-mattcl | 20796.0 ± 768.6 | 19773.3 | 24064.5 | 52.68 ± 21.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|