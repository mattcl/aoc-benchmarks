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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.5 | 2.9 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.8 | 1.01 ± 0.18 |
| mattcl | input-kcen | 2.0 ± 0.3 | 1.5 | 3.4 | 1.05 ± 0.19 |
| mattcl | input-mikofo | 2.2 ± 0.3 | 1.8 | 4.5 | 1.13 ± 0.20 |
| lanjian | input-mattcl | 39.2 ± 1.1 | 37.7 | 42.5 | 20.20 ± 2.64 |
| lanjian | input-lanjian | 43.4 ± 0.9 | 41.7 | 46.3 | 22.33 ± 2.89 |
| lanjian | input-kcen | 47.1 ± 1.3 | 45.2 | 50.4 | 24.24 ± 3.16 |
| mattcl-py | input-mattcl | 57.6 ± 0.7 | 56.1 | 59.8 | 29.68 ± 3.80 |
| mattcl-py | input-lanjian | 58.6 ± 0.6 | 57.0 | 60.0 | 30.17 ± 3.86 |
| mattcl-py | input-kcen | 60.7 ± 0.7 | 59.3 | 62.2 | 31.26 ± 4.00 |
| mattcl-py | input-mikofo | 65.1 ± 0.8 | 63.4 | 67.1 | 33.55 ± 4.30 |
| lanjian | input-mikofo | 66.4 ± 1.2 | 64.6 | 68.7 | 34.19 ± 4.40 |
| kcen | input-mattcl | 199.3 ± 5.1 | 190.3 | 212.3 | 102.67 ± 13.35 |
| kcen | input-lanjian | 208.6 ± 3.7 | 202.4 | 214.3 | 107.42 ± 13.83 |
| kcen | input-kcen | 245.3 ± 3.9 | 240.3 | 252.9 | 126.34 ± 16.24 |
| kcen | input-mikofo | 296.0 ± 16.5 | 284.9 | 341.7 | 152.44 ± 21.22 |
| mikofo | input-mattcl | 1362.9 ± 35.7 | 1341.2 | 1404.1 | 701.96 ± 91.39 |
| mikofo | input-lanjian | 1454.8 ± 28.4 | 1423.9 | 1479.7 | 749.28 ± 96.67 |
| mikofo | input-kcen | 1678.7 ± 20.7 | 1655.9 | 1696.2 | 864.61 ± 110.78 |
| mikofo | input-mikofo | 2078.6 ± 40.6 | 2043.7 | 2123.2 | 1070.54 ± 138.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|