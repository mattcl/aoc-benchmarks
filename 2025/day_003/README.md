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
| mattcl | input-lanjian | 466.7 ± 262.1 | 0.0 | 2298.7 | 1.00 |
| mattcl | input-mattcl | 526.5 ± 157.0 | 0.0 | 1234.5 | 1.13 ± 0.72 |
| whyando | input-lanjian | 543.5 ± 182.0 | 0.0 | 1136.5 | 1.16 ± 0.76 |
| whyando | input-whyando | 557.2 ± 132.8 | 46.9 | 1033.5 | 1.19 ± 0.73 |
| whyando | input-mattcl | 557.6 ± 152.7 | 0.0 | 1040.9 | 1.19 ± 0.75 |
| mattcl | input-whyando | 573.0 ± 153.2 | 13.4 | 1054.1 | 1.23 ± 0.76 |
| kcen | input-lanjian | 891.9 ± 150.8 | 114.2 | 1417.3 | 1.91 ± 1.12 |
| kcen | input-whyando | 941.8 ± 131.0 | 446.6 | 1502.7 | 2.02 ± 1.17 |
| kcen | input-mattcl | 992.9 ± 150.9 | 564.3 | 1577.5 | 2.13 ± 1.24 |
| lanjian | input-lanjian | 4036.9 ± 320.8 | 3376.5 | 5044.7 | 8.65 ± 4.90 |
| lanjian | input-mattcl | 4042.2 ± 313.9 | 3385.1 | 5128.1 | 8.66 ± 4.91 |
| lanjian | input-whyando | 4060.3 ± 333.3 | 3281.7 | 5194.5 | 8.70 ± 4.94 |
| mattcl-py | input-whyando | 21155.7 ± 496.1 | 20162.5 | 23975.1 | 45.33 ± 25.47 |
| mattcl-py | input-lanjian | 21170.2 ± 760.3 | 20093.2 | 24775.0 | 45.36 ± 25.52 |
| mattcl-py | input-mattcl | 21207.9 ± 719.0 | 19970.8 | 24480.3 | 45.44 ± 25.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|