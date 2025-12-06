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
| whyando | input-lanjian | 609.7 ± 232.2 | 0.0 | 1023.5 | 1.00 |
| whyando | input-mattcl | 683.2 ± 146.6 | 206.2 | 994.7 | 1.12 ± 0.49 |
| whyando | input-whyando | 713.6 ± 111.9 | 310.9 | 1117.3 | 1.17 ± 0.48 |
| kcen | input-whyando | 946.1 ± 168.0 | 359.8 | 1504.5 | 1.55 ± 0.65 |
| kcen | input-mattcl | 949.6 ± 136.9 | 314.2 | 1153.0 | 1.56 ± 0.63 |
| kcen | input-lanjian | 966.3 ± 210.2 | 338.8 | 2899.5 | 1.58 ± 0.70 |
| mattcl | input-lanjian | 1061.2 ± 187.2 | 559.7 | 1776.9 | 1.74 ± 0.73 |
| mattcl | input-mattcl | 1062.9 ± 192.2 | 507.4 | 1779.3 | 1.74 ± 0.73 |
| mattcl | input-whyando | 1064.2 ± 189.9 | 543.1 | 1747.0 | 1.75 ± 0.73 |
| lanjian | input-whyando | 1361.6 ± 255.1 | 865.9 | 2356.4 | 2.23 ± 0.95 |
| lanjian | input-mattcl | 1407.7 ± 253.5 | 849.9 | 2617.1 | 2.31 ± 0.97 |
| lanjian | input-lanjian | 1417.3 ± 253.6 | 873.2 | 2456.4 | 2.32 ± 0.98 |
| mattcl-py | input-lanjian | 21143.2 ± 694.5 | 19849.1 | 25043.4 | 34.68 ± 13.26 |
| mattcl-py | input-mattcl | 21160.2 ± 558.1 | 20101.1 | 23558.1 | 34.71 ± 13.25 |
| mattcl-py | input-whyando | 21287.8 ± 653.4 | 20076.3 | 24208.7 | 34.92 ± 13.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|