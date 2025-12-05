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
| whyando | input-mattcl | 657.2 ± 175.1 | 0.0 | 1196.5 | 1.00 |
| whyando | input-whyando | 661.8 ± 159.7 | 0.0 | 1023.0 | 1.01 ± 0.36 |
| whyando | input-lanjian | 675.0 ± 107.8 | 328.8 | 867.3 | 1.03 ± 0.32 |
| kcen | input-mattcl | 907.2 ± 166.8 | 0.0 | 1438.6 | 1.38 ± 0.45 |
| kcen | input-lanjian | 967.4 ± 157.3 | 492.7 | 1479.7 | 1.47 ± 0.46 |
| kcen | input-whyando | 986.5 ± 204.0 | 62.2 | 1735.3 | 1.50 ± 0.51 |
| mattcl | input-mattcl | 1083.9 ± 197.4 | 594.6 | 1919.3 | 1.65 ± 0.53 |
| mattcl | input-lanjian | 1097.8 ± 191.2 | 459.1 | 1855.4 | 1.67 ± 0.53 |
| mattcl | input-whyando | 1099.6 ± 192.9 | 606.4 | 2538.4 | 1.67 ± 0.53 |
| lanjian | input-lanjian | 1358.7 ± 286.9 | 851.5 | 2545.0 | 2.07 ± 0.70 |
| lanjian | input-whyando | 1379.1 ± 278.6 | 910.2 | 2555.3 | 2.10 ± 0.70 |
| lanjian | input-mattcl | 1385.7 ± 290.7 | 833.9 | 3340.1 | 2.11 ± 0.71 |
| mattcl-py | input-mattcl | 21087.0 ± 609.2 | 19880.7 | 24245.3 | 32.08 ± 8.60 |
| mattcl-py | input-whyando | 21099.8 ± 599.0 | 19869.2 | 24614.8 | 32.10 ± 8.60 |
| mattcl-py | input-lanjian | 21121.5 ± 633.2 | 20119.8 | 23531.4 | 32.14 ± 8.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|