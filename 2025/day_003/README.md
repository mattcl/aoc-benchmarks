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
| whyando | input-mattcl | 328.0 ± 266.3 | 0.0 | 1123.0 | 1.00 |
| mattcl | input-lanjian | 547.1 ± 190.4 | 0.0 | 1066.5 | 1.67 ± 1.47 |
| whyando | input-lanjian | 574.3 ± 161.2 | 0.0 | 1021.4 | 1.75 ± 1.50 |
| whyando | input-whyando | 577.2 ± 157.2 | 0.0 | 1047.1 | 1.76 ± 1.51 |
| mattcl | input-mattcl | 578.0 ± 153.0 | 0.0 | 916.2 | 1.76 ± 1.50 |
| mattcl | input-whyando | 603.3 ± 143.0 | 0.0 | 948.5 | 1.84 ± 1.56 |
| kcen | input-lanjian | 931.8 ± 268.9 | 0.0 | 1689.7 | 2.84 ± 2.45 |
| kcen | input-whyando | 964.2 ± 181.1 | 268.0 | 1480.0 | 2.94 ± 2.45 |
| kcen | input-mattcl | 972.6 ± 167.3 | 383.5 | 1649.6 | 2.97 ± 2.46 |
| lanjian | input-lanjian | 4093.5 ± 332.1 | 3219.0 | 5264.9 | 12.48 ± 10.18 |
| lanjian | input-whyando | 4096.3 ± 317.6 | 3364.1 | 5082.6 | 12.49 ± 10.19 |
| lanjian | input-mattcl | 4117.7 ± 332.2 | 3311.4 | 4912.7 | 12.55 ± 10.24 |
| mattcl-py | input-mattcl | 21152.5 ± 666.2 | 20149.0 | 25039.5 | 64.49 ± 52.40 |
| mattcl-py | input-lanjian | 21176.0 ± 532.1 | 19777.7 | 23019.7 | 64.56 ± 52.45 |
| mattcl-py | input-whyando | 21242.7 ± 722.4 | 19987.7 | 24946.0 | 64.77 ± 52.63 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|