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
| whyando | input-lanjian | 543.0 ± 167.4 | 0.0 | 1024.9 | 1.00 |
| whyando | input-whyando | 552.8 ± 173.3 | 0.0 | 1079.7 | 1.02 ± 0.45 |
| whyando | input-mattcl | 575.3 ± 163.1 | 14.9 | 1071.2 | 1.06 ± 0.44 |
| kcen | input-whyando | 855.3 ± 175.8 | 0.0 | 1418.5 | 1.58 ± 0.58 |
| kcen | input-mattcl | 857.0 ± 157.4 | 217.1 | 1574.9 | 1.58 ± 0.57 |
| kcen | input-lanjian | 867.0 ± 206.4 | 0.0 | 1459.1 | 1.60 ± 0.62 |
| mattcl | input-mattcl | 1003.8 ± 185.3 | 14.1 | 1629.8 | 1.85 ± 0.66 |
| mattcl | input-whyando | 1008.0 ± 154.1 | 372.2 | 1624.3 | 1.86 ± 0.64 |
| mattcl | input-lanjian | 1030.6 ± 202.2 | 75.8 | 2152.1 | 1.90 ± 0.69 |
| lanjian | input-lanjian | 1134.7 ± 183.5 | 561.5 | 1867.9 | 2.09 ± 0.73 |
| lanjian | input-mattcl | 1161.1 ± 209.5 | 146.4 | 1839.2 | 2.14 ± 0.76 |
| lanjian | input-whyando | 1196.6 ± 242.8 | 515.4 | 2275.0 | 2.20 ± 0.81 |
| mattcl-py | input-whyando | 20390.9 ± 582.6 | 19338.1 | 23402.8 | 37.55 ± 11.63 |
| mattcl-py | input-lanjian | 20607.5 ± 599.0 | 19376.7 | 23366.0 | 37.95 ± 11.75 |
| mattcl-py | input-mattcl | 20769.0 ± 684.4 | 19331.0 | 25796.8 | 38.25 ± 11.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|