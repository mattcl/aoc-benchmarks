# Day 1 benchmarks

[link to problem](https://adventofcode.com/2025/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-whyando | 438.4 ± 221.7 | 0.0 | 855.2 | 1.00 |
| whyando | input-mattcl | 456.1 ± 204.3 | 0.0 | 759.3 | 1.04 ± 0.70 |
| mattcl | input-whyando | 490.8 ± 207.5 | 0.0 | 788.4 | 1.12 ± 0.74 |
| mattcl | input-mattcl | 495.3 ± 195.9 | 0.0 | 801.4 | 1.13 ± 0.73 |
| mattcl | input-lanjian | 529.7 ± 160.0 | 20.7 | 794.5 | 1.21 ± 0.71 |
| whyando | input-lanjian | 619.1 ± 1801.8 | 0.0 | 14946.2 | 1.41 ± 4.17 |
| kcen | input-whyando | 809.7 ± 258.3 | 0.0 | 1190.6 | 1.85 ± 1.10 |
| kcen | input-lanjian | 871.4 ± 158.0 | 0.0 | 1061.2 | 1.99 ± 1.07 |
| kcen | input-mattcl | 994.0 ± 2317.3 | 0.0 | 19059.7 | 2.27 ± 5.41 |
| lanjian | input-whyando | 1084.2 ± 297.1 | 86.5 | 1504.5 | 2.47 ± 1.42 |
| lanjian | input-mattcl | 1098.4 ± 253.7 | 19.3 | 1445.5 | 2.51 ± 1.39 |
| lanjian | input-lanjian | 1172.9 ± 185.6 | 586.1 | 1420.4 | 2.68 ± 1.42 |
| mattcl-py | input-lanjian | 20082.0 ± 400.4 | 18991.9 | 21472.7 | 45.81 ± 23.19 |
| mattcl-py | input-mattcl | 20738.6 ± 1114.7 | 19263.5 | 28134.3 | 47.31 ± 24.06 |
| mattcl-py | input-whyando | 20745.4 ± 1242.9 | 19313.0 | 27989.8 | 47.32 ± 24.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|