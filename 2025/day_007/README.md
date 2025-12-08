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
| whyando | input-whyando | 366.5 ± 158.7 | 0.0 | 913.5 | 1.00 |
| whyando | input-mattcl | 378.2 ± 162.7 | 0.0 | 998.5 | 1.03 ± 0.63 |
| mattcl | input-lanjian | 379.3 ± 176.3 | 0.0 | 827.1 | 1.03 ± 0.66 |
| whyando | input-lanjian | 403.7 ± 154.3 | 0.0 | 985.0 | 1.10 ± 0.64 |
| mattcl | input-mattcl | 427.6 ± 152.8 | 0.0 | 914.2 | 1.17 ± 0.65 |
| mattcl | input-whyando | 433.5 ± 181.8 | 0.0 | 1002.9 | 1.18 ± 0.71 |
| lanjian | input-mattcl | 708.7 ± 146.0 | 160.3 | 1179.0 | 1.93 ± 0.93 |
| lanjian | input-whyando | 710.9 ± 137.3 | 196.6 | 1111.8 | 1.94 ± 0.92 |
| lanjian | input-lanjian | 746.9 ± 160.6 | 0.0 | 1221.5 | 2.04 ± 0.99 |
| kcen | input-lanjian | 873.1 ± 158.6 | 343.4 | 1428.1 | 2.38 ± 1.12 |
| kcen | input-mattcl | 883.0 ± 146.8 | 281.3 | 1418.5 | 2.41 ± 1.12 |
| kcen | input-whyando | 952.6 ± 154.2 | 441.3 | 1536.3 | 2.60 ± 1.20 |
| mattcl-py | input-lanjian | 17266.4 ± 706.2 | 16244.4 | 20946.9 | 47.11 ± 20.49 |
| mattcl-py | input-mattcl | 17353.8 ± 591.0 | 16406.8 | 20507.2 | 47.34 ± 20.57 |
| mattcl-py | input-whyando | 17460.4 ± 626.8 | 16370.1 | 20467.5 | 47.64 ± 20.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|