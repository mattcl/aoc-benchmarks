# Day 3 benchmarks

[link to problem](https://adventofcode.com/2025/day/3)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 3)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 917.8 ± 334.6 | 18.0 | 1359.4 | 1.00 |
| kcen | input-lanjian | 985.0 ± 197.2 | 96.9 | 1240.8 | 1.07 ± 0.45 |
| whyando | input-mattcl | 1006.8 ± 272.4 | 66.1 | 1500.7 | 1.10 ± 0.50 |
| kcen | input-whyando | 1010.0 ± 139.5 | 323.0 | 1239.1 | 1.10 ± 0.43 |
| kcen | input-mattcl | 1024.2 ± 114.6 | 592.8 | 1180.7 | 1.12 ± 0.43 |
| whyando | input-whyando | 1032.9 ± 175.2 | 386.3 | 1292.4 | 1.13 ± 0.45 |
| whyando | input-lanjian | 1104.5 ± 147.4 | 540.9 | 1343.0 | 1.20 ± 0.47 |
| mattcl | input-mattcl | 1119.7 ± 175.6 | 79.3 | 1320.6 | 1.22 ± 0.48 |
| mattcl | input-whyando | 1119.7 ± 225.2 | 23.7 | 1366.1 | 1.22 ± 0.51 |
| lanjian | input-lanjian | 1417.8 ± 192.1 | 950.8 | 2350.9 | 1.54 ± 0.60 |
| lanjian | input-whyando | 1423.4 ± 153.6 | 928.0 | 1792.7 | 1.55 ± 0.59 |
| lanjian | input-mattcl | 1427.1 ± 153.9 | 946.3 | 2528.9 | 1.55 ± 0.59 |
| mattcl-py | input-mattcl | 21674.7 ± 478.9 | 20690.8 | 23986.5 | 23.62 ± 8.63 |
| mattcl-py | input-whyando | 23197.4 ± 3931.8 | 20706.4 | 39766.9 | 25.28 ± 10.16 |
| mattcl-py | input-lanjian | 23344.3 ± 4471.0 | 20631.0 | 40609.8 | 25.44 ± 10.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|