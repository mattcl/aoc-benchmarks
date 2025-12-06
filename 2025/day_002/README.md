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
| mattcl | input-lanjian | 603.4 ± 161.8 | 67.1 | 1025.0 | 1.00 |
| mattcl | input-whyando | 603.9 ± 159.1 | 0.0 | 1019.8 | 1.00 ± 0.38 |
| mattcl | input-mattcl | 634.9 ± 155.6 | 39.7 | 1202.9 | 1.05 ± 0.38 |
| kcen | input-whyando | 779.0 ± 171.1 | 88.5 | 1236.4 | 1.29 ± 0.45 |
| kcen | input-lanjian | 797.2 ± 142.9 | 0.0 | 1357.3 | 1.32 ± 0.43 |
| kcen | input-mattcl | 813.6 ± 148.0 | 233.8 | 1418.7 | 1.35 ± 0.44 |
| whyando | input-mattcl | 893.2 ± 160.5 | 401.7 | 1681.5 | 1.48 ± 0.48 |
| whyando | input-whyando | 906.0 ± 169.6 | 449.3 | 1534.4 | 1.50 ± 0.49 |
| whyando | input-lanjian | 941.4 ± 176.6 | 412.5 | 1589.0 | 1.56 ± 0.51 |
| lanjian | input-mattcl | 1160.6 ± 233.8 | 531.7 | 1893.5 | 1.92 ± 0.65 |
| lanjian | input-whyando | 1181.2 ± 233.9 | 659.0 | 2997.2 | 1.96 ± 0.65 |
| lanjian | input-lanjian | 1187.2 ± 176.7 | 461.3 | 1851.2 | 1.97 ± 0.60 |
| mattcl-py | input-whyando | 20331.1 ± 593.8 | 18951.6 | 23551.0 | 33.69 ± 9.09 |
| mattcl-py | input-mattcl | 20601.1 ± 679.0 | 19116.6 | 23464.3 | 34.14 ± 9.23 |
| mattcl-py | input-lanjian | 20714.4 ± 687.8 | 19658.2 | 23814.8 | 34.33 ± 9.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|