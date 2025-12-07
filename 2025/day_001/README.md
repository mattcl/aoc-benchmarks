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
| mattcl | input-mattcl | 259.5 ± 260.1 | 0.0 | 1222.2 | 1.00 |
| whyando | input-lanjian | 325.4 ± 234.9 | 0.0 | 964.3 | 1.25 ± 1.55 |
| whyando | input-mattcl | 428.8 ± 216.2 | 0.0 | 854.5 | 1.65 ± 1.85 |
| whyando | input-whyando | 451.5 ± 169.9 | 0.0 | 972.0 | 1.74 ± 1.86 |
| mattcl | input-whyando | 520.6 ± 157.4 | 0.0 | 1087.8 | 2.01 ± 2.10 |
| mattcl | input-lanjian | 532.2 ± 167.9 | 0.0 | 1187.0 | 2.05 ± 2.16 |
| kcen | input-mattcl | 811.5 ± 240.0 | 0.0 | 1361.2 | 3.13 ± 3.27 |
| kcen | input-lanjian | 837.3 ± 162.1 | 0.0 | 1331.9 | 3.23 ± 3.29 |
| kcen | input-whyando | 857.1 ± 161.1 | 292.4 | 1519.3 | 3.30 ± 3.37 |
| lanjian | input-mattcl | 1135.4 ± 405.8 | 114.0 | 2316.4 | 4.38 ± 4.66 |
| lanjian | input-whyando | 1334.7 ± 203.9 | 539.4 | 2116.7 | 5.14 ± 5.22 |
| lanjian | input-lanjian | 1352.0 ± 184.3 | 612.9 | 1976.9 | 5.21 ± 5.27 |
| mattcl-py | input-mattcl | 18272.4 ± 601.3 | 16914.4 | 21460.9 | 70.42 ± 70.62 |
| mattcl-py | input-lanjian | 18286.7 ± 548.6 | 17256.9 | 22472.8 | 70.48 ± 70.67 |
| mattcl-py | input-whyando | 18441.4 ± 726.5 | 17174.9 | 21963.3 | 71.08 ± 71.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|