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
| whyando | input-whyando | 545.5 ± 166.1 | 0.0 | 1072.0 | 1.00 |
| whyando | input-mattcl | 564.2 ± 141.0 | 0.0 | 1055.8 | 1.03 ± 0.41 |
| whyando | input-lanjian | 578.3 ± 142.7 | 0.0 | 1106.7 | 1.06 ± 0.42 |
| kcen | input-whyando | 803.6 ± 122.2 | 258.6 | 992.5 | 1.47 ± 0.50 |
| kcen | input-mattcl | 816.4 ± 134.7 | 256.5 | 1343.2 | 1.50 ± 0.52 |
| kcen | input-lanjian | 872.6 ± 194.9 | 84.3 | 1532.0 | 1.60 ± 0.60 |
| mattcl | input-lanjian | 978.2 ± 141.9 | 435.7 | 1603.2 | 1.79 ± 0.60 |
| mattcl | input-whyando | 997.8 ± 143.6 | 18.2 | 1563.9 | 1.83 ± 0.62 |
| mattcl | input-mattcl | 1061.2 ± 231.4 | 388.7 | 2277.7 | 1.95 ± 0.73 |
| lanjian | input-lanjian | 1167.2 ± 224.3 | 469.9 | 2552.4 | 2.14 ± 0.77 |
| lanjian | input-whyando | 1171.5 ± 197.0 | 573.7 | 2175.8 | 2.15 ± 0.75 |
| lanjian | input-mattcl | 1187.6 ± 200.2 | 619.3 | 1980.0 | 2.18 ± 0.76 |
| mattcl-py | input-whyando | 20339.5 ± 479.5 | 19178.4 | 22113.3 | 37.29 ± 11.39 |
| mattcl-py | input-lanjian | 20607.5 ± 611.1 | 19617.0 | 23711.0 | 37.78 ± 11.56 |
| mattcl-py | input-mattcl | 20720.9 ± 624.1 | 19309.0 | 23750.5 | 37.99 ± 11.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|