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
| mattcl | input-mattcl | 496.4 ± 169.3 | 0.0 | 805.8 | 1.00 |
| whyando | input-mattcl | 524.7 ± 197.0 | 0.0 | 1054.9 | 1.06 ± 0.54 |
| whyando | input-whyando | 539.6 ± 160.8 | 0.0 | 963.1 | 1.09 ± 0.49 |
| mattcl | input-lanjian | 541.3 ± 181.7 | 0.0 | 1031.4 | 1.09 ± 0.52 |
| mattcl | input-whyando | 561.7 ± 145.8 | 0.0 | 903.0 | 1.13 ± 0.48 |
| whyando | input-lanjian | 571.4 ± 189.8 | 0.0 | 1221.2 | 1.15 ± 0.55 |
| kcen | input-mattcl | 912.6 ± 148.6 | 344.1 | 1485.9 | 1.84 ± 0.69 |
| kcen | input-lanjian | 921.2 ± 129.9 | 415.2 | 1396.4 | 1.86 ± 0.68 |
| kcen | input-whyando | 939.9 ± 205.1 | 263.9 | 1528.3 | 1.89 ± 0.77 |
| lanjian | input-whyando | 4030.1 ± 328.8 | 3232.1 | 5171.0 | 8.12 ± 2.85 |
| lanjian | input-lanjian | 4061.4 ± 313.6 | 3342.0 | 5119.2 | 8.18 ± 2.86 |
| lanjian | input-mattcl | 4075.7 ± 307.4 | 3412.2 | 4865.8 | 8.21 ± 2.87 |
| mattcl-py | input-mattcl | 21201.5 ± 608.0 | 19966.5 | 24873.1 | 42.71 ± 14.62 |
| mattcl-py | input-lanjian | 21264.5 ± 762.0 | 20203.2 | 24348.1 | 42.83 ± 14.69 |
| mattcl-py | input-whyando | 21311.0 ± 664.6 | 20288.9 | 24411.8 | 42.93 ± 14.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|