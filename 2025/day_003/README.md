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
| mattcl | input-lanjian | 518.5 ± 165.1 | 0.0 | 781.1 | 1.00 |
| whyando | input-lanjian | 525.4 ± 164.1 | 0.0 | 878.9 | 1.01 ± 0.45 |
| whyando | input-whyando | 532.7 ± 144.7 | 0.0 | 709.9 | 1.03 ± 0.43 |
| whyando | input-mattcl | 533.9 ± 153.3 | 0.0 | 1022.0 | 1.03 ± 0.44 |
| mattcl | input-mattcl | 547.1 ± 181.8 | 0.0 | 1063.0 | 1.06 ± 0.49 |
| mattcl | input-whyando | 552.5 ± 154.4 | 0.0 | 1060.4 | 1.07 ± 0.45 |
| kcen | input-whyando | 888.9 ± 187.1 | 0.0 | 1482.9 | 1.71 ± 0.65 |
| kcen | input-lanjian | 920.5 ± 146.2 | 0.0 | 1387.7 | 1.78 ± 0.63 |
| kcen | input-mattcl | 926.6 ± 175.8 | 170.5 | 1491.6 | 1.79 ± 0.66 |
| lanjian | input-mattcl | 4019.4 ± 333.4 | 3189.4 | 5272.3 | 7.75 ± 2.55 |
| lanjian | input-whyando | 4094.5 ± 297.6 | 3401.5 | 4949.2 | 7.90 ± 2.58 |
| lanjian | input-lanjian | 4119.7 ± 311.7 | 3202.1 | 4962.3 | 7.94 ± 2.60 |
| mattcl-py | input-mattcl | 21100.0 ± 677.8 | 19881.0 | 24111.3 | 40.69 ± 13.02 |
| mattcl-py | input-lanjian | 21142.5 ± 762.4 | 20170.7 | 24160.7 | 40.77 ± 13.07 |
| mattcl-py | input-whyando | 21282.8 ± 692.0 | 20252.0 | 24307.6 | 41.04 ± 13.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|