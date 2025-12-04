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
| whyando | input-mattcl | 648.3 ± 137.9 | 0.0 | 1007.1 | 1.00 |
| whyando | input-whyando | 658.6 ± 172.9 | 0.0 | 1087.2 | 1.02 ± 0.34 |
| whyando | input-lanjian | 660.5 ± 168.6 | 89.3 | 1467.2 | 1.02 ± 0.34 |
| kcen | input-mattcl | 879.1 ± 152.4 | 458.4 | 1485.9 | 1.36 ± 0.37 |
| kcen | input-whyando | 887.1 ± 139.5 | 342.5 | 1393.2 | 1.37 ± 0.36 |
| kcen | input-lanjian | 915.6 ± 172.9 | 410.0 | 1733.9 | 1.41 ± 0.40 |
| mattcl | input-mattcl | 1044.0 ± 188.3 | 549.6 | 1822.0 | 1.61 ± 0.45 |
| mattcl | input-lanjian | 1060.9 ± 192.5 | 553.5 | 1890.4 | 1.64 ± 0.46 |
| mattcl | input-whyando | 1062.3 ± 208.5 | 315.0 | 1943.5 | 1.64 ± 0.47 |
| lanjian | input-lanjian | 1305.1 ± 261.1 | 801.3 | 2385.5 | 2.01 ± 0.59 |
| lanjian | input-whyando | 1342.6 ± 298.7 | 811.4 | 2616.4 | 2.07 ± 0.64 |
| lanjian | input-mattcl | 1343.8 ± 264.1 | 925.2 | 2464.6 | 2.07 ± 0.60 |
| mattcl-py | input-mattcl | 20918.3 ± 532.1 | 19979.5 | 23708.4 | 32.27 ± 6.91 |
| mattcl-py | input-lanjian | 20941.4 ± 620.3 | 20001.2 | 23563.4 | 32.30 ± 6.94 |
| mattcl-py | input-whyando | 21174.0 ± 575.1 | 20235.5 | 24168.3 | 32.66 ± 7.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|