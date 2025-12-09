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
| whyando | input-lanjian | 347.6 ± 170.7 | 0.0 | 1046.4 | 1.00 |
| whyando | input-whyando | 365.0 ± 139.7 | 0.0 | 610.4 | 1.05 ± 0.65 |
| whyando | input-mattcl | 398.4 ± 146.3 | 0.0 | 954.5 | 1.15 ± 0.70 |
| mattcl | input-whyando | 624.0 ± 173.9 | 0.0 | 1126.2 | 1.80 ± 1.01 |
| lanjian | input-mattcl | 630.9 ± 174.6 | 0.0 | 1516.7 | 1.82 ± 1.02 |
| lanjian | input-whyando | 632.1 ± 163.6 | 0.0 | 1054.2 | 1.82 ± 1.01 |
| mattcl | input-mattcl | 634.1 ± 146.8 | 0.0 | 994.9 | 1.82 ± 0.99 |
| mattcl | input-lanjian | 635.2 ± 145.3 | 0.0 | 1180.9 | 1.83 ± 0.99 |
| lanjian | input-lanjian | 647.0 ± 133.0 | 0.0 | 1019.7 | 1.86 ± 0.99 |
| kcen | input-mattcl | 766.9 ± 152.9 | 0.0 | 1267.1 | 2.21 ± 1.17 |
| kcen | input-lanjian | 786.1 ± 137.2 | 270.6 | 1420.8 | 2.26 ± 1.18 |
| kcen | input-whyando | 824.2 ± 159.2 | 262.3 | 1525.9 | 2.37 ± 1.25 |
| mattcl-py | input-whyando | 20434.5 ± 515.9 | 19385.5 | 23372.9 | 58.79 ± 28.91 |
| mattcl-py | input-lanjian | 20642.4 ± 585.0 | 19369.6 | 24262.9 | 59.39 ± 29.21 |
| mattcl-py | input-mattcl | 20659.1 ± 521.1 | 19972.5 | 23995.9 | 59.43 ± 29.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|