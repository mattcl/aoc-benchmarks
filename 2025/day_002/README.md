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
| whyando | input-whyando | 582.4 ± 182.7 | 0.0 | 1203.1 | 1.00 |
| whyando | input-lanjian | 603.5 ± 172.3 | 76.1 | 833.7 | 1.04 ± 0.44 |
| whyando | input-mattcl | 608.9 ± 155.5 | 0.0 | 1092.0 | 1.05 ± 0.42 |
| kcen | input-whyando | 879.0 ± 120.2 | 322.4 | 1382.5 | 1.51 ± 0.52 |
| kcen | input-lanjian | 880.3 ± 164.6 | 300.0 | 1110.8 | 1.51 ± 0.55 |
| kcen | input-mattcl | 905.5 ± 131.4 | 324.0 | 1066.8 | 1.55 ± 0.54 |
| mattcl | input-mattcl | 991.5 ± 290.7 | 9.2 | 1721.9 | 1.70 ± 0.73 |
| mattcl | input-lanjian | 1085.7 ± 171.1 | 65.5 | 1568.3 | 1.86 ± 0.65 |
| mattcl | input-whyando | 1088.2 ± 174.9 | 338.5 | 1717.6 | 1.87 ± 0.66 |
| lanjian | input-lanjian | 1161.0 ± 207.8 | 461.5 | 1432.1 | 1.99 ± 0.72 |
| lanjian | input-whyando | 1161.9 ± 188.3 | 649.0 | 1887.0 | 1.99 ± 0.70 |
| lanjian | input-mattcl | 1164.0 ± 185.3 | 518.2 | 1458.9 | 2.00 ± 0.70 |
| mattcl-py | input-whyando | 20527.7 ± 521.3 | 19526.8 | 22891.3 | 35.25 ± 11.10 |
| mattcl-py | input-mattcl | 21141.1 ± 625.9 | 19633.2 | 22841.7 | 36.30 ± 11.44 |
| mattcl-py | input-lanjian | 22941.5 ± 3324.6 | 20038.0 | 33334.1 | 39.39 ± 13.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|