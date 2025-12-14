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
| whyando | input-lanjian | 445.2 ± 178.1 | 0.0 | 1003.3 | 1.00 |
| whyando | input-mattcl | 471.7 ± 162.7 | 0.0 | 1126.7 | 1.06 ± 0.56 |
| whyando | input-whyando | 494.0 ± 156.6 | 0.0 | 1017.1 | 1.11 ± 0.57 |
| mattcl | input-lanjian | 649.6 ± 175.2 | 0.0 | 846.1 | 1.46 ± 0.70 |
| lanjian | input-whyando | 703.1 ± 152.4 | 14.5 | 1222.0 | 1.58 ± 0.72 |
| mattcl | input-whyando | 705.1 ± 166.3 | 118.3 | 1526.1 | 1.58 ± 0.74 |
| lanjian | input-lanjian | 708.5 ± 132.3 | 0.0 | 1000.6 | 1.59 ± 0.70 |
| mattcl | input-mattcl | 715.2 ± 158.9 | 0.0 | 1354.2 | 1.61 ± 0.74 |
| lanjian | input-mattcl | 761.1 ± 173.4 | 262.4 | 1528.7 | 1.71 ± 0.79 |
| kcen | input-mattcl | 875.4 ± 190.6 | 373.4 | 1751.7 | 1.97 ± 0.90 |
| kcen | input-lanjian | 897.0 ± 202.5 | 173.3 | 1567.1 | 2.01 ± 0.93 |
| kcen | input-whyando | 915.4 ± 204.1 | 295.7 | 1521.7 | 2.06 ± 0.94 |
| mattcl-py | input-whyando | 20531.4 ± 663.1 | 19546.7 | 23011.6 | 46.12 ± 18.51 |
| mattcl-py | input-lanjian | 20657.1 ± 572.3 | 19276.1 | 23442.9 | 46.40 ± 18.61 |
| mattcl-py | input-mattcl | 20782.6 ± 638.3 | 19651.3 | 23824.9 | 46.69 ± 18.73 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|