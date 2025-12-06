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
| whyando | input-whyando | 612.2 ± 179.9 | 0.0 | 1054.6 | 1.00 |
| whyando | input-mattcl | 621.7 ± 169.2 | 0.0 | 941.7 | 1.02 ± 0.41 |
| whyando | input-lanjian | 644.4 ± 160.3 | 0.0 | 1047.7 | 1.05 ± 0.41 |
| kcen | input-whyando | 806.6 ± 211.6 | 0.0 | 1372.1 | 1.32 ± 0.52 |
| kcen | input-mattcl | 848.0 ± 160.3 | 346.9 | 1489.1 | 1.39 ± 0.48 |
| kcen | input-lanjian | 862.0 ± 136.7 | 0.0 | 1317.9 | 1.41 ± 0.47 |
| mattcl | input-whyando | 941.9 ± 321.2 | 0.0 | 1716.6 | 1.54 ± 0.69 |
| mattcl | input-mattcl | 1087.9 ± 203.8 | 442.3 | 1790.5 | 1.78 ± 0.62 |
| mattcl | input-lanjian | 1097.8 ± 191.0 | 500.7 | 2019.3 | 1.79 ± 0.61 |
| lanjian | input-whyando | 1113.8 ± 364.8 | 156.7 | 2023.9 | 1.82 ± 0.80 |
| lanjian | input-mattcl | 1375.4 ± 196.7 | 630.8 | 2088.6 | 2.25 ± 0.73 |
| lanjian | input-lanjian | 1381.0 ± 186.1 | 335.5 | 1852.4 | 2.26 ± 0.73 |
| mattcl-py | input-lanjian | 18217.1 ± 618.6 | 17189.6 | 21127.3 | 29.76 ± 8.81 |
| mattcl-py | input-whyando | 18313.5 ± 617.1 | 17305.7 | 21738.6 | 29.92 ± 8.85 |
| mattcl-py | input-mattcl | 18370.6 ± 686.2 | 17324.1 | 22242.3 | 30.01 ± 8.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|