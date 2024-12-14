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
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.6 | 1.00 |
| mattcl | input-mattcl | 2.0 ± 0.3 | 1.5 | 3.1 | 1.00 ± 0.17 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.6 | 1.02 ± 0.16 |
| mattcl | input-mikofo | 2.2 ± 0.3 | 1.7 | 5.1 | 1.11 ± 0.21 |
| lanjian | input-mattcl | 38.7 ± 1.1 | 36.9 | 41.9 | 19.54 ± 2.28 |
| lanjian | input-lanjian | 42.6 ± 1.2 | 40.8 | 46.2 | 21.52 ± 2.51 |
| lanjian | input-kcen | 46.1 ± 1.2 | 43.9 | 50.2 | 23.32 ± 2.71 |
| lanjian | input-mikofo | 63.6 ± 1.1 | 61.6 | 65.9 | 32.13 ± 3.68 |
| mattcl-py | input-mattcl | 95.8 ± 1.3 | 93.7 | 99.5 | 48.43 ± 5.53 |
| mattcl-py | input-lanjian | 102.8 ± 1.6 | 100.0 | 106.3 | 51.94 ± 5.94 |
| mattcl-py | input-kcen | 110.0 ± 1.5 | 107.4 | 113.2 | 55.58 ± 6.34 |
| mattcl-py | input-mikofo | 145.8 ± 3.3 | 141.4 | 153.4 | 73.68 ± 8.51 |
| kcen | input-mattcl | 200.4 ± 4.2 | 191.4 | 208.6 | 101.30 ± 11.67 |
| kcen | input-lanjian | 209.1 ± 3.9 | 204.9 | 216.1 | 105.67 ± 12.13 |
| kcen | input-kcen | 244.3 ± 4.4 | 236.2 | 249.5 | 123.47 ± 14.16 |
| kcen | input-mikofo | 294.1 ± 4.3 | 287.7 | 301.6 | 148.64 ± 16.98 |
| mikofo | input-mattcl | 1464.4 ± 71.3 | 1382.1 | 1505.8 | 740.10 ± 91.26 |
| mikofo | input-lanjian | 1518.3 ± 59.1 | 1450.1 | 1552.8 | 767.37 ± 91.92 |
| mikofo | input-kcen | 1725.2 ± 37.9 | 1683.3 | 1757.1 | 871.90 ± 100.61 |
| mikofo | input-mikofo | 2137.2 ± 6.1 | 2131.6 | 2143.8 | 1080.13 ± 122.41 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|