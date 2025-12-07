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
| whyando | input-whyando | 235.8 ± 192.6 | 0.0 | 1000.3 | 1.00 |
| whyando | input-lanjian | 357.4 ± 174.7 | 0.0 | 1112.4 | 1.52 ± 1.44 |
| whyando | input-mattcl | 397.9 ± 163.8 | 0.0 | 1047.6 | 1.69 ± 1.54 |
| mattcl | input-whyando | 614.7 ± 143.8 | 0.0 | 1097.8 | 2.61 ± 2.22 |
| mattcl | input-mattcl | 652.8 ± 150.6 | 0.0 | 1160.6 | 2.77 ± 2.35 |
| mattcl | input-lanjian | 657.4 ± 199.4 | 93.6 | 2403.8 | 2.79 ± 2.43 |
| kcen | input-mattcl | 774.4 ± 147.0 | 192.5 | 1247.8 | 3.28 ± 2.75 |
| kcen | input-lanjian | 777.5 ± 126.6 | 372.5 | 1167.4 | 3.30 ± 2.75 |
| kcen | input-whyando | 785.5 ± 134.5 | 0.0 | 1272.8 | 3.33 ± 2.78 |
| lanjian | input-whyando | 1109.8 ± 188.3 | 416.0 | 1833.6 | 4.71 ± 3.93 |
| lanjian | input-lanjian | 1117.0 ± 205.5 | 556.6 | 2015.7 | 4.74 ± 3.97 |
| lanjian | input-mattcl | 1149.8 ± 209.3 | 531.6 | 1841.7 | 4.88 ± 4.08 |
| mattcl-py | input-whyando | 20489.6 ± 662.2 | 19250.7 | 23192.0 | 86.90 ± 71.05 |
| mattcl-py | input-lanjian | 20717.3 ± 652.1 | 19766.9 | 23477.9 | 87.87 ± 71.83 |
| mattcl-py | input-mattcl | 20733.9 ± 831.8 | 19401.2 | 26174.5 | 87.94 ± 71.92 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|