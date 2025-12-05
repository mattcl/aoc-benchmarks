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
| whyando | input-lanjian | 571.8 ± 169.8 | 0.0 | 1240.7 | 1.00 |
| whyando | input-mattcl | 574.3 ± 160.2 | 0.0 | 1078.6 | 1.00 ± 0.41 |
| whyando | input-whyando | 599.2 ± 157.5 | 0.0 | 1050.8 | 1.05 ± 0.42 |
| kcen | input-lanjian | 795.9 ± 151.5 | 250.6 | 1281.3 | 1.39 ± 0.49 |
| kcen | input-whyando | 824.8 ± 174.1 | 0.0 | 1307.5 | 1.44 ± 0.53 |
| kcen | input-mattcl | 829.0 ± 155.2 | 62.3 | 1313.8 | 1.45 ± 0.51 |
| mattcl | input-lanjian | 993.3 ± 216.4 | 363.8 | 2898.4 | 1.74 ± 0.64 |
| mattcl | input-mattcl | 1063.7 ± 153.8 | 560.9 | 1952.8 | 1.86 ± 0.61 |
| mattcl | input-whyando | 1068.2 ± 178.8 | 403.4 | 1948.3 | 1.87 ± 0.64 |
| lanjian | input-whyando | 1099.0 ± 190.4 | 404.3 | 1845.0 | 1.92 ± 0.66 |
| lanjian | input-mattcl | 1115.0 ± 167.3 | 604.7 | 1821.5 | 1.95 ± 0.65 |
| lanjian | input-lanjian | 1173.1 ± 266.1 | 62.1 | 2189.6 | 2.05 ± 0.77 |
| mattcl-py | input-whyando | 20310.7 ± 536.5 | 18936.1 | 22809.4 | 35.52 ± 10.59 |
| mattcl-py | input-lanjian | 20665.9 ± 644.4 | 19450.1 | 23794.4 | 36.14 ± 10.79 |
| mattcl-py | input-mattcl | 20707.0 ± 568.1 | 19360.3 | 22520.0 | 36.21 ± 10.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|