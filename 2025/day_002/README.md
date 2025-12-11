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
| whyando | input-whyando | 420.1 ± 168.2 | 0.0 | 1192.9 | 1.00 |
| whyando | input-lanjian | 437.8 ± 193.6 | 0.0 | 1042.1 | 1.04 ± 0.62 |
| whyando | input-mattcl | 452.3 ± 142.8 | 0.0 | 945.0 | 1.08 ± 0.55 |
| lanjian | input-mattcl | 568.1 ± 246.8 | 0.0 | 1068.5 | 1.35 ± 0.80 |
| kcen | input-mattcl | 613.9 ± 316.1 | 0.0 | 1242.1 | 1.46 ± 0.95 |
| mattcl | input-whyando | 647.4 ± 173.2 | 0.0 | 1139.7 | 1.54 ± 0.74 |
| lanjian | input-whyando | 677.4 ± 145.1 | 54.1 | 991.0 | 1.61 ± 0.73 |
| mattcl | input-mattcl | 684.6 ± 155.1 | 0.0 | 1058.6 | 1.63 ± 0.75 |
| lanjian | input-lanjian | 700.1 ± 201.5 | 0.0 | 1322.2 | 1.67 ± 0.82 |
| mattcl | input-lanjian | 712.6 ± 208.1 | 0.0 | 1724.4 | 1.70 ± 0.84 |
| kcen | input-lanjian | 774.3 ± 192.1 | 0.0 | 1441.7 | 1.84 ± 0.87 |
| kcen | input-whyando | 828.6 ± 165.2 | 0.0 | 1647.4 | 1.97 ± 0.88 |
| mattcl-py | input-whyando | 20544.6 ± 595.7 | 19115.1 | 23476.8 | 48.91 ± 19.64 |
| mattcl-py | input-lanjian | 20690.4 ± 678.8 | 19154.6 | 23910.0 | 49.25 ± 19.79 |
| mattcl-py | input-mattcl | 20700.8 ± 628.9 | 19352.6 | 23929.7 | 49.28 ± 19.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|