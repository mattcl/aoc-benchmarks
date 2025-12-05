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
| whyando | input-whyando | 548.1 ± 236.5 | 0.0 | 1310.8 | 1.00 |
| whyando | input-lanjian | 655.6 ± 180.4 | 0.0 | 1236.7 | 1.20 ± 0.61 |
| whyando | input-mattcl | 674.4 ± 139.4 | 0.0 | 1137.4 | 1.23 ± 0.59 |
| kcen | input-lanjian | 884.1 ± 145.0 | 414.6 | 1676.6 | 1.61 ± 0.74 |
| kcen | input-whyando | 884.4 ± 147.4 | 129.7 | 1388.4 | 1.61 ± 0.75 |
| kcen | input-mattcl | 891.1 ± 175.2 | 98.6 | 1474.8 | 1.63 ± 0.77 |
| mattcl | input-whyando | 1029.2 ± 154.1 | 467.1 | 1761.3 | 1.88 ± 0.86 |
| mattcl | input-lanjian | 1122.3 ± 212.5 | 490.3 | 1754.5 | 2.05 ± 0.97 |
| mattcl | input-mattcl | 1125.0 ± 208.7 | 538.4 | 2320.7 | 2.05 ± 0.96 |
| lanjian | input-whyando | 1396.4 ± 146.7 | 680.5 | 1888.2 | 2.55 ± 1.13 |
| lanjian | input-mattcl | 1403.4 ± 179.2 | 618.2 | 2158.7 | 2.56 ± 1.15 |
| lanjian | input-lanjian | 1414.0 ± 139.1 | 618.1 | 1877.4 | 2.58 ± 1.14 |
| mattcl-py | input-mattcl | 18195.6 ± 613.2 | 17117.4 | 20894.1 | 33.20 ± 14.37 |
| mattcl-py | input-whyando | 18295.3 ± 616.2 | 17220.6 | 22029.2 | 33.38 ± 14.45 |
| mattcl-py | input-lanjian | 18425.3 ± 846.0 | 17121.9 | 22527.8 | 33.62 ± 14.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|