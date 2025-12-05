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
| whyando | input-lanjian | 617.8 ± 206.6 | 0.0 | 1215.6 | 1.00 |
| whyando | input-mattcl | 619.6 ± 156.0 | 0.0 | 1170.2 | 1.00 ± 0.42 |
| whyando | input-whyando | 621.3 ± 148.8 | 0.0 | 1139.4 | 1.01 ± 0.41 |
| kcen | input-lanjian | 644.4 ± 310.4 | 0.0 | 1277.3 | 1.04 ± 0.61 |
| kcen | input-mattcl | 814.9 ± 163.0 | 0.0 | 1559.1 | 1.32 ± 0.51 |
| kcen | input-whyando | 818.2 ± 149.5 | 0.0 | 1311.4 | 1.32 ± 0.50 |
| mattcl | input-mattcl | 992.8 ± 192.9 | 0.0 | 1741.0 | 1.61 ± 0.62 |
| mattcl | input-whyando | 1021.3 ± 173.2 | 319.7 | 1730.6 | 1.65 ± 0.62 |
| mattcl | input-lanjian | 1072.7 ± 191.4 | 496.6 | 1868.0 | 1.74 ± 0.66 |
| lanjian | input-whyando | 1313.9 ± 210.3 | 196.0 | 2059.9 | 2.13 ± 0.79 |
| lanjian | input-lanjian | 1322.3 ± 219.9 | 269.0 | 2067.0 | 2.14 ± 0.80 |
| lanjian | input-mattcl | 1351.1 ± 191.6 | 646.2 | 2121.8 | 2.19 ± 0.79 |
| mattcl-py | input-mattcl | 18248.4 ± 684.4 | 17112.4 | 21263.3 | 29.54 ± 9.94 |
| mattcl-py | input-whyando | 18286.8 ± 726.8 | 17341.0 | 21391.5 | 29.60 ± 9.97 |
| mattcl-py | input-lanjian | 18297.4 ± 636.4 | 17023.0 | 21829.2 | 29.62 ± 9.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|