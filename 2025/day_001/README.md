# Day 1 benchmarks

[link to problem](https://adventofcode.com/2025/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-mattcl | 471.3 ± 172.7 | 0.0 | 960.6 | 1.00 |
| whyando | input-whyando | 491.2 ± 172.6 | 0.0 | 1527.9 | 1.04 ± 0.53 |
| mattcl | input-whyando | 509.4 ± 219.1 | 0.0 | 2626.5 | 1.08 ± 0.61 |
| mattcl | input-mattcl | 528.9 ± 152.7 | 0.0 | 955.9 | 1.12 ± 0.52 |
| whyando | input-lanjian | 534.3 ± 147.8 | 0.0 | 953.5 | 1.13 ± 0.52 |
| mattcl | input-lanjian | 540.2 ± 171.0 | 0.0 | 999.9 | 1.15 ± 0.56 |
| kcen | input-whyando | 829.1 ± 144.8 | 146.9 | 1329.4 | 1.76 ± 0.71 |
| kcen | input-lanjian | 857.1 ± 154.5 | 7.0 | 1470.3 | 1.82 ± 0.74 |
| kcen | input-mattcl | 882.7 ± 163.9 | 376.0 | 1724.7 | 1.87 ± 0.77 |
| lanjian | input-whyando | 1075.9 ± 202.4 | 473.4 | 1771.9 | 2.28 ± 0.94 |
| lanjian | input-mattcl | 1113.6 ± 215.2 | 421.9 | 1968.7 | 2.36 ± 0.98 |
| lanjian | input-lanjian | 1151.5 ± 247.8 | 389.5 | 2234.8 | 2.44 ± 1.04 |
| mattcl-py | input-whyando | 18189.6 ± 607.9 | 17189.2 | 21517.5 | 38.60 ± 14.21 |
| mattcl-py | input-mattcl | 18211.6 ± 616.9 | 17343.2 | 21562.2 | 38.64 ± 14.22 |
| mattcl-py | input-lanjian | 18452.5 ± 730.0 | 17500.2 | 21640.1 | 39.15 ± 14.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|