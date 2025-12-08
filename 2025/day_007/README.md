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
| whyando | input-mattcl | 367.0 ± 137.6 | 0.0 | 812.3 | 1.00 |
| whyando | input-lanjian | 369.5 ± 180.0 | 0.0 | 1098.3 | 1.01 ± 0.62 |
| mattcl | input-whyando | 395.0 ± 175.5 | 0.0 | 1441.1 | 1.08 ± 0.63 |
| mattcl | input-mattcl | 396.3 ± 184.9 | 0.0 | 975.9 | 1.08 ± 0.65 |
| mattcl | input-lanjian | 400.6 ± 150.0 | 0.0 | 763.2 | 1.09 ± 0.58 |
| whyando | input-whyando | 421.1 ± 133.2 | 0.0 | 957.3 | 1.15 ± 0.56 |
| lanjian | input-mattcl | 700.3 ± 160.1 | 0.0 | 1123.9 | 1.91 ± 0.84 |
| lanjian | input-lanjian | 718.2 ± 147.1 | 14.9 | 1219.0 | 1.96 ± 0.84 |
| lanjian | input-whyando | 744.8 ± 183.9 | 207.5 | 1462.2 | 2.03 ± 0.91 |
| kcen | input-lanjian | 890.5 ± 123.4 | 353.7 | 1361.8 | 2.43 ± 0.97 |
| kcen | input-mattcl | 893.3 ± 169.9 | 0.0 | 1461.4 | 2.43 ± 1.02 |
| kcen | input-whyando | 916.4 ± 172.9 | 0.0 | 1454.5 | 2.50 ± 1.05 |
| mattcl-py | input-lanjian | 17395.1 ± 766.1 | 16013.2 | 20631.3 | 47.40 ± 17.89 |
| mattcl-py | input-whyando | 17460.9 ± 545.8 | 16564.4 | 20439.6 | 47.58 ± 17.90 |
| mattcl-py | input-mattcl | 17478.8 ± 765.8 | 16131.4 | 20943.1 | 47.62 ± 17.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|