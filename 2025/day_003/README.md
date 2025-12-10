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
| whyando | input-mattcl | 541.3 ± 163.1 | 0.0 | 821.8 | 1.00 |
| whyando | input-whyando | 544.9 ± 169.0 | 0.0 | 868.7 | 1.01 ± 0.44 |
| mattcl | input-lanjian | 561.0 ± 179.1 | 0.0 | 1155.6 | 1.04 ± 0.46 |
| mattcl | input-mattcl | 571.3 ± 174.4 | 0.0 | 1420.6 | 1.06 ± 0.45 |
| whyando | input-lanjian | 574.0 ± 157.2 | 54.3 | 1029.0 | 1.06 ± 0.43 |
| mattcl | input-whyando | 592.1 ± 160.7 | 0.0 | 995.2 | 1.09 ± 0.44 |
| kcen | input-mattcl | 954.3 ± 159.4 | 249.4 | 1484.6 | 1.76 ± 0.61 |
| kcen | input-whyando | 966.4 ± 181.8 | 328.0 | 1747.8 | 1.79 ± 0.63 |
| kcen | input-lanjian | 997.1 ± 177.0 | 336.0 | 1724.0 | 1.84 ± 0.64 |
| lanjian | input-lanjian | 4062.4 ± 291.8 | 3390.6 | 4882.5 | 7.51 ± 2.33 |
| lanjian | input-mattcl | 4068.7 ± 293.7 | 3540.6 | 5095.2 | 7.52 ± 2.33 |
| lanjian | input-whyando | 4113.3 ± 330.3 | 3283.3 | 5378.1 | 7.60 ± 2.37 |
| mattcl-py | input-lanjian | 21192.6 ± 665.3 | 20274.6 | 24288.3 | 39.15 ± 11.86 |
| mattcl-py | input-mattcl | 21321.9 ± 626.8 | 20314.4 | 24191.1 | 39.39 ± 11.93 |
| mattcl-py | input-whyando | 21420.4 ± 764.9 | 20395.2 | 24748.5 | 39.58 ± 12.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|