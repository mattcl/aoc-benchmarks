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
| whyando | input-mattcl | 644.3 ± 171.4 | 0.0 | 1381.4 | 1.00 |
| whyando | input-lanjian | 675.6 ± 132.1 | 0.0 | 998.7 | 1.05 ± 0.35 |
| whyando | input-whyando | 676.7 ± 127.3 | 103.1 | 1058.4 | 1.05 ± 0.34 |
| kcen | input-mattcl | 923.0 ± 160.0 | 429.3 | 1553.2 | 1.43 ± 0.45 |
| kcen | input-lanjian | 967.7 ± 143.7 | 380.6 | 1343.6 | 1.50 ± 0.46 |
| kcen | input-whyando | 970.1 ± 168.5 | 506.7 | 1711.0 | 1.51 ± 0.48 |
| mattcl | input-lanjian | 1069.3 ± 155.5 | 576.7 | 1893.1 | 1.66 ± 0.50 |
| mattcl | input-mattcl | 1085.6 ± 224.6 | 268.4 | 2001.3 | 1.68 ± 0.57 |
| mattcl | input-whyando | 1113.4 ± 206.8 | 548.0 | 2267.8 | 1.73 ± 0.56 |
| lanjian | input-whyando | 1313.7 ± 270.0 | 831.7 | 2499.6 | 2.04 ± 0.69 |
| lanjian | input-mattcl | 1334.7 ± 288.0 | 826.2 | 2464.0 | 2.07 ± 0.71 |
| lanjian | input-lanjian | 1376.7 ± 254.4 | 895.0 | 2367.2 | 2.14 ± 0.69 |
| mattcl-py | input-lanjian | 21011.7 ± 526.2 | 19851.5 | 23406.2 | 32.61 ± 8.71 |
| mattcl-py | input-mattcl | 21073.9 ± 647.7 | 19824.7 | 23843.2 | 32.71 ± 8.76 |
| mattcl-py | input-whyando | 21238.9 ± 562.9 | 20347.6 | 23806.3 | 32.96 ± 8.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|