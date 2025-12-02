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
| whyando | input-whyando | 561.3 ± 172.3 | 0.0 | 1272.2 | 1.00 |
| whyando | input-lanjian | 565.8 ± 150.1 | 28.2 | 1051.1 | 1.01 ± 0.41 |
| whyando | input-mattcl | 568.0 ± 167.1 | 0.0 | 1074.4 | 1.01 ± 0.43 |
| mattcl | input-lanjian | 640.1 ± 391.2 | 0.0 | 1135.8 | 1.14 ± 0.78 |
| kcen | input-lanjian | 772.4 ± 199.9 | 3.4 | 1092.9 | 1.38 ± 0.55 |
| kcen | input-mattcl | 827.7 ± 170.2 | 0.0 | 1541.3 | 1.47 ± 0.54 |
| kcen | input-whyando | 829.8 ± 167.1 | 0.0 | 1328.2 | 1.48 ± 0.54 |
| mattcl | input-whyando | 997.2 ± 164.0 | 387.8 | 1609.5 | 1.78 ± 0.62 |
| mattcl | input-mattcl | 999.7 ± 152.6 | 600.0 | 1791.8 | 1.78 ± 0.61 |
| lanjian | input-lanjian | 1045.1 ± 192.4 | 54.5 | 1517.6 | 1.86 ± 0.67 |
| lanjian | input-whyando | 1101.0 ± 184.3 | 514.3 | 1905.1 | 1.96 ± 0.69 |
| lanjian | input-mattcl | 1168.4 ± 228.5 | 105.3 | 1870.9 | 2.08 ± 0.76 |
| mattcl-py | input-whyando | 20287.2 ± 554.3 | 19156.9 | 23125.7 | 36.14 ± 11.14 |
| mattcl-py | input-lanjian | 20602.8 ± 605.2 | 19236.1 | 22512.8 | 36.71 ± 11.32 |
| mattcl-py | input-mattcl | 20634.2 ± 696.9 | 19322.2 | 23885.0 | 36.76 ± 11.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|