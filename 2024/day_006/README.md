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
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.3 | 2.6 | 1.00 |
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.4 | 3.0 | 1.00 ± 0.18 |
| mattcl | input-kcen | 1.9 ± 0.3 | 1.5 | 3.1 | 1.04 ± 0.20 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.6 | 2.8 | 1.10 ± 0.18 |
| lanjian | input-mattcl | 38.4 ± 1.1 | 36.9 | 41.6 | 20.47 ± 2.75 |
| lanjian | input-lanjian | 42.3 ± 1.9 | 40.6 | 54.0 | 22.54 ± 3.13 |
| lanjian | input-kcen | 46.1 ± 2.4 | 43.3 | 63.3 | 24.55 ± 3.48 |
| lanjian | input-mikofo | 63.6 ± 1.0 | 61.9 | 66.9 | 33.87 ± 4.49 |
| mattcl-py | input-mattcl | 97.3 ± 3.2 | 93.8 | 106.5 | 51.83 ± 7.02 |
| mattcl-py | input-lanjian | 102.3 ± 1.7 | 100.3 | 106.5 | 54.50 ± 7.22 |
| mattcl-py | input-kcen | 109.5 ± 1.4 | 106.2 | 112.1 | 58.30 ± 7.70 |
| mattcl-py | input-mikofo | 146.4 ± 4.8 | 142.1 | 164.3 | 77.97 ± 10.56 |
| kcen | input-mattcl | 348.2 ± 3.2 | 345.8 | 355.8 | 185.43 ± 24.43 |
| kcen | input-lanjian | 359.5 ± 2.5 | 355.1 | 362.8 | 191.45 ± 25.20 |
| kcen | input-kcen | 409.5 ± 2.8 | 407.0 | 414.0 | 218.05 ± 28.70 |
| kcen | input-mikofo | 528.0 ± 3.2 | 524.1 | 532.9 | 281.17 ± 37.00 |
| mikofo | input-mattcl | 1438.2 ± 40.8 | 1394.3 | 1475.1 | 765.86 ± 102.99 |
| mikofo | input-lanjian | 1519.8 ± 59.3 | 1451.3 | 1554.9 | 809.28 ± 110.96 |
| mikofo | input-kcen | 1828.3 ± 42.4 | 1782.1 | 1865.5 | 973.58 ± 129.94 |
| mikofo | input-mikofo | 2122.1 ± 30.0 | 2089.1 | 2147.8 | 1130.04 ± 149.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|