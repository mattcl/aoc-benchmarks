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
| whyando | input-mattcl | 495.5 ± 172.6 | 0.0 | 913.7 | 1.00 |
| mattcl | input-mattcl | 517.2 ± 180.1 | 0.0 | 952.3 | 1.04 ± 0.51 |
| mattcl | input-whyando | 526.7 ± 160.9 | 0.0 | 1082.2 | 1.06 ± 0.49 |
| whyando | input-whyando | 529.2 ± 132.0 | 43.5 | 1011.9 | 1.07 ± 0.46 |
| whyando | input-lanjian | 541.9 ± 143.4 | 0.0 | 958.0 | 1.09 ± 0.48 |
| mattcl | input-lanjian | 551.3 ± 180.7 | 0.0 | 1139.9 | 1.11 ± 0.53 |
| kcen | input-lanjian | 845.6 ± 147.9 | 300.7 | 1332.6 | 1.71 ± 0.67 |
| kcen | input-mattcl | 864.9 ± 169.2 | 0.0 | 1367.6 | 1.75 ± 0.70 |
| kcen | input-whyando | 866.3 ± 147.1 | 302.2 | 1326.9 | 1.75 ± 0.68 |
| lanjian | input-lanjian | 1142.0 ± 181.2 | 167.4 | 1762.7 | 2.30 ± 0.88 |
| lanjian | input-mattcl | 1149.9 ± 182.7 | 518.1 | 1810.2 | 2.32 ± 0.89 |
| lanjian | input-whyando | 1157.6 ± 207.6 | 627.8 | 1923.7 | 2.34 ± 0.92 |
| mattcl-py | input-mattcl | 18331.0 ± 571.0 | 17635.7 | 21608.8 | 36.99 ± 12.93 |
| mattcl-py | input-whyando | 18368.0 ± 531.9 | 17284.2 | 20811.1 | 37.07 ± 12.95 |
| mattcl-py | input-lanjian | 18453.7 ± 622.3 | 17409.1 | 21662.2 | 37.24 ± 13.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|