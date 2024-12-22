# Day 6 benchmarks

[link to problem](https://adventofcode.com/2024/day/6)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 6)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)
- [mikofo](https://github.com/mikofo/aoc2024) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 3.5 | 1.00 |
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.4 | 2.7 | 1.00 ± 0.17 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.6 | 3.4 | 1.03 ± 0.17 |
| mattcl | input-mikofo | 2.3 ± 0.3 | 1.8 | 3.6 | 1.12 ± 0.19 |
| lanjian | input-mattcl | 39.7 ± 0.7 | 38.6 | 41.9 | 19.82 ± 2.45 |
| lanjian | input-lanjian | 44.0 ± 1.0 | 42.3 | 46.7 | 21.96 ± 2.73 |
| lanjian | input-kcen | 47.3 ± 1.0 | 46.0 | 50.3 | 23.59 ± 2.92 |
| lanjian | input-mikofo | 67.1 ± 1.0 | 65.4 | 69.7 | 33.45 ± 4.12 |
| mattcl-py | input-mattcl | 95.7 ± 1.4 | 93.3 | 100.1 | 47.72 ± 5.88 |
| mattcl-py | input-lanjian | 102.9 ± 1.4 | 100.6 | 106.4 | 51.33 ± 6.31 |
| mattcl-py | input-kcen | 110.0 ± 1.6 | 107.0 | 114.0 | 54.85 ± 6.75 |
| mattcl-py | input-mikofo | 146.4 ± 2.9 | 141.7 | 152.0 | 73.00 ± 9.04 |
| kcen | input-mattcl | 198.1 ± 2.7 | 193.4 | 203.4 | 98.81 ± 12.16 |
| kcen | input-lanjian | 208.7 ± 3.6 | 200.4 | 214.3 | 104.10 ± 12.85 |
| kcen | input-kcen | 244.5 ± 4.3 | 236.2 | 252.4 | 121.95 ± 15.06 |
| kcen | input-mikofo | 290.0 ± 4.7 | 283.6 | 298.1 | 144.63 ± 17.84 |
| mikofo | input-mattcl | 1435.3 ± 36.9 | 1392.8 | 1458.8 | 715.91 ± 89.44 |
| mikofo | input-lanjian | 1505.4 ± 37.4 | 1462.2 | 1529.2 | 750.83 ± 93.67 |
| mikofo | input-kcen | 1734.0 ± 6.9 | 1726.8 | 1740.6 | 864.88 ± 105.79 |
| mikofo | input-mikofo | 2120.4 ± 23.9 | 2100.7 | 2147.1 | 1057.61 ± 129.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|