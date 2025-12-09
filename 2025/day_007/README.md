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
| whyando | input-lanjian | 395.2 ± 163.8 | 0.0 | 1077.2 | 1.00 |
| whyando | input-mattcl | 403.7 ± 160.3 | 0.0 | 1025.6 | 1.02 ± 0.59 |
| mattcl | input-lanjian | 416.4 ± 194.9 | 0.0 | 983.7 | 1.05 ± 0.66 |
| mattcl | input-mattcl | 446.0 ± 162.6 | 0.0 | 998.5 | 1.13 ± 0.62 |
| mattcl | input-whyando | 446.9 ± 160.8 | 0.0 | 929.7 | 1.13 ± 0.62 |
| whyando | input-whyando | 447.4 ± 170.6 | 0.0 | 1062.8 | 1.13 ± 0.64 |
| lanjian | input-lanjian | 709.1 ± 158.7 | 0.0 | 1076.0 | 1.79 ± 0.85 |
| lanjian | input-mattcl | 735.3 ± 144.6 | 55.4 | 1179.2 | 1.86 ± 0.85 |
| lanjian | input-whyando | 759.5 ± 168.7 | 0.0 | 1351.8 | 1.92 ± 0.90 |
| kcen | input-whyando | 907.8 ± 174.3 | 0.0 | 1673.6 | 2.30 ± 1.05 |
| kcen | input-mattcl | 920.5 ± 140.1 | 246.9 | 1375.4 | 2.33 ± 1.03 |
| kcen | input-lanjian | 953.3 ± 189.0 | 428.1 | 1596.4 | 2.41 ± 1.11 |
| mattcl-py | input-whyando | 17503.6 ± 506.8 | 16350.2 | 20149.8 | 44.29 ± 18.40 |
| mattcl-py | input-lanjian | 17537.4 ± 543.3 | 16665.6 | 19956.6 | 44.37 ± 18.44 |
| mattcl-py | input-mattcl | 17552.5 ± 558.8 | 16158.9 | 20389.0 | 44.41 ± 18.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|