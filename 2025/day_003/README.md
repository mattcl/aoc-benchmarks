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
| whyando | input-lanjian | 685.2 ± 144.8 | 23.4 | 1189.9 | 1.00 |
| whyando | input-mattcl | 690.3 ± 177.4 | 70.8 | 1116.8 | 1.01 ± 0.34 |
| whyando | input-whyando | 705.7 ± 137.2 | 0.0 | 1247.4 | 1.03 ± 0.30 |
| kcen | input-mattcl | 913.6 ± 152.5 | 404.3 | 1550.1 | 1.33 ± 0.36 |
| kcen | input-lanjian | 943.9 ± 141.3 | 409.7 | 1673.4 | 1.38 ± 0.36 |
| kcen | input-whyando | 961.3 ± 164.9 | 459.5 | 1619.3 | 1.40 ± 0.38 |
| mattcl | input-lanjian | 1016.7 ± 215.0 | 80.6 | 1630.3 | 1.48 ± 0.44 |
| mattcl | input-mattcl | 1047.2 ± 172.2 | 437.4 | 1816.2 | 1.53 ± 0.41 |
| mattcl | input-whyando | 1109.7 ± 194.0 | 362.9 | 1809.2 | 1.62 ± 0.44 |
| lanjian | input-mattcl | 1367.8 ± 311.0 | 847.5 | 2702.1 | 2.00 ± 0.62 |
| lanjian | input-whyando | 1384.0 ± 292.4 | 805.5 | 2503.1 | 2.02 ± 0.60 |
| lanjian | input-lanjian | 1385.7 ± 300.2 | 835.5 | 2469.1 | 2.02 ± 0.61 |
| mattcl-py | input-lanjian | 20876.9 ± 502.2 | 19513.7 | 23259.6 | 30.47 ± 6.48 |
| mattcl-py | input-mattcl | 20912.8 ± 657.2 | 19717.5 | 23987.1 | 30.52 ± 6.52 |
| mattcl-py | input-whyando | 21114.5 ± 562.1 | 19957.3 | 23680.2 | 30.82 ± 6.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|