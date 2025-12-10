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
| whyando | input-lanjian | 340.2 ± 165.1 | 0.0 | 599.5 | 1.00 |
| whyando | input-mattcl | 351.2 ± 167.2 | 0.0 | 947.0 | 1.03 ± 0.70 |
| whyando | input-whyando | 380.2 ± 153.0 | 0.0 | 1009.4 | 1.12 ± 0.70 |
| mattcl | input-mattcl | 389.7 ± 162.0 | 0.0 | 959.9 | 1.15 ± 0.73 |
| mattcl | input-lanjian | 390.7 ± 187.5 | 0.0 | 830.5 | 1.15 ± 0.78 |
| mattcl | input-whyando | 395.7 ± 167.0 | 0.0 | 973.5 | 1.16 ± 0.75 |
| lanjian | input-whyando | 676.7 ± 147.2 | 0.0 | 885.7 | 1.99 ± 1.06 |
| lanjian | input-lanjian | 692.0 ± 155.0 | 0.0 | 1065.6 | 2.03 ± 1.09 |
| lanjian | input-mattcl | 700.0 ± 139.2 | 196.2 | 1099.4 | 2.06 ± 1.08 |
| kcen | input-whyando | 868.9 ± 132.4 | 227.6 | 1356.4 | 2.55 ± 1.30 |
| kcen | input-mattcl | 886.4 ± 167.8 | 0.0 | 1437.0 | 2.61 ± 1.36 |
| kcen | input-lanjian | 916.3 ± 148.3 | 460.2 | 1523.3 | 2.69 ± 1.38 |
| mattcl-py | input-lanjian | 17459.7 ± 660.6 | 16484.7 | 20718.8 | 51.32 ± 24.98 |
| mattcl-py | input-whyando | 17558.6 ± 723.9 | 16378.2 | 20283.0 | 51.61 ± 25.14 |
| mattcl-py | input-mattcl | 17597.4 ± 764.8 | 16346.5 | 20707.5 | 51.73 ± 25.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|