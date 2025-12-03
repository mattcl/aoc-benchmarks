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
| whyando | input-mattcl | 708.0 ± 153.5 | 0.0 | 1136.7 | 1.00 |
| whyando | input-whyando | 724.8 ± 160.5 | 0.0 | 1139.2 | 1.02 ± 0.32 |
| whyando | input-lanjian | 732.4 ± 128.6 | 160.0 | 1126.8 | 1.03 ± 0.29 |
| kcen | input-whyando | 849.8 ± 139.8 | 72.4 | 1497.9 | 1.20 ± 0.33 |
| kcen | input-mattcl | 862.6 ± 133.2 | 311.4 | 1563.3 | 1.22 ± 0.32 |
| kcen | input-lanjian | 886.6 ± 179.2 | 208.3 | 1406.8 | 1.25 ± 0.37 |
| mattcl | input-whyando | 1027.2 ± 178.8 | 500.6 | 1825.5 | 1.45 ± 0.40 |
| mattcl | input-lanjian | 1033.7 ± 192.3 | 16.8 | 1709.1 | 1.46 ± 0.42 |
| mattcl | input-mattcl | 1102.8 ± 194.9 | 421.5 | 1757.6 | 1.56 ± 0.44 |
| lanjian | input-whyando | 1292.8 ± 223.1 | 207.3 | 1930.8 | 1.83 ± 0.51 |
| lanjian | input-mattcl | 1300.6 ± 257.4 | 211.5 | 2002.5 | 1.84 ± 0.54 |
| lanjian | input-lanjian | 1329.1 ± 270.3 | 441.2 | 2617.1 | 1.88 ± 0.56 |
| mattcl-py | input-whyando | 18081.9 ± 679.0 | 16795.1 | 21233.8 | 25.54 ± 5.62 |
| mattcl-py | input-mattcl | 18150.1 ± 663.4 | 17201.7 | 21551.0 | 25.63 ± 5.64 |
| mattcl-py | input-lanjian | 18160.1 ± 618.3 | 17139.1 | 21191.0 | 25.65 ± 5.63 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|