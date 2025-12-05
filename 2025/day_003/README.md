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
| whyando | input-mattcl | 686.9 ± 140.9 | 166.1 | 1210.3 | 1.00 |
| whyando | input-whyando | 707.5 ± 148.3 | 0.0 | 1168.9 | 1.03 ± 0.30 |
| whyando | input-lanjian | 713.9 ± 145.5 | 29.2 | 1200.4 | 1.04 ± 0.30 |
| kcen | input-lanjian | 950.4 ± 196.9 | 49.5 | 1580.2 | 1.38 ± 0.40 |
| kcen | input-whyando | 980.8 ± 132.6 | 353.5 | 1479.0 | 1.43 ± 0.35 |
| kcen | input-mattcl | 1035.0 ± 185.0 | 539.9 | 2734.7 | 1.51 ± 0.41 |
| mattcl | input-mattcl | 1087.5 ± 179.4 | 639.2 | 1837.4 | 1.58 ± 0.42 |
| mattcl | input-lanjian | 1107.4 ± 202.6 | 433.1 | 1759.3 | 1.61 ± 0.44 |
| mattcl | input-whyando | 1145.3 ± 201.6 | 512.6 | 1802.6 | 1.67 ± 0.45 |
| lanjian | input-mattcl | 1376.6 ± 258.1 | 845.4 | 2453.1 | 2.00 ± 0.56 |
| lanjian | input-lanjian | 1396.6 ± 254.8 | 848.0 | 2466.4 | 2.03 ± 0.56 |
| lanjian | input-whyando | 1409.9 ± 294.1 | 896.8 | 2625.9 | 2.05 ± 0.60 |
| mattcl-py | input-mattcl | 21124.0 ± 639.9 | 19727.0 | 24519.3 | 30.75 ± 6.38 |
| mattcl-py | input-lanjian | 21141.2 ± 774.2 | 19841.2 | 24600.7 | 30.78 ± 6.41 |
| mattcl-py | input-whyando | 21354.9 ± 769.7 | 19903.6 | 24419.4 | 31.09 ± 6.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|