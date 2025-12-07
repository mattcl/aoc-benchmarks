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
| whyando | input-lanjian | 265.2 ± 34.7 | 181.0 | 377.2 | 1.00 |
| mattcl | input-mattcl | 285.9 ± 35.1 | 213.4 | 419.7 | 1.08 ± 0.19 |
| mattcl | input-lanjian | 300.0 ± 107.7 | 116.0 | 677.4 | 1.13 ± 0.43 |
| kcen | input-lanjian | 609.8 ± 115.6 | 411.3 | 1004.0 | 2.30 ± 0.53 |
| kcen | input-mattcl | 613.8 ± 79.1 | 514.5 | 1565.5 | 2.31 ± 0.42 |
| whyando | input-whyando | 650.6 ± 237.9 | 2.5 | 1023.2 | 2.45 ± 0.95 |
| whyando | input-mattcl | 715.9 ± 179.6 | 164.1 | 1074.0 | 2.70 ± 0.76 |
| mattcl | input-whyando | 733.9 ± 198.8 | 43.5 | 1019.6 | 2.77 ± 0.83 |
| lanjian | input-lanjian | 988.9 ± 152.9 | 646.9 | 1646.0 | 3.73 ± 0.75 |
| lanjian | input-mattcl | 1006.4 ± 118.1 | 801.3 | 2225.9 | 3.79 ± 0.67 |
| kcen | input-whyando | 1292.3 ± 195.8 | 379.4 | 1548.0 | 4.87 ± 0.97 |
| lanjian | input-whyando | 1753.8 ± 153.9 | 1049.8 | 2154.5 | 6.61 ± 1.04 |
| mattcl-py | input-whyando | 18425.5 ± 394.8 | 17495.0 | 21413.7 | 69.48 ± 9.20 |
| mattcl-py | input-mattcl | 22426.2 ± 3522.8 | 17254.4 | 27890.4 | 84.56 ± 17.28 |
| mattcl-py | input-lanjian | 23647.1 ± 637.8 | 22270.8 | 26239.7 | 89.17 ± 11.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|