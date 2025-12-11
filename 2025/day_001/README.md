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
| whyando | input-whyando | 505.7 ± 165.6 | 0.0 | 1014.0 | 1.00 |
| mattcl | input-mattcl | 506.6 ± 162.6 | 0.0 | 1135.2 | 1.00 ± 0.46 |
| whyando | input-mattcl | 512.5 ± 161.8 | 0.0 | 988.5 | 1.01 ± 0.46 |
| mattcl | input-lanjian | 526.7 ± 155.7 | 0.0 | 1009.6 | 1.04 ± 0.46 |
| whyando | input-lanjian | 540.2 ± 187.5 | 0.0 | 1103.6 | 1.07 ± 0.51 |
| mattcl | input-whyando | 552.3 ± 129.8 | 43.6 | 1396.9 | 1.09 ± 0.44 |
| kcen | input-mattcl | 810.1 ± 179.1 | 0.0 | 1342.2 | 1.60 ± 0.63 |
| lanjian | input-whyando | 867.7 ± 143.4 | 334.1 | 1456.4 | 1.72 ± 0.63 |
| lanjian | input-mattcl | 881.7 ± 172.3 | 268.0 | 1423.0 | 1.74 ± 0.66 |
| kcen | input-lanjian | 883.1 ± 142.0 | 418.4 | 1327.9 | 1.75 ± 0.64 |
| kcen | input-whyando | 915.3 ± 188.0 | 384.6 | 1617.8 | 1.81 ± 0.70 |
| lanjian | input-lanjian | 926.4 ± 182.5 | 106.8 | 1561.1 | 1.83 ± 0.70 |
| mattcl-py | input-whyando | 18291.8 ± 680.1 | 17299.2 | 21605.9 | 36.17 ± 11.92 |
| mattcl-py | input-mattcl | 18435.1 ± 759.0 | 17318.9 | 21625.7 | 36.46 ± 12.03 |
| mattcl-py | input-lanjian | 18461.5 ± 731.3 | 17171.8 | 21724.0 | 36.51 ± 12.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|