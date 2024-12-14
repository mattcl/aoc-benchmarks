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
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.6 | 2.7 | 1.00 |
| mattcl | input-mattcl | 2.0 ± 0.3 | 1.5 | 4.1 | 1.00 ± 0.18 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.9 | 1.02 ± 0.16 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.7 | 3.7 | 1.10 ± 0.17 |
| lanjian | input-mattcl | 41.4 ± 1.3 | 39.6 | 46.3 | 20.74 ± 2.51 |
| lanjian | input-lanjian | 45.4 ± 1.1 | 43.3 | 48.0 | 22.73 ± 2.72 |
| lanjian | input-kcen | 48.9 ± 1.5 | 46.7 | 53.3 | 24.47 ± 2.97 |
| lanjian | input-mikofo | 68.5 ± 1.2 | 66.6 | 71.4 | 34.28 ± 4.06 |
| mattcl-py | input-mattcl | 95.7 ± 1.2 | 93.4 | 97.7 | 47.90 ± 5.65 |
| mattcl-py | input-lanjian | 102.8 ± 1.5 | 99.9 | 106.6 | 51.49 ± 6.08 |
| mattcl-py | input-kcen | 109.7 ± 2.1 | 106.0 | 114.5 | 54.93 ± 6.52 |
| mattcl-py | input-mikofo | 146.7 ± 3.9 | 140.5 | 154.4 | 73.47 ± 8.83 |
| kcen | input-mattcl | 198.9 ± 3.1 | 193.3 | 204.8 | 99.56 ± 11.77 |
| kcen | input-lanjian | 207.8 ± 2.8 | 203.4 | 214.5 | 104.04 ± 12.27 |
| kcen | input-kcen | 240.1 ± 3.2 | 236.2 | 248.0 | 120.21 ± 14.18 |
| kcen | input-mikofo | 292.0 ± 5.5 | 282.0 | 298.9 | 146.20 ± 17.36 |
| mikofo | input-mattcl | 1436.4 ± 38.8 | 1392.7 | 1466.9 | 719.11 ± 86.50 |
| mikofo | input-lanjian | 1505.7 ± 42.3 | 1457.5 | 1536.9 | 753.80 ± 90.86 |
| mikofo | input-kcen | 1745.5 ± 30.8 | 1711.3 | 1771.0 | 873.86 ± 103.58 |
| mikofo | input-mikofo | 2117.1 ± 2.3 | 2114.9 | 2119.5 | 1059.88 ± 124.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|