# Day 1 benchmarks

[link to problem](https://adventofcode.com/2025/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| kcen | input-mattcl | 878.1 ± 151.9 | 0.0 | 1364.3 | 1.00 |
| kcen | input-whyando | 905.1 ± 133.5 | 395.8 | 1494.1 | 1.03 ± 0.23 |
| kcen | input-lanjian | 934.4 ± 213.5 | 0.0 | 1606.6 | 1.06 ± 0.31 |
| whyando | input-whyando | 1039.8 ± 186.3 | 441.6 | 1873.7 | 1.18 ± 0.29 |
| whyando | input-mattcl | 1046.8 ± 187.7 | 375.8 | 1588.0 | 1.19 ± 0.30 |
| whyando | input-lanjian | 1069.0 ± 171.0 | 469.5 | 1858.2 | 1.22 ± 0.29 |
| mattcl | input-mattcl | 1071.4 ± 187.8 | 305.4 | 1947.5 | 1.22 ± 0.30 |
| mattcl | input-lanjian | 1081.0 ± 195.3 | 528.5 | 1774.3 | 1.23 ± 0.31 |
| mattcl | input-whyando | 1092.8 ± 168.3 | 521.4 | 1912.2 | 1.24 ± 0.29 |
| lanjian | input-whyando | 1353.7 ± 228.0 | 295.2 | 1923.6 | 1.54 ± 0.37 |
| lanjian | input-lanjian | 1395.0 ± 212.8 | 571.4 | 1969.5 | 1.59 ± 0.37 |
| lanjian | input-mattcl | 1417.3 ± 153.2 | 780.8 | 2198.9 | 1.61 ± 0.33 |
| mattcl-py | input-whyando | 18271.8 ± 560.0 | 17340.4 | 21169.8 | 20.81 ± 3.66 |
| mattcl-py | input-mattcl | 18329.6 ± 788.0 | 17144.4 | 21816.4 | 20.87 ± 3.72 |
| mattcl-py | input-lanjian | 18364.7 ± 697.3 | 17027.9 | 21437.7 | 20.91 ± 3.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|