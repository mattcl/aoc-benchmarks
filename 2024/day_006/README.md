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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.5 | 2.8 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 3.0 | 1.01 ± 0.17 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.6 | 3.0 | 1.04 ± 0.16 |
| mattcl | input-mikofo | 2.3 ± 0.2 | 1.9 | 2.9 | 1.14 ± 0.16 |
| lanjian | input-mattcl | 40.0 ± 1.1 | 38.4 | 43.0 | 19.84 ± 2.48 |
| lanjian | input-lanjian | 44.2 ± 1.1 | 42.5 | 47.0 | 21.90 ± 2.73 |
| lanjian | input-kcen | 47.8 ± 1.3 | 46.0 | 52.0 | 23.69 ± 2.96 |
| mattcl-py | input-mattcl | 58.4 ± 0.7 | 56.6 | 59.6 | 28.93 ± 3.55 |
| mattcl-py | input-lanjian | 58.9 ± 0.7 | 57.2 | 60.2 | 29.22 ± 3.58 |
| mattcl-py | input-kcen | 61.1 ± 0.8 | 59.7 | 62.9 | 30.29 ± 3.72 |
| mattcl-py | input-mikofo | 65.6 ± 0.7 | 64.5 | 67.4 | 32.53 ± 3.99 |
| lanjian | input-mikofo | 66.7 ± 1.2 | 64.8 | 69.2 | 33.06 ± 4.09 |
| kcen | input-mattcl | 198.1 ± 4.6 | 189.1 | 207.6 | 98.20 ± 12.21 |
| kcen | input-lanjian | 208.0 ± 3.5 | 201.1 | 216.3 | 103.13 ± 12.72 |
| kcen | input-kcen | 240.5 ± 2.9 | 234.4 | 245.4 | 119.22 ± 14.63 |
| kcen | input-mikofo | 291.4 ± 4.7 | 285.1 | 298.2 | 144.46 ± 17.80 |
| mikofo | input-mattcl | 1409.8 ± 46.4 | 1379.2 | 1463.2 | 699.02 ± 88.44 |
| mikofo | input-lanjian | 1506.6 ± 33.1 | 1476.6 | 1542.1 | 747.01 ± 92.72 |
| mikofo | input-kcen | 1714.4 ± 56.4 | 1649.4 | 1750.4 | 850.05 ± 107.54 |
| mikofo | input-mikofo | 2076.5 ± 45.6 | 2035.3 | 2125.5 | 1029.56 ± 127.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|