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
| whyando | input-whyando | 508.5 ± 150.7 | 0.0 | 729.4 | 1.00 |
| whyando | input-mattcl | 510.3 ± 175.5 | 0.0 | 988.1 | 1.00 ± 0.46 |
| whyando | input-lanjian | 531.0 ± 142.9 | 0.0 | 1121.7 | 1.04 ± 0.42 |
| kcen | input-lanjian | 751.4 ± 165.7 | 0.0 | 1250.8 | 1.48 ± 0.55 |
| kcen | input-whyando | 752.4 ± 149.0 | 0.0 | 1191.7 | 1.48 ± 0.53 |
| kcen | input-mattcl | 769.8 ± 149.8 | 217.9 | 1292.3 | 1.51 ± 0.54 |
| mattcl | input-mattcl | 945.8 ± 160.2 | 280.3 | 1536.2 | 1.86 ± 0.63 |
| mattcl | input-whyando | 965.8 ± 193.7 | 68.0 | 1800.2 | 1.90 ± 0.68 |
| mattcl | input-lanjian | 998.8 ± 216.6 | 217.2 | 1686.4 | 1.96 ± 0.72 |
| lanjian | input-lanjian | 1074.8 ± 180.8 | 460.3 | 1815.2 | 2.11 ± 0.72 |
| lanjian | input-whyando | 1125.6 ± 210.5 | 554.5 | 2008.9 | 2.21 ± 0.78 |
| lanjian | input-mattcl | 1138.7 ± 201.6 | 451.2 | 1862.8 | 2.24 ± 0.77 |
| mattcl-py | input-whyando | 20412.8 ± 533.6 | 19370.9 | 22662.8 | 40.14 ± 11.94 |
| mattcl-py | input-mattcl | 20607.6 ± 614.8 | 19545.4 | 23358.7 | 40.52 ± 12.07 |
| mattcl-py | input-lanjian | 20661.2 ± 659.4 | 19752.7 | 23822.9 | 40.63 ± 12.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|