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
| kcen | input-lanjian | 787.4 ± 123.1 | 174.7 | 1085.5 | 1.00 |
| kcen | input-mattcl | 802.4 ± 119.4 | 245.0 | 1217.3 | 1.02 ± 0.22 |
| kcen | input-whyando | 816.0 ± 126.1 | 347.1 | 1346.0 | 1.04 ± 0.23 |
| whyando | input-lanjian | 869.8 ± 166.9 | 0.0 | 1380.4 | 1.10 ± 0.27 |
| whyando | input-whyando | 893.8 ± 170.0 | 243.5 | 1551.3 | 1.14 ± 0.28 |
| whyando | input-mattcl | 896.4 ± 149.6 | 347.8 | 1494.4 | 1.14 ± 0.26 |
| mattcl | input-mattcl | 943.5 ± 138.1 | 421.1 | 1618.4 | 1.20 ± 0.26 |
| mattcl | input-lanjian | 952.4 ± 155.5 | 348.9 | 1576.0 | 1.21 ± 0.27 |
| mattcl | input-whyando | 1004.5 ± 188.8 | 99.2 | 1644.6 | 1.28 ± 0.31 |
| lanjian | input-whyando | 1105.8 ± 201.3 | 384.3 | 1924.5 | 1.40 ± 0.34 |
| lanjian | input-lanjian | 1154.4 ± 254.1 | 244.3 | 3030.6 | 1.47 ± 0.40 |
| lanjian | input-mattcl | 1156.4 ± 271.1 | 450.4 | 2494.6 | 1.47 ± 0.41 |
| mattcl-py | input-whyando | 20525.1 ± 688.2 | 19135.5 | 22899.4 | 26.07 ± 4.17 |
| mattcl-py | input-lanjian | 20606.5 ± 610.1 | 19164.3 | 23728.8 | 26.17 ± 4.16 |
| mattcl-py | input-mattcl | 20659.3 ± 624.5 | 19500.3 | 23503.6 | 26.24 ± 4.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|