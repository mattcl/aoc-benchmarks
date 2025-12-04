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
| whyando | input-mattcl | 522.0 ± 181.0 | 0.0 | 1070.9 | 1.00 |
| whyando | input-lanjian | 551.7 ± 125.7 | 116.8 | 965.6 | 1.06 ± 0.44 |
| whyando | input-whyando | 563.5 ± 136.7 | 0.0 | 1005.5 | 1.08 ± 0.46 |
| kcen | input-mattcl | 793.3 ± 136.2 | 285.2 | 1536.5 | 1.52 ± 0.59 |
| kcen | input-whyando | 796.4 ± 136.1 | 297.2 | 1224.7 | 1.53 ± 0.59 |
| kcen | input-lanjian | 805.1 ± 114.6 | 264.3 | 1306.6 | 1.54 ± 0.58 |
| mattcl | input-mattcl | 934.7 ± 156.4 | 362.1 | 1506.9 | 1.79 ± 0.69 |
| mattcl | input-lanjian | 998.1 ± 233.9 | 37.8 | 3034.0 | 1.91 ± 0.80 |
| mattcl | input-whyando | 1024.6 ± 170.4 | 550.8 | 1639.3 | 1.96 ± 0.75 |
| lanjian | input-lanjian | 1093.1 ± 197.1 | 67.4 | 1869.7 | 2.09 ± 0.82 |
| lanjian | input-whyando | 1106.1 ± 207.6 | 555.4 | 2066.8 | 2.12 ± 0.84 |
| lanjian | input-mattcl | 1125.7 ± 197.4 | 541.7 | 2140.9 | 2.16 ± 0.84 |
| mattcl-py | input-whyando | 20338.7 ± 617.6 | 19306.5 | 23143.5 | 38.96 ± 13.56 |
| mattcl-py | input-lanjian | 20599.4 ± 544.2 | 19321.6 | 23588.2 | 39.46 ± 13.72 |
| mattcl-py | input-mattcl | 20603.6 ± 671.4 | 19133.8 | 24165.5 | 39.47 ± 13.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|