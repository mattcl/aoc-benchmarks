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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.5 | 2.7 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.3 | 1.5 | 3.1 | 1.01 ± 0.17 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.6 | 3.5 | 1.05 ± 0.17 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.8 | 3.1 | 1.10 ± 0.15 |
| lanjian | input-mattcl | 39.8 ± 1.1 | 38.3 | 43.4 | 19.81 ± 2.31 |
| lanjian | input-lanjian | 43.8 ± 0.9 | 42.6 | 46.8 | 21.80 ± 2.52 |
| lanjian | input-kcen | 47.5 ± 0.9 | 46.2 | 50.3 | 23.64 ± 2.72 |
| lanjian | input-mikofo | 66.9 ± 1.2 | 65.4 | 70.6 | 33.29 ± 3.83 |
| mattcl-py | input-mattcl | 95.6 ± 1.3 | 92.9 | 98.3 | 47.55 ± 5.43 |
| mattcl-py | input-lanjian | 102.6 ± 1.6 | 99.6 | 105.8 | 51.08 ± 5.85 |
| mattcl-py | input-kcen | 110.2 ± 1.8 | 106.2 | 112.9 | 54.82 ± 6.28 |
| mattcl-py | input-mikofo | 146.0 ± 4.0 | 141.2 | 154.3 | 72.67 ± 8.48 |
| kcen | input-mattcl | 200.7 ± 3.5 | 194.8 | 207.1 | 99.88 ± 11.46 |
| kcen | input-lanjian | 211.0 ± 4.0 | 204.7 | 218.7 | 105.01 ± 12.08 |
| kcen | input-kcen | 243.1 ± 4.2 | 235.4 | 248.0 | 120.97 ± 13.89 |
| kcen | input-mikofo | 290.7 ± 3.3 | 287.8 | 298.3 | 144.67 ± 16.50 |
| mikofo | input-mattcl | 1431.2 ± 52.5 | 1381.4 | 1486.0 | 712.20 ± 84.92 |
| mikofo | input-lanjian | 1514.7 ± 75.7 | 1443.3 | 1594.0 | 753.78 ± 93.45 |
| mikofo | input-kcen | 1731.1 ± 30.9 | 1698.7 | 1760.2 | 861.46 ± 98.94 |
| mikofo | input-mikofo | 2114.9 ± 41.3 | 2070.4 | 2151.9 | 1052.45 ± 121.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|