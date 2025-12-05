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
| whyando | input-whyando | 535.7 ± 193.5 | 0.0 | 1268.0 | 1.00 |
| whyando | input-lanjian | 540.8 ± 161.1 | 0.0 | 1021.4 | 1.01 ± 0.47 |
| whyando | input-mattcl | 547.6 ± 162.2 | 0.0 | 1085.1 | 1.02 ± 0.48 |
| kcen | input-mattcl | 793.2 ± 147.9 | 252.8 | 1223.4 | 1.48 ± 0.60 |
| kcen | input-whyando | 795.1 ± 123.1 | 0.0 | 1188.7 | 1.48 ± 0.58 |
| kcen | input-lanjian | 802.1 ± 150.5 | 335.2 | 1292.3 | 1.50 ± 0.61 |
| mattcl | input-whyando | 984.4 ± 140.1 | 358.0 | 1618.7 | 1.84 ± 0.71 |
| mattcl | input-mattcl | 988.8 ± 158.9 | 233.7 | 1707.1 | 1.85 ± 0.73 |
| mattcl | input-lanjian | 995.7 ± 201.9 | 443.0 | 2955.4 | 1.86 ± 0.77 |
| lanjian | input-mattcl | 1102.0 ± 184.7 | 234.9 | 1885.5 | 2.06 ± 0.82 |
| lanjian | input-whyando | 1158.6 ± 200.9 | 501.8 | 1995.8 | 2.16 ± 0.87 |
| lanjian | input-lanjian | 1180.5 ± 221.8 | 542.4 | 2065.6 | 2.20 ± 0.90 |
| mattcl-py | input-whyando | 20378.8 ± 510.1 | 19581.4 | 23048.4 | 38.04 ± 13.78 |
| mattcl-py | input-lanjian | 20554.2 ± 578.3 | 19438.8 | 24072.1 | 38.37 ± 13.90 |
| mattcl-py | input-mattcl | 20642.0 ± 580.2 | 19501.7 | 23691.6 | 38.54 ± 13.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|