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
| whyando | input-whyando | 592.6 ± 160.6 | 0.0 | 1053.9 | 1.00 |
| whyando | input-mattcl | 594.9 ± 167.9 | 0.0 | 1091.4 | 1.00 ± 0.39 |
| whyando | input-lanjian | 602.0 ± 165.6 | 0.0 | 1314.9 | 1.02 ± 0.39 |
| kcen | input-whyando | 804.5 ± 168.4 | 0.0 | 1346.6 | 1.36 ± 0.46 |
| kcen | input-lanjian | 819.6 ± 137.0 | 8.7 | 1264.0 | 1.38 ± 0.44 |
| kcen | input-mattcl | 839.7 ± 152.6 | 375.7 | 1594.9 | 1.42 ± 0.46 |
| mattcl | input-whyando | 984.0 ± 198.1 | 16.2 | 1726.5 | 1.66 ± 0.56 |
| mattcl | input-mattcl | 1035.2 ± 207.8 | 323.5 | 2523.5 | 1.75 ± 0.59 |
| mattcl | input-lanjian | 1074.0 ± 163.5 | 564.1 | 1733.0 | 1.81 ± 0.56 |
| lanjian | input-whyando | 1302.4 ± 201.8 | 556.8 | 1695.1 | 2.20 ± 0.69 |
| lanjian | input-lanjian | 1335.2 ± 152.1 | 710.1 | 1780.6 | 2.25 ± 0.66 |
| lanjian | input-mattcl | 1338.0 ± 211.6 | 233.2 | 2791.0 | 2.26 ± 0.71 |
| mattcl-py | input-mattcl | 18255.7 ± 606.7 | 17263.5 | 21479.9 | 30.81 ± 8.41 |
| mattcl-py | input-lanjian | 18287.4 ± 700.3 | 17188.9 | 21503.9 | 30.86 ± 8.45 |
| mattcl-py | input-whyando | 18317.4 ± 780.0 | 17213.0 | 21528.5 | 30.91 ± 8.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|