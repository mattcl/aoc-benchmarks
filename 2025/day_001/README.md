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
| whyando | input-whyando | 529.9 ± 172.1 | 0.0 | 1207.8 | 1.00 |
| mattcl | input-lanjian | 530.0 ± 157.8 | 0.0 | 925.4 | 1.00 ± 0.44 |
| mattcl | input-whyando | 536.4 ± 160.9 | 0.0 | 993.1 | 1.01 ± 0.45 |
| whyando | input-lanjian | 546.5 ± 176.7 | 0.0 | 1058.6 | 1.03 ± 0.47 |
| mattcl | input-mattcl | 550.8 ± 155.4 | 0.0 | 1066.6 | 1.04 ± 0.45 |
| whyando | input-mattcl | 560.3 ± 124.3 | 0.0 | 930.8 | 1.06 ± 0.42 |
| kcen | input-mattcl | 858.9 ± 138.1 | 107.6 | 1360.3 | 1.62 ± 0.59 |
| kcen | input-whyando | 879.2 ± 146.3 | 307.2 | 1619.5 | 1.66 ± 0.61 |
| kcen | input-lanjian | 894.3 ± 180.3 | 54.3 | 1612.8 | 1.69 ± 0.65 |
| lanjian | input-whyando | 1105.4 ± 178.8 | 565.3 | 1874.9 | 2.09 ± 0.76 |
| lanjian | input-lanjian | 1158.6 ± 244.2 | 113.2 | 2138.9 | 2.19 ± 0.85 |
| lanjian | input-mattcl | 1175.5 ± 236.9 | 488.5 | 2049.5 | 2.22 ± 0.85 |
| mattcl-py | input-mattcl | 18281.8 ± 573.6 | 17454.0 | 21631.2 | 34.50 ± 11.26 |
| mattcl-py | input-lanjian | 18325.6 ± 546.4 | 17402.0 | 21116.1 | 34.58 ± 11.28 |
| mattcl-py | input-whyando | 18352.4 ± 671.0 | 17197.9 | 21462.8 | 34.63 ± 11.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|