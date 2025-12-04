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
| whyando | input-mattcl | 732.4 ± 152.9 | 217.9 | 1578.6 | 1.00 |
| whyando | input-whyando | 734.4 ± 168.6 | 0.0 | 1113.0 | 1.00 ± 0.31 |
| whyando | input-lanjian | 742.4 ± 138.7 | 238.8 | 1131.8 | 1.01 ± 0.28 |
| kcen | input-lanjian | 801.5 ± 300.0 | 0.0 | 1462.1 | 1.09 ± 0.47 |
| kcen | input-whyando | 949.8 ± 116.1 | 455.0 | 1413.1 | 1.30 ± 0.31 |
| kcen | input-mattcl | 1023.2 ± 165.6 | 318.9 | 1546.5 | 1.40 ± 0.37 |
| mattcl | input-lanjian | 1121.8 ± 160.7 | 518.4 | 1842.3 | 1.53 ± 0.39 |
| mattcl | input-mattcl | 1134.0 ± 150.3 | 681.3 | 1848.0 | 1.55 ± 0.38 |
| mattcl | input-whyando | 1207.2 ± 225.9 | 358.3 | 2340.2 | 1.65 ± 0.46 |
| lanjian | input-lanjian | 1266.1 ± 340.5 | 259.6 | 2283.1 | 1.73 ± 0.59 |
| lanjian | input-whyando | 1437.7 ± 212.6 | 710.2 | 2198.5 | 1.96 ± 0.50 |
| lanjian | input-mattcl | 1442.1 ± 244.1 | 633.8 | 2778.5 | 1.97 ± 0.53 |
| mattcl-py | input-lanjian | 18286.1 ± 642.3 | 16927.7 | 21577.6 | 24.97 ± 5.28 |
| mattcl-py | input-whyando | 18334.3 ± 606.7 | 17408.5 | 21448.2 | 25.03 ± 5.29 |
| mattcl-py | input-mattcl | 18349.2 ± 565.1 | 17147.0 | 20972.0 | 25.05 ± 5.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|