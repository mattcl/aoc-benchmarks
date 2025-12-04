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
| whyando | input-mattcl | 675.3 ± 166.3 | 0.0 | 1074.5 | 1.00 |
| whyando | input-whyando | 700.6 ± 156.4 | 104.2 | 1130.9 | 1.04 ± 0.34 |
| whyando | input-lanjian | 710.4 ± 116.8 | 271.7 | 1108.8 | 1.05 ± 0.31 |
| kcen | input-whyando | 919.0 ± 171.8 | 379.5 | 1507.3 | 1.36 ± 0.42 |
| kcen | input-lanjian | 921.6 ± 179.8 | 0.0 | 1557.3 | 1.36 ± 0.43 |
| mattcl | input-lanjian | 942.4 ± 286.6 | 36.6 | 1775.2 | 1.40 ± 0.55 |
| kcen | input-mattcl | 943.4 ± 110.5 | 569.4 | 1619.0 | 1.40 ± 0.38 |
| mattcl | input-whyando | 1013.8 ± 224.1 | 110.3 | 1783.2 | 1.50 ± 0.50 |
| mattcl | input-mattcl | 1114.5 ± 203.5 | 464.1 | 1949.6 | 1.65 ± 0.51 |
| lanjian | input-mattcl | 1345.2 ± 270.1 | 867.5 | 2416.1 | 1.99 ± 0.63 |
| lanjian | input-lanjian | 1362.7 ± 284.2 | 853.3 | 2477.8 | 2.02 ± 0.65 |
| lanjian | input-whyando | 1366.1 ± 248.8 | 850.9 | 2347.6 | 2.02 ± 0.62 |
| mattcl-py | input-mattcl | 20966.1 ± 657.5 | 19895.6 | 23448.6 | 31.05 ± 7.71 |
| mattcl-py | input-lanjian | 20995.4 ± 538.3 | 19971.3 | 23295.7 | 31.09 ± 7.70 |
| mattcl-py | input-whyando | 21241.5 ± 570.2 | 20337.5 | 24194.3 | 31.45 ± 7.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|