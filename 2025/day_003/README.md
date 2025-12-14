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
| mattcl | input-lanjian | 277.6 ± 281.6 | 0.0 | 1017.2 | 1.00 |
| whyando | input-lanjian | 373.2 ± 271.2 | 0.0 | 871.3 | 1.34 ± 1.68 |
| mattcl | input-mattcl | 549.2 ± 171.5 | 0.0 | 867.9 | 1.98 ± 2.10 |
| mattcl | input-whyando | 554.9 ± 186.8 | 5.6 | 1224.3 | 2.00 ± 2.14 |
| whyando | input-mattcl | 582.7 ± 168.3 | 0.0 | 1109.5 | 2.10 ± 2.21 |
| whyando | input-whyando | 594.1 ± 145.2 | 0.0 | 1124.0 | 2.14 ± 2.23 |
| kcen | input-whyando | 928.9 ± 182.8 | 87.8 | 1461.7 | 3.35 ± 3.46 |
| kcen | input-lanjian | 990.3 ± 139.1 | 299.8 | 1424.7 | 3.57 ± 3.65 |
| kcen | input-mattcl | 999.8 ± 234.3 | 0.0 | 1838.9 | 3.60 ± 3.75 |
| lanjian | input-mattcl | 4076.1 ± 282.9 | 3414.0 | 4718.7 | 14.68 ± 14.93 |
| lanjian | input-whyando | 4119.5 ± 323.3 | 3284.7 | 5191.8 | 14.84 ± 15.10 |
| lanjian | input-lanjian | 4140.5 ± 340.7 | 3420.6 | 6118.9 | 14.91 ± 15.18 |
| mattcl-py | input-lanjian | 21349.4 ± 783.8 | 19644.4 | 24533.2 | 76.90 ± 78.07 |
| mattcl-py | input-whyando | 21361.3 ± 716.8 | 19781.7 | 24026.8 | 76.95 ± 78.11 |
| mattcl-py | input-mattcl | 21400.7 ± 851.6 | 20010.5 | 24794.2 | 77.09 ± 78.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|