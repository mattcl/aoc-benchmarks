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
| whyando | input-lanjian | 475.0 ± 177.9 | 0.0 | 946.8 | 1.00 |
| whyando | input-mattcl | 484.1 ± 178.9 | 0.0 | 933.4 | 1.02 ± 0.54 |
| whyando | input-whyando | 494.3 ± 156.7 | 0.0 | 762.4 | 1.04 ± 0.51 |
| kcen | input-whyando | 742.3 ± 144.1 | 0.0 | 1293.2 | 1.56 ± 0.66 |
| kcen | input-mattcl | 765.0 ± 204.1 | 0.0 | 1317.4 | 1.61 ± 0.74 |
| kcen | input-lanjian | 778.8 ± 180.0 | 14.2 | 1671.1 | 1.64 ± 0.72 |
| mattcl | input-mattcl | 939.8 ± 170.6 | 375.8 | 1619.1 | 1.98 ± 0.82 |
| mattcl | input-lanjian | 964.3 ± 179.2 | 284.8 | 1616.7 | 2.03 ± 0.85 |
| mattcl | input-whyando | 999.9 ± 171.5 | 343.8 | 1507.4 | 2.10 ± 0.87 |
| lanjian | input-whyando | 1055.6 ± 211.4 | 232.9 | 1768.9 | 2.22 ± 0.94 |
| lanjian | input-mattcl | 1094.8 ± 239.8 | 336.6 | 1915.8 | 2.30 ± 1.00 |
| lanjian | input-lanjian | 1113.7 ± 221.5 | 406.9 | 2501.7 | 2.34 ± 0.99 |
| mattcl-py | input-whyando | 20421.9 ± 573.3 | 19048.0 | 23027.7 | 42.99 ± 16.14 |
| mattcl-py | input-mattcl | 20685.5 ± 768.2 | 19184.9 | 24065.3 | 43.55 ± 16.39 |
| mattcl-py | input-lanjian | 20693.1 ± 771.9 | 19388.4 | 23752.9 | 43.56 ± 16.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|