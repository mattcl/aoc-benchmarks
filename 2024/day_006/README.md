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
| mattcl | input-lanjian | 2.0 ± 0.3 | 1.4 | 2.8 | 1.00 |
| mattcl | input-mattcl | 2.0 ± 0.3 | 1.4 | 2.7 | 1.00 ± 0.18 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.6 | 2.9 | 1.03 ± 0.16 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.9 | 3.0 | 1.10 ± 0.16 |
| lanjian | input-mattcl | 41.3 ± 1.2 | 39.7 | 44.1 | 20.62 ± 2.65 |
| lanjian | input-lanjian | 45.3 ± 1.2 | 43.3 | 49.3 | 22.59 ± 2.89 |
| lanjian | input-kcen | 48.9 ± 1.3 | 46.9 | 51.9 | 24.42 ± 3.12 |
| lanjian | input-mikofo | 69.5 ± 1.2 | 67.0 | 71.8 | 34.68 ± 4.38 |
| mattcl-py | input-mattcl | 95.6 ± 1.3 | 92.5 | 97.6 | 47.71 ± 6.00 |
| mattcl-py | input-lanjian | 103.2 ± 1.6 | 100.6 | 106.8 | 51.53 ± 6.50 |
| mattcl-py | input-kcen | 109.2 ± 1.4 | 107.3 | 113.7 | 54.54 ± 6.86 |
| mattcl-py | input-mikofo | 146.8 ± 4.2 | 141.1 | 155.5 | 73.29 ± 9.40 |
| kcen | input-mattcl | 202.3 ± 4.7 | 195.0 | 210.4 | 101.00 ± 12.86 |
| kcen | input-lanjian | 210.2 ± 3.7 | 204.4 | 217.5 | 104.94 ± 13.26 |
| kcen | input-kcen | 240.7 ± 3.8 | 235.1 | 248.2 | 120.17 ± 15.16 |
| kcen | input-mikofo | 295.0 ± 5.7 | 285.2 | 302.1 | 147.27 ± 18.65 |
| mikofo | input-mattcl | 1414.2 ± 47.2 | 1370.9 | 1464.6 | 706.04 ± 91.44 |
| mikofo | input-lanjian | 1524.9 ± 61.0 | 1464.1 | 1586.1 | 761.31 ± 100.01 |
| mikofo | input-kcen | 1737.5 ± 16.8 | 1722.1 | 1755.4 | 867.44 ± 108.86 |
| mikofo | input-mikofo | 2133.0 ± 26.3 | 2109.2 | 2161.2 | 1064.89 ± 133.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|