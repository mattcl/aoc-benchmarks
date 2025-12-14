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
| whyando | input-lanjian | 492.8 ± 191.9 | 0.0 | 1159.3 | 1.00 |
| whyando | input-mattcl | 512.6 ± 175.5 | 0.0 | 1078.7 | 1.04 ± 0.54 |
| mattcl | input-mattcl | 516.7 ± 170.6 | 0.0 | 987.6 | 1.05 ± 0.54 |
| whyando | input-whyando | 518.7 ± 171.2 | 0.0 | 1059.5 | 1.05 ± 0.54 |
| mattcl | input-whyando | 526.8 ± 178.5 | 0.0 | 1166.2 | 1.07 ± 0.55 |
| mattcl | input-lanjian | 527.5 ± 162.7 | 0.0 | 1121.6 | 1.07 ± 0.53 |
| kcen | input-lanjian | 840.4 ± 155.7 | 316.9 | 1318.4 | 1.71 ± 0.74 |
| kcen | input-whyando | 840.6 ± 162.6 | 188.9 | 1342.8 | 1.71 ± 0.74 |
| lanjian | input-whyando | 841.0 ± 193.6 | 0.0 | 1374.6 | 1.71 ± 0.77 |
| kcen | input-mattcl | 852.3 ± 149.5 | 0.0 | 1323.3 | 1.73 ± 0.74 |
| lanjian | input-mattcl | 858.6 ± 131.5 | 426.3 | 1321.8 | 1.74 ± 0.73 |
| lanjian | input-lanjian | 882.9 ± 157.9 | 238.5 | 1470.7 | 1.79 ± 0.77 |
| mattcl-py | input-lanjian | 18248.7 ± 526.8 | 17354.9 | 21358.0 | 37.03 ± 14.46 |
| mattcl-py | input-mattcl | 18261.0 ± 743.8 | 16978.1 | 21541.7 | 37.06 ± 14.51 |
| mattcl-py | input-whyando | 18317.5 ± 714.1 | 17214.4 | 21849.9 | 37.17 ± 14.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|