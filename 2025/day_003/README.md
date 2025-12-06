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
| whyando | input-mattcl | 623.0 ± 186.6 | 0.0 | 1458.7 | 1.00 |
| whyando | input-whyando | 637.8 ± 136.8 | 4.7 | 1140.0 | 1.02 ± 0.38 |
| whyando | input-lanjian | 676.6 ± 142.5 | 90.3 | 1432.1 | 1.09 ± 0.40 |
| kcen | input-mattcl | 885.7 ± 172.7 | 0.0 | 1401.3 | 1.42 ± 0.51 |
| kcen | input-whyando | 928.5 ± 115.4 | 418.4 | 1400.3 | 1.49 ± 0.48 |
| kcen | input-lanjian | 936.8 ± 158.3 | 333.7 | 1860.4 | 1.50 ± 0.52 |
| mattcl | input-lanjian | 1026.9 ± 171.9 | 405.2 | 1762.5 | 1.65 ± 0.57 |
| mattcl | input-mattcl | 1052.1 ± 193.8 | 544.3 | 1852.9 | 1.69 ± 0.59 |
| mattcl | input-whyando | 1091.0 ± 233.3 | 125.1 | 2130.9 | 1.75 ± 0.64 |
| lanjian | input-mattcl | 1312.3 ± 283.7 | 804.1 | 2419.5 | 2.11 ± 0.78 |
| lanjian | input-lanjian | 1329.0 ± 244.9 | 823.4 | 2349.1 | 2.13 ± 0.75 |
| lanjian | input-whyando | 1339.8 ± 284.5 | 777.1 | 2449.9 | 2.15 ± 0.79 |
| mattcl-py | input-lanjian | 21085.7 ± 613.2 | 20188.5 | 24347.6 | 33.84 ± 10.18 |
| mattcl-py | input-mattcl | 21110.0 ± 595.2 | 20139.0 | 23684.0 | 33.88 ± 10.19 |
| mattcl-py | input-whyando | 21191.2 ± 601.5 | 20134.9 | 24083.3 | 34.01 ± 10.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|