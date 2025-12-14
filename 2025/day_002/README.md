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
| whyando | input-whyando | 365.7 ± 178.1 | 0.0 | 841.8 | 1.00 |
| whyando | input-lanjian | 405.4 ± 159.0 | 0.0 | 854.2 | 1.11 ± 0.69 |
| mattcl | input-lanjian | 419.2 ± 282.6 | 0.0 | 1021.0 | 1.15 ± 0.95 |
| whyando | input-mattcl | 421.7 ± 164.8 | 0.0 | 1032.2 | 1.15 ± 0.72 |
| lanjian | input-lanjian | 552.5 ± 304.5 | 0.0 | 1380.5 | 1.51 ± 1.11 |
| mattcl | input-whyando | 614.2 ± 156.5 | 0.0 | 995.1 | 1.68 ± 0.92 |
| mattcl | input-mattcl | 628.6 ± 159.7 | 0.0 | 1410.2 | 1.72 ± 0.94 |
| lanjian | input-whyando | 629.8 ± 156.9 | 0.0 | 1019.5 | 1.72 ± 0.94 |
| lanjian | input-mattcl | 630.3 ± 186.6 | 0.0 | 1320.5 | 1.72 ± 0.98 |
| kcen | input-lanjian | 642.8 ± 291.7 | 0.0 | 1226.1 | 1.76 ± 1.17 |
| kcen | input-mattcl | 751.3 ± 158.8 | 0.0 | 1289.8 | 2.05 ± 1.09 |
| kcen | input-whyando | 801.8 ± 176.8 | 227.3 | 1401.7 | 2.19 ± 1.17 |
| mattcl-py | input-whyando | 20500.0 ± 602.7 | 19247.2 | 22756.1 | 56.05 ± 27.34 |
| mattcl-py | input-lanjian | 20716.6 ± 632.6 | 19724.8 | 23434.4 | 56.64 ± 27.63 |
| mattcl-py | input-mattcl | 20742.2 ± 575.5 | 19875.1 | 23320.8 | 56.71 ± 27.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|