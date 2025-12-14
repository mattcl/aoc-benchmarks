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
| whyando | input-lanjian | 441.3 ± 161.7 | 0.0 | 956.0 | 1.00 |
| whyando | input-whyando | 447.9 ± 167.1 | 0.0 | 1054.7 | 1.02 ± 0.53 |
| whyando | input-mattcl | 457.5 ± 168.7 | 0.0 | 1319.6 | 1.04 ± 0.54 |
| mattcl | input-mattcl | 661.6 ± 139.9 | 0.0 | 869.0 | 1.50 ± 0.63 |
| lanjian | input-whyando | 674.9 ± 169.9 | 0.0 | 1108.0 | 1.53 ± 0.68 |
| mattcl | input-lanjian | 677.1 ± 152.7 | 101.4 | 1106.1 | 1.53 ± 0.66 |
| lanjian | input-mattcl | 677.8 ± 157.8 | 0.0 | 1078.7 | 1.54 ± 0.67 |
| mattcl | input-whyando | 684.6 ± 161.1 | 187.4 | 1269.3 | 1.55 ± 0.68 |
| lanjian | input-lanjian | 688.7 ± 148.6 | 0.0 | 1137.1 | 1.56 ± 0.66 |
| kcen | input-mattcl | 787.6 ± 136.5 | 225.6 | 1453.1 | 1.78 ± 0.72 |
| kcen | input-lanjian | 816.6 ± 122.2 | 327.6 | 1271.8 | 1.85 ± 0.73 |
| kcen | input-whyando | 834.0 ± 135.1 | 353.0 | 1599.1 | 1.89 ± 0.76 |
| mattcl-py | input-whyando | 20386.1 ± 461.1 | 19429.9 | 23206.2 | 46.20 ± 16.96 |
| mattcl-py | input-mattcl | 20709.1 ± 647.8 | 19467.3 | 24232.3 | 46.93 ± 17.26 |
| mattcl-py | input-lanjian | 20763.0 ± 702.5 | 19681.6 | 23880.3 | 47.05 ± 17.31 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|