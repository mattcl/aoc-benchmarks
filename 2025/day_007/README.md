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
| whyando | input-whyando | 380.9 ± 166.5 | 0.0 | 942.7 | 1.00 |
| whyando | input-mattcl | 409.8 ± 175.1 | 0.0 | 1136.7 | 1.08 ± 0.66 |
| mattcl | input-lanjian | 419.8 ± 183.5 | 0.0 | 1036.1 | 1.10 ± 0.68 |
| mattcl | input-mattcl | 435.4 ± 197.6 | 0.0 | 974.1 | 1.14 ± 0.72 |
| mattcl | input-whyando | 437.6 ± 184.9 | 0.0 | 1020.2 | 1.15 ± 0.70 |
| whyando | input-lanjian | 445.2 ± 135.5 | 0.0 | 966.6 | 1.17 ± 0.62 |
| lanjian | input-lanjian | 725.5 ± 132.5 | 245.3 | 1055.9 | 1.90 ± 0.90 |
| lanjian | input-whyando | 731.2 ± 129.3 | 184.9 | 1165.1 | 1.92 ± 0.91 |
| lanjian | input-mattcl | 746.1 ± 151.0 | 227.4 | 1390.3 | 1.96 ± 0.94 |
| kcen | input-whyando | 914.3 ± 173.2 | 0.0 | 1481.5 | 2.40 ± 1.14 |
| kcen | input-lanjian | 916.8 ± 171.8 | 301.1 | 1511.2 | 2.41 ± 1.15 |
| kcen | input-mattcl | 941.4 ± 153.9 | 458.9 | 1846.7 | 2.47 ± 1.15 |
| mattcl-py | input-lanjian | 17520.8 ± 595.4 | 16656.8 | 20781.6 | 46.00 ± 20.17 |
| mattcl-py | input-mattcl | 17707.9 ± 680.9 | 16692.0 | 21436.7 | 46.49 ± 20.41 |
| mattcl-py | input-whyando | 17777.1 ± 642.5 | 16411.0 | 20917.7 | 46.68 ± 20.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|