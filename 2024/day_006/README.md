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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.5 | 2.5 | 1.00 ± 0.15 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.6 | 2.7 | 1.04 ± 0.16 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.8 | 3.4 | 1.13 ± 0.18 |
| lanjian | input-mattcl | 39.9 ± 1.0 | 37.8 | 42.9 | 20.00 ± 2.33 |
| lanjian | input-lanjian | 44.1 ± 1.2 | 42.4 | 48.4 | 22.12 ± 2.58 |
| lanjian | input-kcen | 47.7 ± 1.1 | 46.2 | 50.8 | 23.90 ± 2.77 |
| lanjian | input-mikofo | 67.0 ± 1.0 | 65.3 | 70.0 | 33.59 ± 3.85 |
| mattcl-py | input-mattcl | 95.9 ± 1.1 | 93.9 | 98.2 | 48.07 ± 5.49 |
| mattcl-py | input-lanjian | 103.0 ± 1.4 | 100.6 | 105.7 | 51.63 ± 5.91 |
| mattcl-py | input-kcen | 109.5 ± 1.3 | 107.2 | 111.7 | 54.91 ± 6.27 |
| mattcl-py | input-mikofo | 144.9 ± 2.2 | 140.7 | 148.8 | 72.67 ± 8.33 |
| kcen | input-mattcl | 198.7 ± 2.7 | 194.0 | 204.5 | 99.65 ± 11.40 |
| kcen | input-lanjian | 208.4 ± 2.7 | 204.0 | 214.6 | 104.52 ± 11.94 |
| kcen | input-kcen | 245.5 ± 3.7 | 240.4 | 250.3 | 123.13 ± 14.10 |
| kcen | input-mikofo | 295.5 ± 3.6 | 290.6 | 302.7 | 148.18 ± 16.92 |
| mikofo | input-mattcl | 1425.1 ± 45.2 | 1372.9 | 1451.3 | 714.61 ± 84.25 |
| mikofo | input-lanjian | 1492.1 ± 61.4 | 1429.7 | 1552.5 | 748.21 ± 90.37 |
| mikofo | input-kcen | 1750.5 ± 44.5 | 1707.0 | 1795.9 | 877.77 ± 102.14 |
| mikofo | input-mikofo | 2123.4 ± 28.1 | 2106.3 | 2155.8 | 1064.79 ± 121.73 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|