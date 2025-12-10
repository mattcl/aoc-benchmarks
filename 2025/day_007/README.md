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
| whyando | input-whyando | 353.6 ± 157.1 | 0.0 | 662.6 | 1.00 |
| whyando | input-lanjian | 358.9 ± 166.7 | 0.0 | 987.6 | 1.01 ± 0.65 |
| whyando | input-mattcl | 379.3 ± 171.9 | 0.0 | 945.7 | 1.07 ± 0.68 |
| mattcl | input-mattcl | 383.2 ± 195.5 | 0.0 | 1088.8 | 1.08 ± 0.73 |
| mattcl | input-whyando | 392.0 ± 186.4 | 0.0 | 993.1 | 1.11 ± 0.72 |
| mattcl | input-lanjian | 412.3 ± 171.5 | 0.0 | 880.2 | 1.17 ± 0.71 |
| lanjian | input-lanjian | 689.3 ± 175.0 | 0.0 | 1084.2 | 1.95 ± 1.00 |
| lanjian | input-mattcl | 691.6 ± 166.0 | 0.0 | 1136.9 | 1.96 ± 0.99 |
| lanjian | input-whyando | 699.9 ± 135.9 | 231.4 | 1200.6 | 1.98 ± 0.96 |
| kcen | input-mattcl | 863.3 ± 155.7 | 3.3 | 1354.6 | 2.44 ± 1.17 |
| kcen | input-whyando | 887.8 ± 190.6 | 0.0 | 1422.2 | 2.51 ± 1.24 |
| kcen | input-lanjian | 892.1 ± 149.2 | 476.1 | 1687.0 | 2.52 ± 1.20 |
| mattcl-py | input-mattcl | 17496.0 ± 519.7 | 16426.3 | 20265.2 | 49.48 ± 22.03 |
| mattcl-py | input-whyando | 17575.2 ± 720.6 | 16226.1 | 20644.5 | 49.70 ± 22.18 |
| mattcl-py | input-lanjian | 17589.9 ± 646.1 | 16532.1 | 20348.1 | 49.74 ± 22.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|