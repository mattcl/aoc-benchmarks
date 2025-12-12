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
| whyando | input-whyando | 373.3 ± 161.5 | 0.0 | 895.0 | 1.00 |
| whyando | input-lanjian | 386.7 ± 182.7 | 0.0 | 1207.2 | 1.04 ± 0.66 |
| whyando | input-mattcl | 396.6 ± 149.2 | 0.0 | 944.2 | 1.06 ± 0.61 |
| mattcl | input-whyando | 603.7 ± 150.2 | 0.0 | 1096.2 | 1.62 ± 0.81 |
| mattcl | input-lanjian | 615.8 ± 143.4 | 21.9 | 943.4 | 1.65 ± 0.81 |
| mattcl | input-mattcl | 643.0 ± 140.2 | 0.0 | 1018.5 | 1.72 ± 0.83 |
| lanjian | input-mattcl | 646.5 ± 137.9 | 135.7 | 986.3 | 1.73 ± 0.84 |
| lanjian | input-whyando | 653.5 ± 142.1 | 0.0 | 1106.0 | 1.75 ± 0.85 |
| lanjian | input-lanjian | 672.0 ± 148.8 | 94.5 | 1274.3 | 1.80 ± 0.88 |
| kcen | input-whyando | 735.5 ± 210.6 | 0.0 | 1321.3 | 1.97 ± 1.02 |
| kcen | input-mattcl | 775.9 ± 156.9 | 302.9 | 1496.2 | 2.08 ± 0.99 |
| kcen | input-lanjian | 787.2 ± 127.0 | 366.5 | 1479.4 | 2.11 ± 0.97 |
| mattcl-py | input-whyando | 20410.1 ± 560.4 | 19605.2 | 23387.0 | 54.68 ± 23.71 |
| mattcl-py | input-mattcl | 20692.0 ± 585.5 | 19786.1 | 23700.0 | 55.43 ± 24.04 |
| mattcl-py | input-lanjian | 20709.4 ± 629.3 | 19634.4 | 24388.4 | 55.48 ± 24.07 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|