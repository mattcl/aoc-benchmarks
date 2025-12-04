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
| whyando | input-mattcl | 683.0 ± 161.7 | 7.7 | 1360.8 | 1.00 |
| whyando | input-lanjian | 698.7 ± 152.5 | 152.8 | 1364.9 | 1.02 ± 0.33 |
| whyando | input-whyando | 707.2 ± 119.4 | 221.7 | 922.7 | 1.04 ± 0.30 |
| kcen | input-mattcl | 799.0 ± 315.3 | 0.0 | 1586.2 | 1.17 ± 0.54 |
| kcen | input-whyando | 965.1 ± 132.4 | 184.9 | 1584.0 | 1.41 ± 0.39 |
| kcen | input-lanjian | 985.5 ± 164.9 | 391.1 | 1890.8 | 1.44 ± 0.42 |
| mattcl | input-mattcl | 1060.2 ± 230.3 | 125.1 | 1818.5 | 1.55 ± 0.50 |
| mattcl | input-whyando | 1071.2 ± 199.2 | 381.4 | 1809.4 | 1.57 ± 0.47 |
| mattcl | input-lanjian | 1150.1 ± 212.5 | 645.3 | 1955.1 | 1.68 ± 0.51 |
| lanjian | input-lanjian | 1395.1 ± 261.4 | 869.9 | 2360.5 | 2.04 ± 0.62 |
| lanjian | input-mattcl | 1418.9 ± 272.8 | 919.6 | 2696.3 | 2.08 ± 0.63 |
| lanjian | input-whyando | 1431.5 ± 292.8 | 875.9 | 2587.8 | 2.10 ± 0.66 |
| mattcl-py | input-mattcl | 20862.1 ± 501.9 | 19907.3 | 22945.2 | 30.54 ± 7.27 |
| mattcl-py | input-whyando | 21027.4 ± 591.7 | 19803.1 | 23866.6 | 30.79 ± 7.34 |
| mattcl-py | input-lanjian | 21052.9 ± 688.8 | 20017.5 | 24833.2 | 30.82 ± 7.37 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|