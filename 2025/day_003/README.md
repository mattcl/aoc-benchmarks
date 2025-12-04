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
| kcen | input-lanjian | 569.2 ± 411.7 | 0.0 | 1439.5 | 1.00 |
| whyando | input-mattcl | 682.6 ± 129.4 | 185.7 | 1028.8 | 1.20 ± 0.90 |
| whyando | input-lanjian | 691.8 ± 149.5 | 120.8 | 1064.2 | 1.22 ± 0.92 |
| whyando | input-whyando | 695.9 ± 147.6 | 0.0 | 1339.3 | 1.22 ± 0.92 |
| kcen | input-mattcl | 960.7 ± 144.1 | 376.1 | 1567.2 | 1.69 ± 1.25 |
| kcen | input-whyando | 970.5 ± 135.9 | 367.0 | 1541.1 | 1.71 ± 1.26 |
| mattcl | input-lanjian | 1001.6 ± 208.5 | 193.0 | 1736.8 | 1.76 ± 1.32 |
| mattcl | input-mattcl | 1069.1 ± 199.0 | 440.5 | 1773.9 | 1.88 ± 1.40 |
| mattcl | input-whyando | 1077.9 ± 152.9 | 214.1 | 1686.6 | 1.89 ± 1.40 |
| lanjian | input-mattcl | 1364.0 ± 301.1 | 840.6 | 2511.2 | 2.40 ± 1.81 |
| lanjian | input-lanjian | 1366.9 ± 253.1 | 855.1 | 2377.9 | 2.40 ± 1.79 |
| lanjian | input-whyando | 1376.1 ± 287.6 | 849.8 | 2671.3 | 2.42 ± 1.82 |
| mattcl-py | input-mattcl | 20900.4 ± 754.0 | 19771.8 | 24170.1 | 36.72 ± 26.59 |
| mattcl-py | input-lanjian | 20914.3 ± 632.4 | 19652.0 | 24393.0 | 36.75 ± 26.60 |
| mattcl-py | input-whyando | 21141.9 ± 603.6 | 20235.6 | 24161.2 | 37.15 ± 26.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|