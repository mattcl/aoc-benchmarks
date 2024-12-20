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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.4 | 2.4 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.5 | 2.9 | 1.00 ± 0.17 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.9 | 1.04 ± 0.15 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.8 | 3.1 | 1.11 ± 0.15 |
| lanjian | input-mattcl | 40.4 ± 1.1 | 39.1 | 43.9 | 20.97 ± 2.34 |
| lanjian | input-lanjian | 44.4 ± 1.0 | 42.9 | 48.1 | 23.05 ± 2.55 |
| lanjian | input-kcen | 48.4 ± 1.1 | 46.5 | 52.1 | 25.08 ± 2.76 |
| lanjian | input-mikofo | 68.0 ± 1.7 | 65.5 | 73.0 | 35.25 ± 3.90 |
| mattcl-py | input-mattcl | 94.5 ± 1.0 | 92.1 | 96.0 | 48.99 ± 5.31 |
| mattcl-py | input-lanjian | 101.1 ± 1.7 | 97.9 | 105.3 | 52.41 ± 5.73 |
| mattcl-py | input-kcen | 107.7 ± 1.6 | 104.9 | 111.6 | 55.86 ± 6.09 |
| mattcl-py | input-mikofo | 142.2 ± 2.1 | 138.5 | 146.1 | 73.75 ± 8.04 |
| kcen | input-mattcl | 196.7 ± 3.5 | 190.6 | 200.7 | 102.01 ± 11.16 |
| kcen | input-lanjian | 207.3 ± 5.5 | 195.7 | 215.3 | 107.51 ± 11.95 |
| kcen | input-kcen | 242.7 ± 3.6 | 234.6 | 247.8 | 125.85 ± 13.71 |
| kcen | input-mikofo | 292.2 ± 5.5 | 284.3 | 299.3 | 151.55 ± 16.61 |
| mikofo | input-mattcl | 1407.6 ± 42.6 | 1371.0 | 1454.3 | 730.02 ± 81.83 |
| mikofo | input-lanjian | 1482.3 ± 13.9 | 1470.0 | 1497.5 | 768.74 ± 83.29 |
| mikofo | input-kcen | 1703.9 ± 49.0 | 1649.7 | 1745.0 | 883.66 ± 98.71 |
| mikofo | input-mikofo | 2071.9 ± 29.0 | 2039.5 | 2095.2 | 1074.51 ± 116.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|