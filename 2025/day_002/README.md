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
| whyando | input-whyando | 513.8 ± 166.8 | 0.0 | 974.2 | 1.00 |
| whyando | input-lanjian | 528.4 ± 141.5 | 0.0 | 968.1 | 1.03 ± 0.43 |
| whyando | input-mattcl | 542.2 ± 153.0 | 0.0 | 1055.1 | 1.06 ± 0.45 |
| kcen | input-lanjian | 787.4 ± 115.6 | 323.8 | 1060.5 | 1.53 ± 0.55 |
| kcen | input-whyando | 816.9 ± 172.6 | 290.9 | 1599.9 | 1.59 ± 0.62 |
| kcen | input-mattcl | 827.6 ± 149.3 | 283.1 | 1350.1 | 1.61 ± 0.60 |
| mattcl | input-mattcl | 954.9 ± 157.3 | 368.4 | 1562.1 | 1.86 ± 0.68 |
| mattcl | input-whyando | 970.5 ± 158.6 | 402.6 | 1610.4 | 1.89 ± 0.69 |
| mattcl | input-lanjian | 1023.9 ± 211.8 | 138.7 | 1812.1 | 1.99 ± 0.77 |
| lanjian | input-mattcl | 1088.3 ± 179.2 | 558.8 | 1844.3 | 2.12 ± 0.77 |
| lanjian | input-whyando | 1110.5 ± 244.6 | 425.3 | 2918.7 | 2.16 ± 0.85 |
| lanjian | input-lanjian | 1146.1 ± 234.5 | 456.1 | 2017.0 | 2.23 ± 0.86 |
| mattcl-py | input-whyando | 20243.8 ± 699.1 | 19104.6 | 23658.7 | 39.40 ± 12.86 |
| mattcl-py | input-lanjian | 20329.1 ± 595.0 | 19120.3 | 23531.4 | 39.57 ± 12.90 |
| mattcl-py | input-mattcl | 20514.2 ± 696.2 | 19299.2 | 23903.3 | 39.93 ± 13.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|