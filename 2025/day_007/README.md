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
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-mattcl | 380.9 ± 185.8 | 0.0 | 914.0 | 1.00 |
| mattcl | input-whyando | 387.9 ± 194.4 | 0.0 | 941.3 | 1.02 ± 0.71 |
| whyando | input-lanjian | 397.9 ± 169.3 | 0.0 | 917.0 | 1.04 ± 0.68 |
| whyando | input-whyando | 415.4 ± 168.0 | 0.0 | 993.9 | 1.09 ± 0.69 |
| mattcl | input-mattcl | 433.3 ± 180.8 | 0.0 | 1020.7 | 1.14 ± 0.73 |
| mattcl | input-lanjian | 448.5 ± 157.3 | 0.0 | 1100.8 | 1.18 ± 0.71 |
| kcen | input-mattcl | 923.3 ± 153.9 | 308.0 | 1467.1 | 2.42 ± 1.25 |
| kcen | input-whyando | 958.7 ± 226.3 | 0.0 | 1598.9 | 2.52 ± 1.36 |
| kcen | input-lanjian | 982.2 ± 133.5 | 563.3 | 1487.1 | 2.58 ± 1.31 |
| mattcl-py | input-whyando | 17348.8 ± 567.0 | 16166.3 | 20165.7 | 45.54 ± 22.26 |
| mattcl-py | input-lanjian | 17372.0 ± 626.6 | 16467.0 | 20781.7 | 45.60 ± 22.30 |
| mattcl-py | input-mattcl | 17498.8 ± 790.7 | 16372.1 | 20959.5 | 45.94 ± 22.50 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|