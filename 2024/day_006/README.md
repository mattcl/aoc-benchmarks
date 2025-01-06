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
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.5 | 1.00 |
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.4 | 2.6 | 1.00 ± 0.16 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.6 | 2.5 | 1.02 ± 0.15 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.8 | 2.8 | 1.10 ± 0.15 |
| lanjian | input-mattcl | 39.4 ± 1.0 | 38.3 | 42.3 | 20.04 ± 2.31 |
| lanjian | input-lanjian | 43.5 ± 1.0 | 42.4 | 46.3 | 22.11 ± 2.53 |
| lanjian | input-kcen | 47.1 ± 1.2 | 45.1 | 50.5 | 23.97 ± 2.76 |
| mattcl-py | input-mattcl | 57.3 ± 0.6 | 56.0 | 58.8 | 29.14 ± 3.29 |
| mattcl-py | input-lanjian | 58.4 ± 0.6 | 57.3 | 59.6 | 29.72 ± 3.36 |
| mattcl-py | input-kcen | 60.0 ± 0.7 | 58.1 | 61.8 | 30.53 ± 3.45 |
| mattcl-py | input-mikofo | 64.6 ± 0.7 | 62.7 | 66.4 | 32.88 ± 3.71 |
| lanjian | input-mikofo | 66.6 ± 1.1 | 64.8 | 69.3 | 33.91 ± 3.85 |
| kcen | input-mattcl | 199.4 ± 4.2 | 193.2 | 207.4 | 101.46 ± 11.61 |
| kcen | input-lanjian | 207.2 ± 5.7 | 197.2 | 216.4 | 105.41 ± 12.20 |
| kcen | input-kcen | 237.4 ± 3.9 | 230.5 | 244.4 | 120.77 ± 13.72 |
| kcen | input-mikofo | 298.7 ± 8.1 | 287.1 | 311.4 | 152.00 ± 17.59 |
| mikofo | input-mattcl | 1356.4 ± 16.4 | 1343.0 | 1374.7 | 690.16 ± 78.05 |
| mikofo | input-lanjian | 1472.7 ± 18.9 | 1451.4 | 1487.6 | 749.30 ± 84.80 |
| mikofo | input-kcen | 1667.5 ± 35.9 | 1634.7 | 1705.9 | 848.44 ± 97.13 |
| mikofo | input-mikofo | 2056.6 ± 66.2 | 1980.2 | 2095.3 | 1046.41 ± 122.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|