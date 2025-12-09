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
| whyando | input-whyando | 323.2 ± 124.5 | 0.0 | 615.1 | 1.00 |
| whyando | input-mattcl | 341.5 ± 155.3 | 0.0 | 574.5 | 1.06 ± 0.63 |
| whyando | input-lanjian | 379.6 ± 158.1 | 0.0 | 939.7 | 1.17 ± 0.67 |
| mattcl | input-mattcl | 421.9 ± 161.9 | 0.0 | 1027.2 | 1.31 ± 0.71 |
| mattcl | input-whyando | 427.4 ± 146.7 | 0.0 | 948.5 | 1.32 ± 0.68 |
| mattcl | input-lanjian | 432.5 ± 157.8 | 0.0 | 1012.6 | 1.34 ± 0.71 |
| lanjian | input-mattcl | 694.6 ± 178.6 | 0.0 | 1370.8 | 2.15 ± 0.99 |
| lanjian | input-lanjian | 712.4 ± 129.9 | 194.1 | 1095.0 | 2.20 ± 0.94 |
| lanjian | input-whyando | 713.6 ± 157.9 | 0.0 | 1163.8 | 2.21 ± 0.98 |
| kcen | input-whyando | 865.7 ± 196.3 | 0.0 | 1406.6 | 2.68 ± 1.20 |
| kcen | input-mattcl | 868.4 ± 139.7 | 303.9 | 1332.7 | 2.69 ± 1.12 |
| kcen | input-lanjian | 890.1 ± 141.3 | 0.0 | 1408.0 | 2.75 ± 1.15 |
| mattcl-py | input-lanjian | 17377.3 ± 654.9 | 16382.0 | 20456.3 | 53.76 ± 20.80 |
| mattcl-py | input-mattcl | 17377.6 ± 620.0 | 16334.3 | 20547.7 | 53.76 ± 20.79 |
| mattcl-py | input-whyando | 17488.5 ± 542.7 | 16168.8 | 20110.2 | 54.10 ± 20.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|