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
| whyando | input-lanjian | 403.6 ± 183.5 | 0.0 | 1031.5 | 1.00 |
| whyando | input-mattcl | 405.5 ± 176.0 | 0.0 | 1018.8 | 1.00 ± 0.63 |
| whyando | input-whyando | 439.2 ± 129.0 | 0.0 | 965.0 | 1.09 ± 0.59 |
| lanjian | input-mattcl | 526.6 ± 268.7 | 0.0 | 1129.2 | 1.30 ± 0.89 |
| mattcl | input-mattcl | 545.3 ± 224.7 | 0.0 | 917.7 | 1.35 ± 0.83 |
| lanjian | input-whyando | 627.6 ± 192.4 | 0.0 | 1141.6 | 1.56 ± 0.85 |
| kcen | input-whyando | 632.2 ± 325.1 | 0.0 | 1472.5 | 1.57 ± 1.08 |
| mattcl | input-lanjian | 643.7 ± 176.1 | 0.0 | 1485.2 | 1.60 ± 0.85 |
| mattcl | input-whyando | 652.6 ± 153.9 | 61.0 | 1264.1 | 1.62 ± 0.83 |
| lanjian | input-lanjian | 659.5 ± 150.7 | 0.0 | 896.5 | 1.63 ± 0.83 |
| kcen | input-mattcl | 765.7 ± 185.6 | 0.0 | 1365.2 | 1.90 ± 0.98 |
| kcen | input-lanjian | 793.6 ± 177.9 | 0.0 | 1315.5 | 1.97 ± 1.00 |
| mattcl-py | input-whyando | 20354.8 ± 661.3 | 19296.6 | 23596.8 | 50.44 ± 22.99 |
| mattcl-py | input-mattcl | 20516.9 ± 534.1 | 19150.7 | 22997.3 | 50.84 ± 23.15 |
| mattcl-py | input-lanjian | 20635.6 ± 677.4 | 19076.8 | 23708.5 | 51.13 ± 23.31 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|