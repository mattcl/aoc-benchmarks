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
| whyando | input-whyando | 332.0 ± 365.0 | 0.0 | 3089.1 | 1.00 |
| whyando | input-lanjian | 559.3 ± 293.5 | 0.0 | 950.5 | 1.68 ± 2.05 |
| mattcl | input-mattcl | 633.4 ± 358.9 | 31.7 | 1538.0 | 1.91 ± 2.36 |
| whyando | input-mattcl | 677.8 ± 279.1 | 0.0 | 1363.4 | 2.04 ± 2.40 |
| kcen | input-whyando | 809.9 ± 227.3 | 0.0 | 1112.8 | 2.44 ± 2.77 |
| kcen | input-mattcl | 824.0 ± 196.0 | 0.0 | 1314.2 | 2.48 ± 2.79 |
| kcen | input-lanjian | 908.5 ± 180.5 | 330.8 | 1546.9 | 2.74 ± 3.06 |
| mattcl | input-lanjian | 1199.9 ± 205.0 | 620.8 | 2029.9 | 3.61 ± 4.02 |
| mattcl | input-whyando | 1240.0 ± 221.3 | 668.4 | 2047.5 | 3.73 ± 4.16 |
| lanjian | input-mattcl | 1269.7 ± 233.1 | 645.1 | 2088.0 | 3.82 ± 4.26 |
| lanjian | input-whyando | 1319.2 ± 269.4 | 190.2 | 2590.0 | 3.97 ± 4.44 |
| lanjian | input-lanjian | 1321.4 ± 212.6 | 574.1 | 2085.1 | 3.98 ± 4.42 |
| mattcl-py | input-lanjian | 18168.2 ± 515.7 | 17244.1 | 20645.2 | 54.72 ± 60.18 |
| mattcl-py | input-mattcl | 18251.3 ± 645.0 | 17173.4 | 21310.2 | 54.97 ± 60.46 |
| mattcl-py | input-whyando | 18311.3 ± 685.2 | 17331.5 | 21063.7 | 55.15 ± 60.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|