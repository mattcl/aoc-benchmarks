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
| whyando | input-whyando | 368.4 ± 186.0 | 0.0 | 891.7 | 1.00 |
| whyando | input-lanjian | 381.9 ± 153.9 | 0.0 | 945.6 | 1.04 ± 0.67 |
| whyando | input-mattcl | 414.2 ± 153.6 | 0.0 | 898.7 | 1.12 ± 0.70 |
| mattcl | input-whyando | 599.4 ± 179.0 | 39.2 | 1295.7 | 1.63 ± 0.95 |
| mattcl | input-lanjian | 616.6 ± 151.4 | 0.0 | 807.7 | 1.67 ± 0.94 |
| mattcl | input-mattcl | 623.7 ± 196.5 | 0.0 | 1089.3 | 1.69 ± 1.01 |
| kcen | input-mattcl | 784.4 ± 175.4 | 0.0 | 1283.3 | 2.13 ± 1.18 |
| kcen | input-whyando | 809.3 ± 170.7 | 0.0 | 1397.4 | 2.20 ± 1.20 |
| lanjian | input-mattcl | 825.2 ± 166.4 | 0.0 | 1518.8 | 2.24 ± 1.22 |
| lanjian | input-whyando | 828.2 ± 190.2 | 102.3 | 1344.1 | 2.25 ± 1.25 |
| kcen | input-lanjian | 836.7 ± 179.1 | 296.3 | 1879.5 | 2.27 ± 1.25 |
| lanjian | input-lanjian | 852.8 ± 184.0 | 104.3 | 1418.1 | 2.32 ± 1.27 |
| mattcl-py | input-whyando | 20498.9 ± 551.4 | 19456.8 | 23346.6 | 55.65 ± 28.13 |
| mattcl-py | input-mattcl | 20789.6 ± 736.3 | 19319.4 | 24243.9 | 56.44 ± 28.56 |
| mattcl-py | input-lanjian | 20810.5 ± 522.8 | 19623.9 | 23175.7 | 56.49 ± 28.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|