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
| whyando | input-mattcl | 348.8 ± 155.2 | 0.0 | 886.8 | 1.00 |
| whyando | input-whyando | 359.7 ± 146.1 | 0.0 | 872.9 | 1.03 ± 0.62 |
| whyando | input-lanjian | 368.7 ± 154.5 | 0.0 | 950.4 | 1.06 ± 0.65 |
| mattcl | input-lanjian | 565.1 ± 174.1 | 0.0 | 982.9 | 1.62 ± 0.88 |
| mattcl | input-whyando | 606.5 ± 168.2 | 0.0 | 1072.1 | 1.74 ± 0.91 |
| lanjian | input-lanjian | 621.0 ± 152.6 | 0.0 | 1041.6 | 1.78 ± 0.90 |
| lanjian | input-whyando | 625.0 ± 160.0 | 33.9 | 1433.1 | 1.79 ± 0.92 |
| lanjian | input-mattcl | 642.1 ± 158.6 | 0.0 | 1052.2 | 1.84 ± 0.94 |
| mattcl | input-mattcl | 644.6 ± 127.5 | 113.2 | 1021.7 | 1.85 ± 0.90 |
| kcen | input-mattcl | 749.8 ± 185.1 | 0.0 | 1500.0 | 2.15 ± 1.09 |
| kcen | input-whyando | 759.0 ± 150.6 | 0.0 | 1260.3 | 2.18 ± 1.06 |
| kcen | input-lanjian | 794.7 ± 155.6 | 333.6 | 1524.0 | 2.28 ± 1.11 |
| mattcl-py | input-whyando | 20337.1 ± 560.8 | 18944.8 | 22708.0 | 58.30 ± 25.99 |
| mattcl-py | input-lanjian | 20569.1 ± 461.2 | 19596.6 | 22636.6 | 58.97 ± 26.27 |
| mattcl-py | input-mattcl | 20586.3 ± 550.4 | 19523.8 | 23330.1 | 59.01 ± 26.31 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|