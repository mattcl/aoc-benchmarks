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
| whyando | input-lanjian | 403.3 ± 170.7 | 0.0 | 1236.1 | 1.00 |
| whyando | input-mattcl | 410.3 ± 154.1 | 0.0 | 978.4 | 1.02 ± 0.58 |
| whyando | input-whyando | 414.2 ± 157.2 | 0.0 | 1001.2 | 1.03 ± 0.58 |
| mattcl | input-lanjian | 619.0 ± 178.0 | 0.0 | 1034.0 | 1.53 ± 0.79 |
| mattcl | input-whyando | 635.9 ± 165.3 | 0.0 | 1058.6 | 1.58 ± 0.78 |
| mattcl | input-mattcl | 670.4 ± 154.9 | 238.5 | 1403.6 | 1.66 ± 0.80 |
| kcen | input-whyando | 814.9 ± 151.2 | 268.3 | 1576.7 | 2.02 ± 0.93 |
| lanjian | input-lanjian | 819.4 ± 155.8 | 286.1 | 1345.8 | 2.03 ± 0.94 |
| lanjian | input-whyando | 821.7 ± 179.8 | 0.0 | 1321.9 | 2.04 ± 0.97 |
| kcen | input-lanjian | 822.2 ± 158.9 | 205.6 | 1339.1 | 2.04 ± 0.95 |
| kcen | input-mattcl | 848.6 ± 197.2 | 136.8 | 1602.7 | 2.10 ± 1.02 |
| lanjian | input-mattcl | 878.3 ± 179.9 | 248.3 | 1511.0 | 2.18 ± 1.02 |
| mattcl-py | input-whyando | 20412.8 ± 597.3 | 19132.8 | 23365.9 | 50.62 ± 21.48 |
| mattcl-py | input-mattcl | 20731.4 ± 530.2 | 19729.4 | 23629.8 | 51.41 ± 21.80 |
| mattcl-py | input-lanjian | 20830.5 ± 762.0 | 19642.0 | 24900.6 | 51.65 ± 21.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|