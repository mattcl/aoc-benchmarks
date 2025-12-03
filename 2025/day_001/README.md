# Day 1 benchmarks

[link to problem](https://adventofcode.com/2025/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-whyando | 715.3 ± 127.4 | 229.8 | 901.8 | 1.00 |
| whyando | input-mattcl | 724.1 ± 152.6 | 0.0 | 1127.6 | 1.01 ± 0.28 |
| whyando | input-lanjian | 796.1 ± 188.5 | 210.2 | 1497.4 | 1.11 ± 0.33 |
| kcen | input-mattcl | 828.5 ± 169.1 | 0.0 | 1324.5 | 1.16 ± 0.31 |
| kcen | input-whyando | 831.7 ± 157.0 | 85.8 | 1329.8 | 1.16 ± 0.30 |
| kcen | input-lanjian | 857.7 ± 143.6 | 0.0 | 1212.2 | 1.20 ± 0.29 |
| mattcl | input-mattcl | 1003.4 ± 191.0 | 437.8 | 1631.2 | 1.40 ± 0.37 |
| mattcl | input-lanjian | 1026.1 ± 142.5 | 482.1 | 1711.1 | 1.43 ± 0.32 |
| mattcl | input-whyando | 1037.1 ± 171.9 | 412.2 | 1705.6 | 1.45 ± 0.35 |
| lanjian | input-lanjian | 1295.9 ± 266.6 | 180.1 | 2533.2 | 1.81 ± 0.49 |
| lanjian | input-mattcl | 1328.7 ± 214.8 | 695.1 | 2106.8 | 1.86 ± 0.45 |
| lanjian | input-whyando | 1340.6 ± 200.7 | 647.3 | 2060.5 | 1.87 ± 0.44 |
| mattcl-py | input-whyando | 18167.5 ± 609.7 | 16859.5 | 21027.6 | 25.40 ± 4.60 |
| mattcl-py | input-mattcl | 18186.6 ± 675.5 | 17277.3 | 21533.6 | 25.42 ± 4.63 |
| mattcl-py | input-lanjian | 18205.3 ± 618.3 | 17172.1 | 21340.6 | 25.45 ± 4.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|