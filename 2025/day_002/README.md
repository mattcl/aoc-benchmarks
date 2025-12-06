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
| whyando | input-mattcl | 542.3 ± 171.4 | 0.0 | 1044.6 | 1.00 |
| whyando | input-whyando | 550.3 ± 158.2 | 0.0 | 1026.6 | 1.01 ± 0.43 |
| whyando | input-lanjian | 573.6 ± 165.2 | 0.0 | 1150.3 | 1.06 ± 0.45 |
| kcen | input-whyando | 797.7 ± 121.7 | 57.6 | 1120.5 | 1.47 ± 0.52 |
| kcen | input-mattcl | 807.0 ± 150.7 | 248.3 | 1423.1 | 1.49 ± 0.55 |
| kcen | input-lanjian | 818.7 ± 169.2 | 29.0 | 1337.6 | 1.51 ± 0.57 |
| mattcl | input-mattcl | 1029.0 ± 208.4 | 296.7 | 1654.2 | 1.90 ± 0.71 |
| mattcl | input-lanjian | 1037.9 ± 189.1 | 230.7 | 1833.0 | 1.91 ± 0.70 |
| mattcl | input-whyando | 1050.0 ± 187.5 | 390.5 | 1766.5 | 1.94 ± 0.70 |
| lanjian | input-lanjian | 1130.8 ± 207.4 | 585.3 | 1931.6 | 2.09 ± 0.76 |
| lanjian | input-whyando | 1160.7 ± 211.1 | 571.6 | 2033.4 | 2.14 ± 0.78 |
| lanjian | input-mattcl | 1196.2 ± 237.3 | 202.3 | 1848.1 | 2.21 ± 0.82 |
| mattcl-py | input-whyando | 20299.2 ± 579.5 | 19356.6 | 23552.4 | 37.43 ± 11.88 |
| mattcl-py | input-lanjian | 20590.8 ± 417.4 | 19798.9 | 23124.3 | 37.97 ± 12.03 |
| mattcl-py | input-mattcl | 20621.8 ± 625.1 | 19220.1 | 23587.4 | 38.03 ± 12.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|