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
| whyando | input-mattcl | 635.6 ± 158.3 | 0.0 | 1042.0 | 1.00 |
| whyando | input-lanjian | 654.9 ± 157.5 | 0.0 | 1144.5 | 1.03 ± 0.36 |
| whyando | input-whyando | 671.8 ± 131.9 | 0.0 | 1227.1 | 1.06 ± 0.34 |
| kcen | input-lanjian | 859.0 ± 169.7 | 0.0 | 1380.1 | 1.35 ± 0.43 |
| kcen | input-mattcl | 878.8 ± 128.2 | 285.7 | 1473.6 | 1.38 ± 0.40 |
| kcen | input-whyando | 886.4 ± 169.3 | 221.3 | 1382.5 | 1.39 ± 0.44 |
| mattcl | input-whyando | 1037.3 ± 195.1 | 15.9 | 1805.5 | 1.63 ± 0.51 |
| mattcl | input-mattcl | 1043.2 ± 147.1 | 336.6 | 1706.6 | 1.64 ± 0.47 |
| mattcl | input-lanjian | 1106.9 ± 193.9 | 461.5 | 1810.9 | 1.74 ± 0.53 |
| lanjian | input-lanjian | 1355.0 ± 232.3 | 510.5 | 1893.2 | 2.13 ± 0.64 |
| lanjian | input-mattcl | 1361.9 ± 204.0 | 606.7 | 2211.4 | 2.14 ± 0.62 |
| lanjian | input-whyando | 1370.1 ± 220.5 | 533.3 | 2233.4 | 2.16 ± 0.64 |
| mattcl-py | input-lanjian | 18285.6 ± 502.7 | 17286.9 | 21259.3 | 28.77 ± 7.21 |
| mattcl-py | input-mattcl | 18302.9 ± 659.1 | 17044.0 | 21351.7 | 28.80 ± 7.25 |
| mattcl-py | input-whyando | 18386.7 ± 704.6 | 17325.7 | 21849.3 | 28.93 ± 7.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|