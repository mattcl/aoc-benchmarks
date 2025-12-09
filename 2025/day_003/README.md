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
| whyando | input-mattcl | 540.6 ± 161.7 | 0.0 | 1124.7 | 1.00 |
| whyando | input-lanjian | 546.7 ± 145.5 | 0.0 | 1024.0 | 1.01 ± 0.40 |
| mattcl | input-lanjian | 547.2 ± 170.3 | 0.0 | 1154.2 | 1.01 ± 0.44 |
| mattcl | input-mattcl | 557.2 ± 235.0 | 34.1 | 3036.2 | 1.03 ± 0.53 |
| whyando | input-whyando | 579.4 ± 145.3 | 33.3 | 1147.7 | 1.07 ± 0.42 |
| mattcl | input-whyando | 592.0 ± 167.0 | 0.0 | 1221.8 | 1.09 ± 0.45 |
| kcen | input-mattcl | 932.5 ± 168.2 | 363.9 | 1665.3 | 1.72 ± 0.60 |
| kcen | input-whyando | 942.4 ± 170.0 | 0.0 | 1732.0 | 1.74 ± 0.61 |
| kcen | input-lanjian | 954.2 ± 135.0 | 387.9 | 1438.7 | 1.76 ± 0.58 |
| lanjian | input-lanjian | 4062.5 ± 326.9 | 3200.6 | 5139.8 | 7.51 ± 2.33 |
| lanjian | input-whyando | 4099.2 ± 331.8 | 3155.1 | 5112.1 | 7.58 ± 2.35 |
| lanjian | input-mattcl | 4119.5 ± 310.4 | 3370.7 | 5123.8 | 7.62 ± 2.35 |
| mattcl-py | input-mattcl | 21033.4 ± 664.3 | 19875.1 | 24141.1 | 38.91 ± 11.70 |
| mattcl-py | input-lanjian | 21181.2 ± 784.6 | 19649.6 | 24338.1 | 39.18 ± 11.81 |
| mattcl-py | input-whyando | 21237.8 ± 730.6 | 19959.7 | 24478.5 | 39.28 ± 11.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|