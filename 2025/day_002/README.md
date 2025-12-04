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
| whyando | input-mattcl | 523.9 ± 183.0 | 0.0 | 1076.6 | 1.00 |
| whyando | input-lanjian | 547.9 ± 159.3 | 0.0 | 1051.7 | 1.05 ± 0.48 |
| whyando | input-whyando | 565.6 ± 171.5 | 0.0 | 1200.7 | 1.08 ± 0.50 |
| kcen | input-whyando | 775.4 ± 161.2 | 234.8 | 1227.6 | 1.48 ± 0.60 |
| kcen | input-mattcl | 784.0 ± 121.0 | 328.8 | 1365.2 | 1.50 ± 0.57 |
| kcen | input-lanjian | 809.7 ± 171.0 | 0.0 | 1533.3 | 1.55 ± 0.63 |
| mattcl | input-mattcl | 949.8 ± 147.3 | 213.6 | 1395.6 | 1.81 ± 0.69 |
| mattcl | input-whyando | 973.5 ± 156.0 | 458.6 | 1628.3 | 1.86 ± 0.71 |
| mattcl | input-lanjian | 982.3 ± 146.7 | 394.8 | 1566.3 | 1.87 ± 0.71 |
| lanjian | input-mattcl | 1124.5 ± 216.9 | 489.3 | 2154.6 | 2.15 ± 0.86 |
| lanjian | input-lanjian | 1128.1 ± 235.3 | 397.7 | 1974.0 | 2.15 ± 0.88 |
| lanjian | input-whyando | 1139.0 ± 199.1 | 397.5 | 2065.5 | 2.17 ± 0.85 |
| mattcl-py | input-whyando | 20259.5 ± 689.3 | 18986.2 | 23035.2 | 38.67 ± 13.57 |
| mattcl-py | input-mattcl | 20493.7 ± 495.0 | 19663.8 | 23615.3 | 39.11 ± 13.70 |
| mattcl-py | input-lanjian | 20625.3 ± 680.6 | 19469.7 | 23644.7 | 39.37 ± 13.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|