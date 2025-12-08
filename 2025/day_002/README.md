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
| whyando | input-whyando | 386.7 ± 178.5 | 0.0 | 948.0 | 1.00 |
| whyando | input-mattcl | 395.1 ± 163.3 | 0.0 | 1054.3 | 1.02 ± 0.63 |
| whyando | input-lanjian | 411.9 ± 135.7 | 0.0 | 630.6 | 1.07 ± 0.60 |
| mattcl | input-whyando | 705.6 ± 176.0 | 135.3 | 1035.8 | 1.82 ± 0.96 |
| mattcl | input-mattcl | 723.4 ± 135.8 | 204.7 | 940.8 | 1.87 ± 0.93 |
| kcen | input-whyando | 737.3 ± 191.4 | 0.0 | 1274.5 | 1.91 ± 1.01 |
| mattcl | input-lanjian | 749.9 ± 162.5 | 0.0 | 1347.0 | 1.94 ± 0.99 |
| kcen | input-lanjian | 782.9 ± 173.0 | 0.0 | 1414.6 | 2.02 ± 1.04 |
| kcen | input-mattcl | 807.9 ± 147.5 | 69.8 | 1368.6 | 2.09 ± 1.04 |
| lanjian | input-mattcl | 845.4 ± 151.2 | 116.2 | 1469.9 | 2.19 ± 1.08 |
| lanjian | input-whyando | 847.1 ± 150.5 | 0.0 | 1322.6 | 2.19 ± 1.08 |
| lanjian | input-lanjian | 896.2 ± 161.3 | 362.2 | 1600.6 | 2.32 ± 1.15 |
| mattcl-py | input-whyando | 20474.1 ± 530.2 | 19388.7 | 22872.2 | 52.94 ± 24.47 |
| mattcl-py | input-mattcl | 20706.6 ± 683.0 | 19644.4 | 23877.7 | 53.54 ± 24.77 |
| mattcl-py | input-lanjian | 20715.0 ± 530.9 | 19772.6 | 24170.9 | 53.57 ± 24.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|