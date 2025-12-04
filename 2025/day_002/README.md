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
| whyando | input-lanjian | 322.6 ± 233.2 | 0.0 | 1079.5 | 1.00 |
| whyando | input-whyando | 544.1 ± 164.6 | 0.0 | 1001.7 | 1.69 ± 1.32 |
| whyando | input-mattcl | 568.5 ± 165.4 | 0.0 | 1285.4 | 1.76 ± 1.37 |
| mattcl | input-mattcl | 709.1 ± 367.0 | 0.0 | 1736.6 | 2.20 ± 1.95 |
| kcen | input-mattcl | 738.0 ± 245.2 | 0.0 | 1579.4 | 2.29 ± 1.82 |
| lanjian | input-mattcl | 825.1 ± 402.9 | 0.0 | 1782.0 | 2.56 ± 2.23 |
| kcen | input-whyando | 832.7 ± 167.0 | 0.0 | 1574.5 | 2.58 ± 1.94 |
| kcen | input-lanjian | 875.0 ± 167.4 | 327.0 | 1861.4 | 2.71 ± 2.03 |
| mattcl | input-lanjian | 1000.0 ± 133.4 | 565.1 | 1551.7 | 3.10 ± 2.28 |
| mattcl | input-whyando | 1001.0 ± 140.6 | 488.7 | 1705.2 | 3.10 ± 2.29 |
| lanjian | input-lanjian | 1121.2 ± 184.3 | 497.5 | 1814.4 | 3.48 ± 2.58 |
| lanjian | input-whyando | 1192.4 ± 233.2 | 318.0 | 2038.5 | 3.70 ± 2.77 |
| mattcl-py | input-whyando | 20516.2 ± 705.3 | 19183.1 | 23785.2 | 63.60 ± 46.03 |
| mattcl-py | input-mattcl | 20696.6 ± 579.0 | 19706.2 | 23979.9 | 64.16 ± 46.42 |
| mattcl-py | input-lanjian | 20791.3 ± 965.0 | 19568.5 | 28569.7 | 64.45 ± 46.69 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|