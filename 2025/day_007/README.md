# Day 7 benchmarks

[link to problem](https://adventofcode.com/2025/day/7)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 7)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-mattcl | 334.4 ± 146.7 | 0.0 | 675.7 | 1.00 |
| whyando | input-lanjian | 341.9 ± 172.9 | 0.0 | 1044.9 | 1.02 ± 0.68 |
| whyando | input-whyando | 366.5 ± 163.7 | 0.0 | 1023.9 | 1.10 ± 0.69 |
| mattcl | input-lanjian | 375.9 ± 173.2 | 0.0 | 950.4 | 1.12 ± 0.72 |
| mattcl | input-mattcl | 376.3 ± 179.0 | 0.0 | 1011.0 | 1.13 ± 0.73 |
| mattcl | input-whyando | 411.1 ± 155.7 | 0.0 | 938.2 | 1.23 ± 0.71 |
| lanjian | input-whyando | 674.6 ± 164.0 | 88.1 | 1293.2 | 2.02 ± 1.01 |
| lanjian | input-mattcl | 678.6 ± 151.0 | 0.0 | 1089.9 | 2.03 ± 1.00 |
| lanjian | input-lanjian | 684.2 ± 138.6 | 0.0 | 874.6 | 2.05 ± 0.99 |
| kcen | input-whyando | 825.7 ± 175.5 | 73.4 | 1518.6 | 2.47 ± 1.20 |
| kcen | input-mattcl | 826.8 ± 185.7 | 0.0 | 1324.2 | 2.47 ± 1.22 |
| kcen | input-lanjian | 878.7 ± 134.6 | 291.1 | 1494.3 | 2.63 ± 1.22 |
| mattcl-py | input-lanjian | 17449.3 ± 574.6 | 16463.5 | 20291.0 | 52.18 ± 22.95 |
| mattcl-py | input-whyando | 17468.9 ± 589.6 | 16513.5 | 20833.6 | 52.24 ± 22.98 |
| mattcl-py | input-mattcl | 17516.0 ± 689.2 | 16407.5 | 21086.2 | 52.38 ± 23.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|