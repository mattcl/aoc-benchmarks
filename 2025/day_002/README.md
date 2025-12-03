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
| whyando | input-lanjian | 533.1 ± 178.9 | 0.0 | 1054.4 | 1.00 |
| whyando | input-whyando | 550.7 ± 168.6 | 0.0 | 1070.3 | 1.03 ± 0.47 |
| whyando | input-mattcl | 553.3 ± 151.4 | 0.2 | 1144.3 | 1.04 ± 0.45 |
| kcen | input-lanjian | 659.5 ± 327.1 | 0.0 | 1343.5 | 1.24 ± 0.74 |
| kcen | input-mattcl | 819.2 ± 115.2 | 440.1 | 1233.0 | 1.54 ± 0.56 |
| kcen | input-whyando | 821.6 ± 130.7 | 0.0 | 1409.7 | 1.54 ± 0.57 |
| mattcl | input-lanjian | 983.3 ± 200.6 | 385.9 | 1891.5 | 1.84 ± 0.72 |
| mattcl | input-mattcl | 993.7 ± 189.8 | 410.4 | 1532.0 | 1.86 ± 0.72 |
| mattcl | input-whyando | 1016.9 ± 142.1 | 426.3 | 1617.8 | 1.91 ± 0.69 |
| lanjian | input-lanjian | 1034.6 ± 249.5 | 50.3 | 1783.9 | 1.94 ± 0.80 |
| lanjian | input-whyando | 1096.3 ± 170.7 | 500.2 | 1796.5 | 2.06 ± 0.76 |
| lanjian | input-mattcl | 1146.1 ± 221.8 | 517.9 | 1870.7 | 2.15 ± 0.83 |
| mattcl-py | input-whyando | 20236.9 ± 455.9 | 19154.0 | 22556.8 | 37.96 ± 12.77 |
| mattcl-py | input-lanjian | 20641.8 ± 788.9 | 19008.9 | 24170.1 | 38.72 ± 13.08 |
| mattcl-py | input-mattcl | 20668.6 ± 616.7 | 19618.6 | 23303.7 | 38.77 ± 13.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|