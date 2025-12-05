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
| whyando | input-mattcl | 519.3 ± 258.1 | 0.0 | 838.3 | 1.00 |
| whyando | input-whyando | 651.9 ± 150.4 | 70.7 | 1337.6 | 1.26 ± 0.69 |
| whyando | input-lanjian | 667.3 ± 152.5 | 49.8 | 1038.7 | 1.29 ± 0.70 |
| kcen | input-lanjian | 894.0 ± 144.1 | 467.1 | 1571.6 | 1.72 ± 0.90 |
| kcen | input-mattcl | 896.6 ± 148.8 | 235.4 | 1422.2 | 1.73 ± 0.90 |
| kcen | input-whyando | 914.8 ± 171.5 | 232.5 | 1565.2 | 1.76 ± 0.94 |
| mattcl | input-lanjian | 1014.2 ± 122.0 | 642.3 | 1666.4 | 1.95 ± 1.00 |
| mattcl | input-mattcl | 1014.7 ± 144.5 | 141.0 | 1697.4 | 1.95 ± 1.01 |
| mattcl | input-whyando | 1046.4 ± 194.8 | 437.1 | 2146.6 | 2.02 ± 1.07 |
| lanjian | input-whyando | 1294.8 ± 266.5 | 797.5 | 2532.7 | 2.49 ± 1.34 |
| lanjian | input-lanjian | 1354.5 ± 263.4 | 830.9 | 2425.0 | 2.61 ± 1.39 |
| lanjian | input-mattcl | 1358.4 ± 278.5 | 834.5 | 2429.9 | 2.62 ± 1.41 |
| mattcl-py | input-lanjian | 21023.2 ± 716.4 | 19935.0 | 24748.6 | 40.48 ± 20.17 |
| mattcl-py | input-mattcl | 21036.1 ± 714.0 | 19596.6 | 24760.8 | 40.51 ± 20.18 |
| mattcl-py | input-whyando | 21197.9 ± 757.5 | 19890.7 | 24219.2 | 40.82 ± 20.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|