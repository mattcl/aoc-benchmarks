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
| mattcl | input-mattcl | 2.1 ± 0.2 | 1.5 | 2.9 | 1.00 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.7 | 2.7 | 1.03 ± 0.15 |
| mattcl | input-mikofo | 2.3 ± 0.2 | 1.9 | 4.1 | 1.13 ± 0.17 |
| mattcl | input-lanjian | 2.6 ± 1.2 | 1.6 | 8.5 | 1.27 ± 0.58 |
| lanjian | input-mattcl | 37.5 ± 1.0 | 35.7 | 40.4 | 18.24 ± 2.09 |
| lanjian | input-lanjian | 41.4 ± 1.0 | 39.7 | 45.1 | 20.10 ± 2.28 |
| lanjian | input-kcen | 44.7 ± 1.5 | 42.9 | 50.9 | 21.73 ± 2.52 |
| mattcl-py | input-mattcl | 58.3 ± 0.7 | 56.3 | 59.5 | 28.34 ± 3.17 |
| mattcl-py | input-lanjian | 59.1 ± 0.8 | 57.4 | 61.1 | 28.72 ± 3.21 |
| mattcl-py | input-kcen | 60.7 ± 0.8 | 59.1 | 62.1 | 29.51 ± 3.30 |
| lanjian | input-mikofo | 62.7 ± 1.3 | 60.5 | 66.2 | 30.50 ± 3.44 |
| mattcl-py | input-mikofo | 65.6 ± 1.1 | 63.1 | 67.7 | 31.88 ± 3.58 |
| kcen | input-mattcl | 198.4 ± 3.0 | 193.6 | 204.6 | 96.44 ± 10.81 |
| kcen | input-lanjian | 207.7 ± 7.3 | 201.2 | 231.4 | 100.95 ± 11.76 |
| kcen | input-kcen | 242.3 ± 7.0 | 228.5 | 252.1 | 117.76 ± 13.52 |
| kcen | input-mikofo | 292.2 ± 4.1 | 283.9 | 298.5 | 142.03 ± 15.90 |
| mikofo | input-mattcl | 1403.3 ± 41.9 | 1373.7 | 1451.3 | 682.03 ± 78.46 |
| mikofo | input-lanjian | 1498.3 ± 57.8 | 1463.0 | 1565.0 | 728.22 ± 85.63 |
| mikofo | input-kcen | 1700.5 ± 69.9 | 1619.9 | 1743.0 | 826.49 ± 97.90 |
| mikofo | input-mikofo | 2117.4 ± 98.6 | 2012.3 | 2207.7 | 1029.12 ± 123.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|