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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.4 | 2.9 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.7 | 1.02 ± 0.18 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.5 | 1.03 ± 0.17 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.7 | 3.2 | 1.11 ± 0.18 |
| lanjian | input-mattcl | 41.0 ± 1.0 | 38.9 | 43.8 | 21.18 ± 2.76 |
| lanjian | input-lanjian | 45.4 ± 1.3 | 42.4 | 48.2 | 23.49 ± 3.07 |
| lanjian | input-kcen | 48.9 ± 1.0 | 47.2 | 51.9 | 25.31 ± 3.28 |
| lanjian | input-mikofo | 68.8 ± 1.3 | 66.4 | 71.5 | 35.60 ± 4.60 |
| mattcl-py | input-mattcl | 95.7 ± 1.2 | 93.4 | 98.8 | 49.47 ± 6.35 |
| mattcl-py | input-lanjian | 102.7 ± 1.5 | 99.4 | 105.5 | 53.09 ± 6.82 |
| mattcl-py | input-kcen | 109.6 ± 1.8 | 107.1 | 116.1 | 56.66 ± 7.30 |
| mattcl-py | input-mikofo | 146.1 ± 3.3 | 141.1 | 152.6 | 75.55 ± 9.80 |
| kcen | input-mattcl | 198.1 ± 4.0 | 192.4 | 206.1 | 102.44 ± 13.25 |
| kcen | input-lanjian | 207.1 ± 4.8 | 201.1 | 220.2 | 107.11 ± 13.90 |
| kcen | input-kcen | 238.9 ± 2.7 | 234.0 | 243.3 | 123.53 ± 15.84 |
| kcen | input-mikofo | 290.7 ± 5.5 | 280.5 | 299.0 | 150.37 ± 19.41 |
| mikofo | input-mattcl | 1422.2 ± 21.1 | 1399.6 | 1441.5 | 735.56 ± 94.56 |
| mikofo | input-lanjian | 1500.6 ± 55.5 | 1463.8 | 1564.4 | 776.06 ± 103.17 |
| mikofo | input-kcen | 1729.0 ± 30.7 | 1694.0 | 1751.9 | 894.21 ± 115.29 |
| mikofo | input-mikofo | 2119.9 ± 8.8 | 2110.9 | 2128.5 | 1096.40 ± 140.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|