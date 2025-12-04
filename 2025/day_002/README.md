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
| whyando | input-whyando | 508.8 ± 195.3 | 0.0 | 911.1 | 1.00 |
| whyando | input-mattcl | 529.7 ± 184.9 | 0.0 | 1000.5 | 1.04 ± 0.54 |
| whyando | input-lanjian | 557.8 ± 154.0 | 28.3 | 1093.5 | 1.10 ± 0.52 |
| kcen | input-mattcl | 787.9 ± 148.9 | 0.0 | 1456.9 | 1.55 ± 0.66 |
| kcen | input-lanjian | 792.1 ± 121.9 | 251.5 | 1157.8 | 1.56 ± 0.64 |
| kcen | input-whyando | 808.2 ± 131.0 | 366.8 | 1197.3 | 1.59 ± 0.66 |
| mattcl | input-whyando | 892.2 ± 248.5 | 8.9 | 1228.9 | 1.75 ± 0.83 |
| mattcl | input-lanjian | 965.5 ± 167.1 | 20.5 | 1558.4 | 1.90 ± 0.80 |
| mattcl | input-mattcl | 967.3 ± 179.2 | 154.9 | 1657.7 | 1.90 ± 0.81 |
| lanjian | input-whyando | 975.0 ± 336.2 | 0.0 | 1373.8 | 1.92 ± 0.99 |
| lanjian | input-lanjian | 1113.2 ± 219.6 | 0.5 | 1882.4 | 2.19 ± 0.94 |
| lanjian | input-mattcl | 1165.2 ± 242.6 | 416.2 | 2014.0 | 2.29 ± 1.00 |
| mattcl-py | input-whyando | 20144.3 ± 429.3 | 18994.4 | 22250.6 | 39.59 ± 15.23 |
| mattcl-py | input-lanjian | 20571.1 ± 687.1 | 19514.6 | 23419.4 | 40.43 ± 15.58 |
| mattcl-py | input-mattcl | 20609.7 ± 536.6 | 19452.0 | 23797.0 | 40.51 ± 15.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|