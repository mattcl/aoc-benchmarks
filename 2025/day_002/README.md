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
| whyando | input-lanjian | 413.8 ± 171.6 | 0.0 | 776.5 | 1.00 |
| whyando | input-whyando | 429.5 ± 188.1 | 0.0 | 980.0 | 1.04 ± 0.63 |
| whyando | input-mattcl | 450.4 ± 155.5 | 0.0 | 1005.7 | 1.09 ± 0.59 |
| mattcl | input-mattcl | 661.0 ± 153.9 | 0.0 | 887.3 | 1.60 ± 0.76 |
| mattcl | input-lanjian | 679.1 ± 147.8 | 0.0 | 1017.5 | 1.64 ± 0.77 |
| mattcl | input-whyando | 699.8 ± 161.9 | 0.0 | 1113.7 | 1.69 ± 0.80 |
| kcen | input-mattcl | 854.3 ± 167.4 | 3.0 | 1382.4 | 2.06 ± 0.95 |
| kcen | input-lanjian | 859.7 ± 132.1 | 297.1 | 1315.2 | 2.08 ± 0.92 |
| kcen | input-whyando | 876.1 ± 137.1 | 421.8 | 1606.8 | 2.12 ± 0.94 |
| lanjian | input-whyando | 885.9 ± 137.1 | 351.6 | 1361.2 | 2.14 ± 0.95 |
| lanjian | input-mattcl | 957.3 ± 176.3 | 280.9 | 1519.5 | 2.31 ± 1.05 |
| lanjian | input-lanjian | 979.0 ± 169.4 | 428.4 | 1514.3 | 2.37 ± 1.06 |
| mattcl-py | input-whyando | 20533.8 ± 651.8 | 19540.4 | 23635.9 | 49.62 ± 20.64 |
| mattcl-py | input-mattcl | 20680.6 ± 588.7 | 19389.5 | 23549.3 | 49.97 ± 20.77 |
| mattcl-py | input-lanjian | 20758.3 ± 624.4 | 19843.0 | 23338.1 | 50.16 ± 20.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|