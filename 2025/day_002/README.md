# Day 2 benchmarks

[link to problem](https://adventofcode.com/2025/day/2)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 2)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 538.4 ± 143.4 | 77.1 | 756.7 | 1.00 |
| whyando | input-whyando | 563.3 ± 135.7 | 0.0 | 1041.6 | 1.05 ± 0.38 |
| whyando | input-mattcl | 598.2 ± 172.5 | 0.0 | 1177.1 | 1.11 ± 0.44 |
| kcen | input-lanjian | 770.2 ± 133.3 | 271.2 | 1387.2 | 1.43 ± 0.45 |
| kcen | input-mattcl | 781.2 ± 165.2 | 0.0 | 1274.7 | 1.45 ± 0.49 |
| kcen | input-whyando | 797.4 ± 175.4 | 198.0 | 1664.8 | 1.48 ± 0.51 |
| mattcl | input-whyando | 980.9 ± 132.0 | 378.7 | 1638.9 | 1.82 ± 0.54 |
| mattcl | input-mattcl | 1027.8 ± 181.3 | 485.5 | 1876.0 | 1.91 ± 0.61 |
| mattcl | input-lanjian | 1043.6 ± 181.4 | 386.9 | 1886.9 | 1.94 ± 0.62 |
| lanjian | input-mattcl | 1090.5 ± 195.5 | 388.5 | 1824.8 | 2.03 ± 0.65 |
| lanjian | input-whyando | 1115.7 ± 245.7 | 426.2 | 3141.6 | 2.07 ± 0.72 |
| lanjian | input-lanjian | 1134.2 ± 218.5 | 366.2 | 1850.4 | 2.11 ± 0.69 |
| mattcl-py | input-whyando | 20279.7 ± 511.9 | 18952.3 | 23390.5 | 37.67 ± 10.07 |
| mattcl-py | input-lanjian | 20543.3 ± 624.7 | 19312.2 | 24047.7 | 38.16 ± 10.23 |
| mattcl-py | input-mattcl | 20564.1 ± 560.3 | 19266.4 | 23193.3 | 38.20 ± 10.22 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|