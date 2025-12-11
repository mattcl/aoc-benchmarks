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
| whyando | input-mattcl | 386.4 ± 190.3 | 0.0 | 678.3 | 1.00 |
| whyando | input-lanjian | 396.6 ± 178.7 | 0.0 | 677.2 | 1.03 ± 0.68 |
| mattcl | input-whyando | 398.2 ± 174.7 | 0.0 | 640.2 | 1.03 ± 0.68 |
| whyando | input-whyando | 398.4 ± 166.2 | 0.0 | 712.1 | 1.03 ± 0.67 |
| mattcl | input-lanjian | 441.4 ± 172.4 | 0.0 | 711.2 | 1.14 ± 0.72 |
| mattcl | input-mattcl | 469.7 ± 167.9 | 0.0 | 707.9 | 1.22 ± 0.74 |
| lanjian | input-lanjian | 756.5 ± 181.9 | 174.8 | 1041.1 | 1.96 ± 1.07 |
| lanjian | input-mattcl | 777.0 ± 108.8 | 258.9 | 964.9 | 2.01 ± 1.03 |
| kcen | input-mattcl | 923.5 ± 169.5 | 319.2 | 1236.7 | 2.39 ± 1.26 |
| kcen | input-lanjian | 954.5 ± 181.4 | 0.0 | 1330.9 | 2.47 ± 1.30 |
| kcen | input-whyando | 1236.2 ± 1899.4 | 0.0 | 18358.5 | 3.20 ± 5.16 |
| lanjian | input-whyando | 1418.5 ± 3250.0 | 0.0 | 18424.2 | 3.67 ± 8.60 |
| mattcl-py | input-whyando | 17996.1 ± 412.3 | 16968.4 | 20708.4 | 46.57 ± 22.96 |
| mattcl-py | input-lanjian | 18201.4 ± 541.8 | 17178.7 | 20749.5 | 47.10 ± 23.23 |
| mattcl-py | input-mattcl | 18206.6 ± 449.7 | 17025.0 | 20017.4 | 47.12 ± 23.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|