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
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 2.5 | 1.00 |
| mattcl | input-mattcl | 1.9 ± 0.3 | 1.4 | 3.1 | 1.00 ± 0.19 |
| mattcl | input-kcen | 1.9 ± 0.2 | 1.5 | 2.7 | 1.02 ± 0.17 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.8 | 2.8 | 1.11 ± 0.17 |
| lanjian | input-mattcl | 41.1 ± 1.2 | 38.8 | 44.3 | 21.41 ± 2.83 |
| lanjian | input-lanjian | 44.9 ± 1.0 | 43.5 | 48.1 | 23.41 ± 3.06 |
| lanjian | input-kcen | 48.6 ± 1.2 | 46.8 | 52.2 | 25.31 ± 3.32 |
| lanjian | input-mikofo | 69.2 ± 1.3 | 66.9 | 74.4 | 36.06 ± 4.69 |
| mattcl-py | input-mattcl | 95.8 ± 1.1 | 93.7 | 98.6 | 49.89 ± 6.45 |
| mattcl-py | input-lanjian | 102.7 ± 1.7 | 98.9 | 106.0 | 53.50 ± 6.94 |
| mattcl-py | input-kcen | 111.8 ± 2.5 | 108.0 | 117.3 | 58.24 ± 7.61 |
| mattcl-py | input-mikofo | 145.3 ± 3.4 | 141.7 | 154.4 | 75.73 ± 9.90 |
| kcen | input-mattcl | 201.1 ± 4.0 | 194.5 | 209.9 | 104.79 ± 13.64 |
| kcen | input-lanjian | 206.9 ± 4.9 | 197.4 | 217.0 | 107.77 ± 14.10 |
| kcen | input-kcen | 239.3 ± 3.6 | 236.0 | 248.1 | 124.68 ± 16.15 |
| kcen | input-mikofo | 294.8 ± 3.5 | 289.1 | 300.5 | 153.60 ± 19.85 |
| mikofo | input-mattcl | 1407.0 ± 25.7 | 1381.5 | 1433.0 | 733.06 ± 95.26 |
| mikofo | input-lanjian | 1498.0 ± 39.9 | 1452.0 | 1523.2 | 780.47 ± 102.54 |
| mikofo | input-kcen | 1736.0 ± 11.7 | 1724.0 | 1747.5 | 904.45 ± 116.52 |
| mikofo | input-mikofo | 2140.9 ± 41.6 | 2104.9 | 2186.4 | 1115.41 ± 145.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|