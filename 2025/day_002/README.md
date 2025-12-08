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
| whyando | input-lanjian | 392.1 ± 182.3 | 0.0 | 853.4 | 1.00 |
| whyando | input-whyando | 396.3 ± 168.8 | 0.0 | 1050.1 | 1.01 ± 0.64 |
| whyando | input-mattcl | 404.4 ± 184.2 | 0.0 | 933.3 | 1.03 ± 0.67 |
| mattcl | input-lanjian | 754.5 ± 146.2 | 136.5 | 1322.3 | 1.92 ± 0.97 |
| mattcl | input-mattcl | 758.1 ± 218.4 | 0.0 | 1447.9 | 1.93 ± 1.06 |
| mattcl | input-whyando | 770.0 ± 147.5 | 0.0 | 1253.1 | 1.96 ± 0.99 |
| kcen | input-whyando | 812.5 ± 154.3 | 58.7 | 1327.8 | 2.07 ± 1.04 |
| kcen | input-mattcl | 825.5 ± 132.0 | 237.2 | 1249.2 | 2.11 ± 1.04 |
| kcen | input-lanjian | 831.7 ± 143.1 | 0.0 | 1239.0 | 2.12 ± 1.05 |
| lanjian | input-lanjian | 874.3 ± 156.7 | 46.6 | 1371.1 | 2.23 ± 1.11 |
| lanjian | input-whyando | 884.1 ± 148.1 | 320.2 | 1408.4 | 2.26 ± 1.11 |
| lanjian | input-mattcl | 925.8 ± 179.9 | 324.5 | 1530.9 | 2.36 ± 1.19 |
| mattcl-py | input-whyando | 20520.0 ± 692.9 | 18970.2 | 23804.9 | 52.34 ± 24.40 |
| mattcl-py | input-lanjian | 20694.1 ± 588.8 | 19365.6 | 23341.2 | 52.78 ± 24.58 |
| mattcl-py | input-mattcl | 20783.6 ± 643.3 | 19582.8 | 23847.8 | 53.01 ± 24.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|