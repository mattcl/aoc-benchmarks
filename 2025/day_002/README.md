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
| whyando | input-lanjian | 354.3 ± 181.1 | 0.0 | 852.3 | 1.00 |
| whyando | input-whyando | 388.1 ± 177.7 | 0.0 | 1535.3 | 1.10 ± 0.75 |
| whyando | input-mattcl | 405.2 ± 154.5 | 0.0 | 1105.4 | 1.14 ± 0.73 |
| mattcl | input-whyando | 602.9 ± 142.2 | 137.0 | 1066.3 | 1.70 ± 0.96 |
| mattcl | input-mattcl | 621.7 ± 149.2 | 0.0 | 1126.7 | 1.75 ± 0.99 |
| mattcl | input-lanjian | 622.0 ± 157.0 | 10.0 | 1120.7 | 1.76 ± 1.00 |
| lanjian | input-whyando | 627.8 ± 132.1 | 22.4 | 963.2 | 1.77 ± 0.98 |
| lanjian | input-lanjian | 637.3 ± 135.5 | 158.6 | 1030.8 | 1.80 ± 1.00 |
| lanjian | input-mattcl | 638.9 ± 204.1 | 0.0 | 1328.0 | 1.80 ± 1.09 |
| kcen | input-lanjian | 724.5 ± 177.2 | 0.0 | 1435.1 | 2.04 ± 1.16 |
| kcen | input-whyando | 780.3 ± 127.3 | 318.1 | 1223.9 | 2.20 ± 1.18 |
| kcen | input-mattcl | 816.0 ± 178.1 | 195.7 | 1738.2 | 2.30 ± 1.28 |
| mattcl-py | input-whyando | 20447.8 ± 718.1 | 19130.6 | 23497.2 | 57.71 ± 29.57 |
| mattcl-py | input-lanjian | 20680.5 ± 552.4 | 19179.2 | 24074.8 | 58.37 ± 29.88 |
| mattcl-py | input-mattcl | 20767.1 ± 590.9 | 19740.0 | 22757.9 | 58.61 ± 30.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|