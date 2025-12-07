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
| whyando | input-whyando | 439.2 ± 191.1 | 0.0 | 984.6 | 1.00 |
| whyando | input-lanjian | 470.1 ± 154.6 | 0.0 | 1071.2 | 1.07 ± 0.58 |
| whyando | input-mattcl | 487.4 ± 165.4 | 0.0 | 1202.7 | 1.11 ± 0.61 |
| mattcl | input-whyando | 707.1 ± 162.6 | 139.4 | 1142.5 | 1.61 ± 0.79 |
| mattcl | input-mattcl | 731.7 ± 171.5 | 25.0 | 1329.8 | 1.67 ± 0.82 |
| mattcl | input-lanjian | 732.5 ± 175.3 | 182.4 | 1333.2 | 1.67 ± 0.83 |
| kcen | input-mattcl | 848.2 ± 155.7 | 0.0 | 1200.8 | 1.93 ± 0.91 |
| kcen | input-whyando | 866.7 ± 152.2 | 224.1 | 1281.3 | 1.97 ± 0.93 |
| kcen | input-lanjian | 871.1 ± 167.6 | 0.0 | 1577.4 | 1.98 ± 0.94 |
| lanjian | input-lanjian | 1205.7 ± 179.4 | 639.2 | 1966.0 | 2.75 ± 1.26 |
| lanjian | input-whyando | 1247.6 ± 216.3 | 673.2 | 3033.0 | 2.84 ± 1.33 |
| lanjian | input-mattcl | 1274.7 ± 201.2 | 532.7 | 2072.9 | 2.90 ± 1.34 |
| mattcl-py | input-whyando | 20650.3 ± 653.7 | 19628.4 | 23898.8 | 47.02 ± 20.50 |
| mattcl-py | input-mattcl | 20753.6 ± 542.0 | 19796.9 | 23091.8 | 47.25 ± 20.59 |
| mattcl-py | input-lanjian | 20755.3 ± 722.5 | 19404.1 | 23706.3 | 47.25 ± 20.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|