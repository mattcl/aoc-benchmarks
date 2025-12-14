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
| mattcl | input-mattcl | 507.8 ± 209.3 | 0.0 | 1207.1 | 1.00 |
| mattcl | input-whyando | 543.3 ± 139.7 | 0.0 | 732.5 | 1.07 ± 0.52 |
| whyando | input-lanjian | 549.1 ± 171.9 | 0.0 | 1126.4 | 1.08 ± 0.56 |
| mattcl | input-lanjian | 550.2 ± 143.0 | 0.0 | 765.0 | 1.08 ± 0.53 |
| whyando | input-mattcl | 559.6 ± 141.6 | 0.0 | 890.1 | 1.10 ± 0.53 |
| whyando | input-whyando | 565.6 ± 147.0 | 0.0 | 970.5 | 1.11 ± 0.54 |
| kcen | input-mattcl | 922.3 ± 172.5 | 284.0 | 1478.4 | 1.82 ± 0.82 |
| kcen | input-lanjian | 927.7 ± 164.5 | 366.3 | 1504.8 | 1.83 ± 0.82 |
| kcen | input-whyando | 954.7 ± 167.9 | 477.2 | 1505.2 | 1.88 ± 0.84 |
| lanjian | input-whyando | 4028.5 ± 319.1 | 3320.0 | 5013.0 | 7.93 ± 3.33 |
| lanjian | input-mattcl | 4058.6 ± 300.1 | 3279.6 | 5030.8 | 7.99 ± 3.35 |
| lanjian | input-lanjian | 4067.4 ± 331.6 | 3258.3 | 5112.8 | 8.01 ± 3.36 |
| mattcl-py | input-mattcl | 21258.0 ± 787.0 | 20056.4 | 26126.9 | 41.86 ± 17.32 |
| mattcl-py | input-lanjian | 21319.4 ± 810.4 | 19604.3 | 24165.5 | 41.98 ± 17.38 |
| mattcl-py | input-whyando | 21405.6 ± 653.3 | 20287.5 | 24697.4 | 42.15 ± 17.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|