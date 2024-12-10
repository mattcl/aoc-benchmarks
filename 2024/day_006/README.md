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
| mattcl | input-mattcl | 1.8 ± 0.3 | 1.3 | 2.6 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 2.8 | 1.02 ± 0.19 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.4 | 2.9 | 1.06 ± 0.19 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.7 | 3.8 | 1.12 ± 0.19 |
| lanjian | input-mattcl | 38.0 ± 1.6 | 36.6 | 50.4 | 20.55 ± 2.94 |
| lanjian | input-lanjian | 41.7 ± 1.1 | 40.1 | 44.4 | 22.55 ± 3.14 |
| lanjian | input-kcen | 45.1 ± 1.1 | 43.5 | 48.6 | 24.43 ± 3.39 |
| lanjian | input-mikofo | 63.0 ± 1.0 | 61.7 | 65.6 | 34.08 ± 4.68 |
| mattcl-py | input-mattcl | 93.9 ± 0.9 | 92.0 | 95.6 | 50.83 ± 6.95 |
| mattcl-py | input-lanjian | 101.0 ± 1.3 | 98.6 | 103.9 | 54.66 ± 7.49 |
| mattcl-py | input-kcen | 107.6 ± 1.7 | 104.5 | 111.9 | 58.25 ± 8.00 |
| mattcl-py | input-mikofo | 144.5 ± 5.8 | 140.1 | 163.0 | 78.19 ± 11.12 |
| kcen | input-mattcl | 197.1 ± 3.8 | 191.3 | 202.6 | 106.70 ± 14.70 |
| kcen | input-lanjian | 205.3 ± 5.0 | 196.4 | 213.2 | 111.09 ± 15.40 |
| kcen | input-kcen | 245.3 ± 8.9 | 233.6 | 269.4 | 132.77 ± 18.75 |
| kcen | input-mikofo | 290.9 ± 7.6 | 280.0 | 302.3 | 157.45 ± 21.87 |
| mikofo | input-mattcl | 1374.6 ± 18.7 | 1353.1 | 1387.4 | 743.97 ± 102.03 |
| mikofo | input-lanjian | 1465.6 ± 33.1 | 1436.1 | 1501.4 | 793.20 ± 109.72 |
| mikofo | input-kcen | 1684.8 ± 47.6 | 1631.4 | 1722.4 | 911.86 ± 127.07 |
| mikofo | input-mikofo | 2079.3 ± 24.4 | 2052.7 | 2100.8 | 1125.36 ± 154.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|