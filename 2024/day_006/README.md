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
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.8 | 1.02 ± 0.16 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.6 | 4.1 | 1.05 ± 0.16 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.8 | 3.1 | 1.13 ± 0.16 |
| lanjian | input-mattcl | 39.9 ± 1.0 | 38.1 | 43.0 | 20.31 ± 2.30 |
| lanjian | input-lanjian | 44.1 ± 1.3 | 42.2 | 46.8 | 22.44 ± 2.56 |
| lanjian | input-kcen | 47.4 ± 1.1 | 46.0 | 50.3 | 24.11 ± 2.71 |
| mattcl-py | input-mattcl | 58.3 ± 0.9 | 56.7 | 61.7 | 29.66 ± 3.30 |
| mattcl-py | input-lanjian | 59.1 ± 0.9 | 57.2 | 60.9 | 30.07 ± 3.34 |
| mattcl-py | input-kcen | 60.9 ± 0.7 | 59.7 | 62.6 | 30.98 ± 3.43 |
| mattcl-py | input-mikofo | 65.5 ± 0.8 | 63.5 | 67.4 | 33.34 ± 3.70 |
| lanjian | input-mikofo | 66.7 ± 1.1 | 65.2 | 69.8 | 33.95 ± 3.79 |
| kcen | input-lanjian | 206.1 ± 3.0 | 201.7 | 210.2 | 104.90 ± 11.66 |
| kcen | input-mattcl | 213.2 ± 61.0 | 191.2 | 433.5 | 108.52 ± 33.29 |
| kcen | input-kcen | 237.1 ± 3.0 | 232.3 | 241.2 | 120.72 ± 13.40 |
| kcen | input-mikofo | 289.2 ± 4.2 | 281.9 | 294.3 | 147.24 ± 16.38 |
| mikofo | input-mattcl | 1419.2 ± 49.0 | 1373.2 | 1470.7 | 722.48 ± 83.47 |
| mikofo | input-lanjian | 1498.8 ± 74.0 | 1440.4 | 1582.1 | 763.01 ± 92.18 |
| mikofo | input-kcen | 1693.9 ± 66.2 | 1617.5 | 1732.9 | 862.33 ± 100.88 |
| mikofo | input-mikofo | 2103.2 ± 19.4 | 2088.9 | 2125.2 | 1070.66 ± 118.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|