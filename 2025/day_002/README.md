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
| whyando | input-lanjian | 338.2 ± 173.2 | 0.0 | 972.6 | 1.00 |
| whyando | input-mattcl | 349.6 ± 155.8 | 0.0 | 728.4 | 1.03 ± 0.70 |
| whyando | input-whyando | 360.4 ± 157.3 | 0.0 | 964.8 | 1.07 ± 0.72 |
| mattcl | input-lanjian | 590.7 ± 145.6 | 0.0 | 880.9 | 1.75 ± 0.99 |
| mattcl | input-whyando | 620.2 ± 174.2 | 14.5 | 1560.9 | 1.83 ± 1.07 |
| lanjian | input-mattcl | 624.2 ± 151.1 | 0.0 | 1118.2 | 1.85 ± 1.04 |
| lanjian | input-whyando | 627.6 ± 161.0 | 92.4 | 1154.0 | 1.86 ± 1.06 |
| lanjian | input-lanjian | 633.0 ± 153.7 | 93.3 | 1094.4 | 1.87 ± 1.06 |
| mattcl | input-mattcl | 636.1 ± 154.3 | 0.0 | 1064.8 | 1.88 ± 1.07 |
| kcen | input-lanjian | 735.0 ± 147.0 | 205.1 | 1206.3 | 2.17 ± 1.19 |
| kcen | input-mattcl | 759.6 ± 151.3 | 0.0 | 1300.4 | 2.25 ± 1.23 |
| kcen | input-whyando | 782.5 ± 98.3 | 377.8 | 1181.1 | 2.31 ± 1.22 |
| mattcl-py | input-whyando | 20501.7 ± 780.1 | 19419.9 | 23685.2 | 60.61 ± 31.11 |
| mattcl-py | input-mattcl | 20557.6 ± 524.6 | 19600.4 | 23863.8 | 60.78 ± 31.15 |
| mattcl-py | input-lanjian | 20658.4 ± 716.2 | 19737.6 | 24093.3 | 61.07 ± 31.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|