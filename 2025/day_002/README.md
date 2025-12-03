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
| kcen | input-lanjian | 462.4 ± 65.8 | 380.0 | 868.8 | 1.00 |
| lanjian | input-lanjian | 760.4 ± 227.3 | 492.6 | 1708.2 | 1.64 ± 0.54 |
| whyando | input-lanjian | 934.8 ± 229.1 | 251.1 | 1333.2 | 2.02 ± 0.57 |
| mattcl | input-lanjian | 938.1 ± 369.7 | 446.1 | 1748.7 | 2.03 ± 0.85 |
| whyando | input-mattcl | 964.0 ± 207.4 | 355.1 | 1345.8 | 2.08 ± 0.54 |
| whyando | input-whyando | 1043.2 ± 159.8 | 264.4 | 1334.2 | 2.26 ± 0.47 |
| kcen | input-mattcl | 1252.9 ± 266.7 | 327.6 | 1589.5 | 2.71 ± 0.69 |
| kcen | input-whyando | 1290.3 ± 225.3 | 401.2 | 1635.6 | 2.79 ± 0.63 |
| mattcl | input-whyando | 1345.9 ± 283.3 | 502.3 | 1716.5 | 2.91 ± 0.74 |
| lanjian | input-mattcl | 1471.3 ± 739.6 | 575.4 | 7952.1 | 3.18 ± 1.66 |
| mattcl | input-mattcl | 1477.0 ± 181.3 | 688.5 | 1757.5 | 3.19 ± 0.60 |
| lanjian | input-whyando | 1578.3 ± 260.0 | 519.4 | 2020.4 | 3.41 ± 0.74 |
| mattcl-py | input-whyando | 22196.6 ± 602.0 | 21001.2 | 25904.9 | 48.00 ± 6.95 |
| mattcl-py | input-lanjian | 22486.8 ± 912.5 | 21062.3 | 25331.9 | 48.63 ± 7.19 |
| mattcl-py | input-mattcl | 22978.9 ± 419.7 | 21851.6 | 24268.9 | 49.69 ± 7.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|