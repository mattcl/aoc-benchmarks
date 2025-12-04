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
| whyando | input-mattcl | 500.2 ± 179.8 | 0.0 | 1005.8 | 1.00 |
| whyando | input-lanjian | 510.7 ± 147.3 | 0.0 | 912.7 | 1.02 ± 0.47 |
| whyando | input-whyando | 550.5 ± 142.9 | 0.0 | 1013.9 | 1.10 ± 0.49 |
| kcen | input-whyando | 742.1 ± 158.5 | 0.0 | 1145.3 | 1.48 ± 0.62 |
| kcen | input-lanjian | 745.7 ± 135.8 | 240.5 | 1193.0 | 1.49 ± 0.60 |
| kcen | input-mattcl | 762.8 ± 162.3 | 0.0 | 1199.6 | 1.52 ± 0.64 |
| mattcl | input-whyando | 939.2 ± 173.6 | 399.5 | 1610.8 | 1.88 ± 0.76 |
| mattcl | input-mattcl | 940.6 ± 131.6 | 409.6 | 1471.8 | 1.88 ± 0.73 |
| mattcl | input-lanjian | 973.8 ± 181.0 | 457.6 | 2178.9 | 1.95 ± 0.79 |
| lanjian | input-lanjian | 1049.1 ± 174.6 | 422.9 | 1732.4 | 2.10 ± 0.83 |
| lanjian | input-whyando | 1120.9 ± 205.1 | 379.3 | 1872.3 | 2.24 ± 0.90 |
| lanjian | input-mattcl | 1126.6 ± 239.9 | 407.2 | 1913.3 | 2.25 ± 0.94 |
| mattcl-py | input-whyando | 20228.8 ± 563.7 | 19010.2 | 22529.0 | 40.44 ± 14.58 |
| mattcl-py | input-mattcl | 20477.8 ± 709.7 | 19549.6 | 23483.7 | 40.94 ± 14.78 |
| mattcl-py | input-lanjian | 20555.6 ± 750.0 | 19422.3 | 25538.7 | 41.09 ± 14.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|