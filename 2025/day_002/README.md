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
| kcen | input-mattcl | 361.4 ± 296.1 | 0.0 | 1123.5 | 1.00 |
| whyando | input-whyando | 512.8 ± 181.2 | 0.0 | 1022.5 | 1.42 ± 1.27 |
| whyando | input-lanjian | 543.9 ± 149.1 | 28.6 | 984.5 | 1.50 ± 1.30 |
| whyando | input-mattcl | 559.3 ± 130.5 | 80.4 | 1031.6 | 1.55 ± 1.32 |
| lanjian | input-mattcl | 709.4 ± 409.6 | 0.0 | 2573.0 | 1.96 ± 1.97 |
| kcen | input-lanjian | 769.2 ± 128.6 | 288.1 | 1067.2 | 2.13 ± 1.78 |
| kcen | input-whyando | 777.8 ± 153.3 | 0.0 | 1480.1 | 2.15 ± 1.81 |
| mattcl | input-mattcl | 971.7 ± 196.0 | 297.9 | 1627.2 | 2.69 ± 2.27 |
| mattcl | input-whyando | 988.6 ± 169.7 | 437.8 | 1543.3 | 2.74 ± 2.29 |
| mattcl | input-lanjian | 998.1 ± 179.2 | 189.1 | 1983.0 | 2.76 ± 2.32 |
| lanjian | input-whyando | 1111.8 ± 166.5 | 571.8 | 1838.7 | 3.08 ± 2.56 |
| lanjian | input-lanjian | 1120.0 ± 184.3 | 574.2 | 1799.8 | 3.10 ± 2.59 |
| mattcl-py | input-whyando | 20192.8 ± 493.6 | 19032.7 | 21927.5 | 55.88 ± 45.81 |
| mattcl-py | input-mattcl | 20534.7 ± 525.5 | 19262.0 | 22571.6 | 56.82 ± 46.58 |
| mattcl-py | input-lanjian | 20597.6 ± 710.2 | 19474.9 | 23696.2 | 57.00 ± 46.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|