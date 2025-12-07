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
| whyando | input-lanjian | 361.8 ± 168.3 | 0.0 | 907.3 | 1.00 |
| whyando | input-mattcl | 389.3 ± 176.6 | 0.0 | 1078.2 | 1.08 ± 0.70 |
| whyando | input-whyando | 396.9 ± 163.6 | 0.0 | 957.0 | 1.10 ± 0.68 |
| mattcl | input-lanjian | 626.6 ± 168.7 | 0.0 | 1158.2 | 1.73 ± 0.93 |
| mattcl | input-whyando | 632.1 ± 157.2 | 0.0 | 1337.2 | 1.75 ± 0.92 |
| mattcl | input-mattcl | 648.2 ± 118.2 | 0.0 | 894.8 | 1.79 ± 0.90 |
| kcen | input-lanjian | 671.8 ± 273.3 | 0.0 | 1277.0 | 1.86 ± 1.15 |
| kcen | input-whyando | 789.8 ± 206.4 | 0.0 | 1348.7 | 2.18 ± 1.16 |
| kcen | input-mattcl | 793.8 ± 137.9 | 334.2 | 1180.1 | 2.19 ± 1.09 |
| lanjian | input-lanjian | 802.6 ± 169.8 | 0.0 | 1299.9 | 2.22 ± 1.13 |
| lanjian | input-mattcl | 830.9 ± 147.4 | 253.5 | 1394.3 | 2.30 ± 1.14 |
| lanjian | input-whyando | 873.0 ± 197.4 | 357.6 | 1619.0 | 2.41 ± 1.25 |
| mattcl-py | input-whyando | 20283.0 ± 565.0 | 18897.1 | 23148.7 | 56.06 ± 26.13 |
| mattcl-py | input-lanjian | 20609.7 ± 595.8 | 19628.9 | 24096.2 | 56.96 ± 26.55 |
| mattcl-py | input-mattcl | 20655.4 ± 662.0 | 19554.0 | 24358.2 | 57.09 ± 26.63 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|