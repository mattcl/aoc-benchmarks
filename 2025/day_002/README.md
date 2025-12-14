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
| whyando | input-lanjian | 443.7 ± 169.0 | 0.0 | 999.7 | 1.00 |
| whyando | input-whyando | 450.1 ± 167.0 | 0.0 | 1114.1 | 1.01 ± 0.54 |
| whyando | input-mattcl | 462.5 ± 164.4 | 0.0 | 1145.7 | 1.04 ± 0.54 |
| mattcl | input-lanjian | 636.7 ± 220.3 | 0.0 | 918.2 | 1.44 ± 0.74 |
| mattcl | input-mattcl | 692.8 ± 155.9 | 0.0 | 1158.1 | 1.56 ± 0.69 |
| lanjian | input-lanjian | 696.8 ± 191.6 | 0.0 | 986.4 | 1.57 ± 0.74 |
| mattcl | input-whyando | 714.4 ± 152.0 | 136.2 | 1160.5 | 1.61 ± 0.70 |
| lanjian | input-whyando | 723.5 ± 196.6 | 0.0 | 1521.3 | 1.63 ± 0.76 |
| lanjian | input-mattcl | 752.3 ± 173.2 | 0.0 | 1213.7 | 1.70 ± 0.75 |
| kcen | input-mattcl | 815.7 ± 124.4 | 0.0 | 1070.3 | 1.84 ± 0.75 |
| kcen | input-lanjian | 817.4 ± 145.8 | 233.5 | 1194.1 | 1.84 ± 0.78 |
| kcen | input-whyando | 828.6 ± 161.1 | 0.0 | 1597.4 | 1.87 ± 0.80 |
| mattcl-py | input-whyando | 20497.4 ± 528.3 | 19569.3 | 23104.1 | 46.20 ± 17.64 |
| mattcl-py | input-mattcl | 20789.4 ± 602.9 | 19642.7 | 23520.6 | 46.86 ± 17.91 |
| mattcl-py | input-lanjian | 20973.7 ± 869.2 | 19816.0 | 24127.1 | 47.28 ± 18.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|