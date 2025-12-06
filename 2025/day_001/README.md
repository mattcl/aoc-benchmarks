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
| whyando | input-lanjian | 602.2 ± 166.3 | 0.0 | 1207.6 | 1.00 |
| whyando | input-mattcl | 623.5 ± 152.3 | 6.6 | 1064.5 | 1.04 ± 0.38 |
| whyando | input-whyando | 639.3 ± 183.1 | 0.0 | 1441.2 | 1.06 ± 0.42 |
| kcen | input-whyando | 842.8 ± 113.8 | 301.5 | 1121.3 | 1.40 ± 0.43 |
| kcen | input-mattcl | 864.2 ± 116.9 | 307.0 | 1314.4 | 1.44 ± 0.44 |
| kcen | input-lanjian | 894.8 ± 203.1 | 0.0 | 1451.0 | 1.49 ± 0.53 |
| mattcl | input-whyando | 1018.7 ± 173.2 | 378.1 | 1734.3 | 1.69 ± 0.55 |
| mattcl | input-lanjian | 1027.1 ± 191.2 | 496.3 | 1752.2 | 1.71 ± 0.57 |
| mattcl | input-mattcl | 1112.1 ± 232.8 | 607.6 | 3003.5 | 1.85 ± 0.64 |
| lanjian | input-whyando | 1365.7 ± 214.9 | 514.0 | 2171.5 | 2.27 ± 0.72 |
| lanjian | input-lanjian | 1366.4 ± 174.1 | 695.1 | 1853.3 | 2.27 ± 0.69 |
| lanjian | input-mattcl | 1371.3 ± 181.0 | 421.7 | 2013.4 | 2.28 ± 0.70 |
| mattcl-py | input-mattcl | 18244.9 ± 550.2 | 17196.9 | 21355.4 | 30.30 ± 8.42 |
| mattcl-py | input-lanjian | 18269.2 ± 595.2 | 17342.5 | 21527.8 | 30.34 ± 8.44 |
| mattcl-py | input-whyando | 18379.8 ± 724.8 | 17286.1 | 21356.9 | 30.52 ± 8.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|