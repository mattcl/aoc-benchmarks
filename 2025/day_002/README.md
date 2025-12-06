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
| whyando | input-lanjian | 519.3 ± 190.2 | 0.0 | 1024.9 | 1.00 |
| whyando | input-mattcl | 562.8 ± 159.5 | 0.0 | 1268.1 | 1.08 ± 0.50 |
| whyando | input-whyando | 563.7 ± 159.1 | 0.0 | 1154.9 | 1.09 ± 0.50 |
| kcen | input-whyando | 792.4 ± 128.4 | 269.9 | 1270.3 | 1.53 ± 0.61 |
| kcen | input-lanjian | 793.5 ± 169.7 | 0.0 | 1281.4 | 1.53 ± 0.65 |
| kcen | input-mattcl | 858.4 ± 206.4 | 0.0 | 1451.1 | 1.65 ± 0.72 |
| mattcl | input-lanjian | 984.9 ± 173.4 | 328.7 | 1579.4 | 1.90 ± 0.77 |
| mattcl | input-whyando | 991.8 ± 173.3 | 67.9 | 1569.1 | 1.91 ± 0.78 |
| mattcl | input-mattcl | 1027.7 ± 178.4 | 413.6 | 1575.7 | 1.98 ± 0.80 |
| lanjian | input-lanjian | 1135.5 ± 196.9 | 576.9 | 2045.1 | 2.19 ± 0.89 |
| lanjian | input-whyando | 1151.1 ± 216.1 | 448.5 | 1948.8 | 2.22 ± 0.91 |
| lanjian | input-mattcl | 1170.2 ± 199.6 | 693.1 | 1866.3 | 2.25 ± 0.91 |
| mattcl-py | input-whyando | 20347.6 ± 716.4 | 18927.0 | 22790.3 | 39.18 ± 14.42 |
| mattcl-py | input-lanjian | 20575.6 ± 621.1 | 19149.1 | 23622.5 | 39.62 ± 14.56 |
| mattcl-py | input-mattcl | 20784.7 ± 817.6 | 19578.4 | 23916.7 | 40.02 ± 14.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|