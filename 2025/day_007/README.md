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
| whyando | input-whyando | 404.5 ± 167.8 | 0.0 | 970.6 | 1.00 |
| whyando | input-mattcl | 420.9 ± 141.0 | 0.0 | 956.9 | 1.04 ± 0.55 |
| whyando | input-lanjian | 431.8 ± 126.2 | 0.0 | 835.6 | 1.07 ± 0.54 |
| mattcl | input-whyando | 435.5 ± 169.8 | 0.0 | 961.7 | 1.08 ± 0.61 |
| mattcl | input-mattcl | 447.5 ± 165.1 | 0.0 | 1086.5 | 1.11 ± 0.61 |
| mattcl | input-lanjian | 457.9 ± 169.8 | 0.0 | 1080.2 | 1.13 ± 0.63 |
| lanjian | input-mattcl | 724.1 ± 135.2 | 130.6 | 1140.9 | 1.79 ± 0.81 |
| lanjian | input-whyando | 745.6 ± 187.1 | 0.0 | 1418.5 | 1.84 ± 0.89 |
| lanjian | input-lanjian | 816.9 ± 172.5 | 191.4 | 1442.3 | 2.02 ± 0.94 |
| kcen | input-mattcl | 891.0 ± 158.8 | 315.3 | 1455.3 | 2.20 ± 0.99 |
| kcen | input-whyando | 920.6 ± 154.7 | 190.1 | 1462.9 | 2.28 ± 1.02 |
| kcen | input-lanjian | 961.6 ± 187.6 | 27.7 | 1610.9 | 2.38 ± 1.09 |
| mattcl-py | input-whyando | 17501.6 ± 565.1 | 16476.3 | 20650.5 | 43.27 ± 18.01 |
| mattcl-py | input-lanjian | 17530.9 ± 628.7 | 16099.6 | 20687.5 | 43.34 ± 18.05 |
| mattcl-py | input-mattcl | 17559.7 ± 651.4 | 16472.4 | 20977.5 | 43.42 ± 18.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|