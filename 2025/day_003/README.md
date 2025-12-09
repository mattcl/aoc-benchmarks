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
| mattcl | input-lanjian | 517.0 ± 199.1 | 0.0 | 1020.5 | 1.00 |
| whyando | input-lanjian | 545.8 ± 175.1 | 0.0 | 1060.9 | 1.06 ± 0.53 |
| whyando | input-whyando | 547.7 ± 179.3 | 0.0 | 1044.4 | 1.06 ± 0.54 |
| whyando | input-mattcl | 553.5 ± 200.3 | 0.0 | 1354.2 | 1.07 ± 0.57 |
| mattcl | input-mattcl | 578.8 ± 141.4 | 33.4 | 803.1 | 1.12 ± 0.51 |
| mattcl | input-whyando | 599.9 ± 159.0 | 0.0 | 1012.8 | 1.16 ± 0.54 |
| kcen | input-lanjian | 804.3 ± 283.5 | 0.0 | 1385.7 | 1.56 ± 0.81 |
| kcen | input-whyando | 930.1 ± 137.1 | 407.5 | 1506.7 | 1.80 ± 0.74 |
| kcen | input-mattcl | 1019.2 ± 175.6 | 511.8 | 1812.1 | 1.97 ± 0.83 |
| lanjian | input-lanjian | 4068.3 ± 288.4 | 3453.4 | 4997.6 | 7.87 ± 3.08 |
| lanjian | input-mattcl | 4075.3 ± 324.2 | 3274.6 | 4929.2 | 7.88 ± 3.10 |
| lanjian | input-whyando | 4106.4 ± 333.4 | 3238.3 | 5004.9 | 7.94 ± 3.13 |
| mattcl-py | input-lanjian | 21121.5 ± 575.4 | 20171.0 | 24120.3 | 40.85 ± 15.77 |
| mattcl-py | input-mattcl | 21291.0 ± 713.9 | 20287.3 | 24734.8 | 41.18 ± 15.92 |
| mattcl-py | input-whyando | 21380.1 ± 743.8 | 19861.5 | 24465.0 | 41.35 ± 15.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|