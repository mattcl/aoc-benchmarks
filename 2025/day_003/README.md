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
| mattcl | input-lanjian | 522.2 ± 169.0 | 0.0 | 917.0 | 1.00 |
| whyando | input-mattcl | 544.3 ± 167.7 | 0.0 | 1076.8 | 1.04 ± 0.47 |
| mattcl | input-whyando | 546.5 ± 161.2 | 0.0 | 996.1 | 1.05 ± 0.46 |
| mattcl | input-mattcl | 549.7 ± 150.8 | 0.0 | 1015.5 | 1.05 ± 0.45 |
| whyando | input-whyando | 571.1 ± 163.2 | 0.0 | 996.8 | 1.09 ± 0.47 |
| whyando | input-lanjian | 585.2 ± 139.6 | 0.0 | 1001.6 | 1.12 ± 0.45 |
| kcen | input-whyando | 916.3 ± 152.0 | 260.7 | 1467.9 | 1.75 ± 0.64 |
| kcen | input-mattcl | 977.3 ± 171.3 | 539.1 | 1767.3 | 1.87 ± 0.69 |
| kcen | input-lanjian | 979.0 ± 184.5 | 0.0 | 2058.5 | 1.87 ± 0.70 |
| lanjian | input-mattcl | 4048.6 ± 298.5 | 3410.5 | 4867.9 | 7.75 ± 2.57 |
| lanjian | input-whyando | 4071.0 ± 293.5 | 3460.3 | 5088.7 | 7.80 ± 2.59 |
| lanjian | input-lanjian | 4101.8 ± 314.2 | 3417.1 | 5077.6 | 7.86 ± 2.61 |
| mattcl-py | input-mattcl | 21151.2 ± 646.4 | 20139.8 | 24263.8 | 40.51 ± 13.17 |
| mattcl-py | input-lanjian | 21191.7 ± 671.4 | 20259.9 | 24454.6 | 40.58 ± 13.20 |
| mattcl-py | input-whyando | 21404.8 ± 717.9 | 20112.5 | 24370.5 | 40.99 ± 13.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|