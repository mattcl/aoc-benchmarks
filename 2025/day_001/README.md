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
| whyando | input-mattcl | 708.4 ± 146.1 | 47.4 | 1081.8 | 1.00 |
| whyando | input-whyando | 715.6 ± 172.4 | 0.0 | 1225.9 | 1.01 ± 0.32 |
| whyando | input-lanjian | 722.8 ± 119.9 | 255.7 | 1129.3 | 1.02 ± 0.27 |
| kcen | input-lanjian | 830.4 ± 137.9 | 401.1 | 1330.5 | 1.17 ± 0.31 |
| kcen | input-whyando | 835.9 ± 174.4 | 0.0 | 1371.0 | 1.18 ± 0.35 |
| kcen | input-mattcl | 855.3 ± 101.5 | 422.5 | 1306.8 | 1.21 ± 0.29 |
| mattcl | input-lanjian | 898.2 ± 333.5 | 0.0 | 1712.0 | 1.27 ± 0.54 |
| lanjian | input-lanjian | 1002.3 ± 457.9 | 49.3 | 2035.1 | 1.41 ± 0.71 |
| mattcl | input-whyando | 1009.8 ± 176.7 | 356.7 | 1721.2 | 1.43 ± 0.39 |
| mattcl | input-mattcl | 1022.1 ± 156.2 | 353.5 | 1659.5 | 1.44 ± 0.37 |
| lanjian | input-whyando | 1308.9 ± 217.9 | 584.8 | 2027.5 | 1.85 ± 0.49 |
| lanjian | input-mattcl | 1318.6 ± 191.9 | 622.1 | 1980.8 | 1.86 ± 0.47 |
| mattcl-py | input-whyando | 18134.6 ± 579.7 | 17160.0 | 21233.3 | 25.60 ± 5.34 |
| mattcl-py | input-mattcl | 18147.7 ± 504.3 | 17138.5 | 21147.6 | 25.62 ± 5.33 |
| mattcl-py | input-lanjian | 18199.4 ± 598.9 | 17140.4 | 21072.1 | 25.69 ± 5.37 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|