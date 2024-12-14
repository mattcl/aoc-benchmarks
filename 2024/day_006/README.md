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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.5 | 2.8 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 2.8 | 1.00 ± 0.18 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.8 | 1.03 ± 0.18 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.7 | 3.3 | 1.11 ± 0.18 |
| lanjian | input-mattcl | 38.6 ± 0.8 | 37.3 | 41.3 | 19.88 ± 2.59 |
| lanjian | input-lanjian | 42.6 ± 1.0 | 41.5 | 45.8 | 21.91 ± 2.86 |
| lanjian | input-kcen | 46.0 ± 1.1 | 44.1 | 48.9 | 23.65 ± 3.09 |
| lanjian | input-mikofo | 63.8 ± 1.3 | 61.9 | 67.2 | 32.83 ± 4.27 |
| mattcl-py | input-mattcl | 95.4 ± 1.0 | 93.8 | 97.8 | 49.09 ± 6.33 |
| mattcl-py | input-lanjian | 102.8 ± 1.4 | 100.2 | 105.3 | 52.90 ± 6.83 |
| mattcl-py | input-kcen | 109.5 ± 1.3 | 106.7 | 112.5 | 56.33 ± 7.27 |
| mattcl-py | input-mikofo | 146.3 ± 3.0 | 141.5 | 152.9 | 75.24 ± 9.79 |
| kcen | input-mattcl | 202.1 ± 2.6 | 198.0 | 206.1 | 103.97 ± 13.42 |
| kcen | input-lanjian | 209.9 ± 5.7 | 202.4 | 226.8 | 108.01 ± 14.19 |
| kcen | input-kcen | 243.1 ± 4.2 | 236.4 | 249.0 | 125.06 ± 16.21 |
| kcen | input-mikofo | 300.4 ± 5.1 | 293.1 | 308.1 | 154.55 ± 20.02 |
| mikofo | input-mattcl | 1430.0 ± 34.4 | 1396.9 | 1465.5 | 735.65 ± 96.15 |
| mikofo | input-lanjian | 1507.4 ± 18.0 | 1486.9 | 1521.0 | 775.51 ± 100.06 |
| mikofo | input-kcen | 1732.6 ± 24.2 | 1706.6 | 1754.5 | 891.38 ± 115.19 |
| mikofo | input-mikofo | 2158.2 ± 45.1 | 2111.5 | 2201.6 | 1110.30 ± 144.52 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|