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
| whyando | input-lanjian | 368.0 ± 163.6 | 0.0 | 593.2 | 1.00 |
| whyando | input-whyando | 393.8 ± 159.2 | 0.0 | 1010.9 | 1.07 ± 0.64 |
| whyando | input-mattcl | 402.5 ± 171.2 | 0.0 | 993.5 | 1.09 ± 0.67 |
| mattcl | input-lanjian | 551.0 ± 236.8 | 0.0 | 1150.5 | 1.50 ± 0.93 |
| mattcl | input-whyando | 623.3 ± 164.9 | 0.0 | 1141.3 | 1.69 ± 0.88 |
| mattcl | input-mattcl | 633.5 ± 176.9 | 0.0 | 1044.4 | 1.72 ± 0.90 |
| lanjian | input-whyando | 652.6 ± 160.4 | 0.0 | 1146.3 | 1.77 ± 0.90 |
| lanjian | input-lanjian | 653.0 ± 146.5 | 0.0 | 1257.7 | 1.77 ± 0.88 |
| lanjian | input-mattcl | 672.3 ± 159.3 | 49.4 | 1127.8 | 1.83 ± 0.92 |
| kcen | input-mattcl | 785.6 ± 130.2 | 255.6 | 1229.0 | 2.14 ± 1.01 |
| kcen | input-whyando | 792.4 ± 125.8 | 315.1 | 1217.7 | 2.15 ± 1.02 |
| kcen | input-lanjian | 792.8 ± 140.6 | 318.6 | 1306.5 | 2.15 ± 1.03 |
| mattcl-py | input-whyando | 20333.9 ± 669.6 | 19172.5 | 23600.5 | 55.26 ± 24.64 |
| mattcl-py | input-lanjian | 20590.7 ± 525.5 | 19228.5 | 23455.6 | 55.96 ± 24.92 |
| mattcl-py | input-mattcl | 20689.5 ± 591.7 | 19579.4 | 23880.6 | 56.23 ± 25.05 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|