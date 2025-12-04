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
| whyando | input-mattcl | 530.2 ± 167.2 | 0.0 | 957.6 | 1.00 |
| whyando | input-lanjian | 547.1 ± 148.3 | 0.0 | 982.7 | 1.03 ± 0.43 |
| whyando | input-whyando | 557.2 ± 136.9 | 88.9 | 950.5 | 1.05 ± 0.42 |
| kcen | input-lanjian | 762.7 ± 143.0 | 0.0 | 1212.3 | 1.44 ± 0.53 |
| kcen | input-whyando | 773.7 ± 156.1 | 238.9 | 1253.8 | 1.46 ± 0.55 |
| kcen | input-mattcl | 802.6 ± 132.4 | 289.2 | 1291.6 | 1.51 ± 0.54 |
| mattcl | input-whyando | 954.3 ± 163.1 | 129.4 | 1538.1 | 1.80 ± 0.65 |
| mattcl | input-lanjian | 970.1 ± 159.0 | 344.0 | 1538.8 | 1.83 ± 0.65 |
| mattcl | input-mattcl | 990.7 ± 160.4 | 404.1 | 1603.8 | 1.87 ± 0.66 |
| lanjian | input-whyando | 1058.8 ± 186.4 | 472.4 | 1873.0 | 2.00 ± 0.72 |
| lanjian | input-mattcl | 1108.2 ± 185.9 | 450.4 | 1831.4 | 2.09 ± 0.75 |
| lanjian | input-lanjian | 1154.8 ± 214.9 | 563.4 | 1846.0 | 2.18 ± 0.80 |
| mattcl-py | input-whyando | 20100.3 ± 542.1 | 18928.1 | 23375.9 | 37.91 ± 12.00 |
| mattcl-py | input-mattcl | 20558.4 ± 655.8 | 19471.3 | 23865.6 | 38.77 ± 12.29 |
| mattcl-py | input-lanjian | 20572.2 ± 667.8 | 19219.9 | 23663.9 | 38.80 ± 12.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|