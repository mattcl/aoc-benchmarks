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
| whyando | input-lanjian | 645.9 ± 180.7 | 0.0 | 1183.5 | 1.00 |
| whyando | input-mattcl | 654.6 ± 164.3 | 0.0 | 899.0 | 1.01 ± 0.38 |
| whyando | input-whyando | 680.7 ± 172.3 | 0.0 | 1289.9 | 1.05 ± 0.40 |
| kcen | input-whyando | 910.8 ± 182.2 | 0.0 | 1635.8 | 1.41 ± 0.49 |
| kcen | input-lanjian | 944.7 ± 142.9 | 336.0 | 1450.7 | 1.46 ± 0.47 |
| kcen | input-mattcl | 967.8 ± 214.3 | 49.8 | 2584.5 | 1.50 ± 0.53 |
| mattcl | input-mattcl | 978.6 ± 297.6 | 0.0 | 1776.9 | 1.52 ± 0.63 |
| mattcl | input-whyando | 1027.1 ± 156.8 | 495.1 | 1739.3 | 1.59 ± 0.51 |
| mattcl | input-lanjian | 1088.5 ± 209.2 | 104.6 | 2008.9 | 1.69 ± 0.57 |
| lanjian | input-lanjian | 1368.1 ± 308.0 | 790.1 | 2496.5 | 2.12 ± 0.76 |
| lanjian | input-mattcl | 1370.9 ± 276.2 | 827.9 | 2364.5 | 2.12 ± 0.73 |
| lanjian | input-whyando | 1380.3 ± 220.7 | 895.1 | 2368.5 | 2.14 ± 0.69 |
| mattcl-py | input-mattcl | 21051.1 ± 600.8 | 19999.7 | 23814.4 | 32.59 ± 9.17 |
| mattcl-py | input-lanjian | 21149.6 ± 706.7 | 20178.1 | 24759.4 | 32.74 ± 9.23 |
| mattcl-py | input-whyando | 21201.5 ± 736.4 | 19750.7 | 24436.3 | 32.82 ± 9.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|