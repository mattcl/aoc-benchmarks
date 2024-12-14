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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.4 | 2.6 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.5 | 2.6 | 1.01 ± 0.17 |
| mattcl | input-kcen | 2.0 ± 0.3 | 1.5 | 2.9 | 1.06 ± 0.19 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.7 | 2.8 | 1.11 ± 0.16 |
| lanjian | input-mattcl | 40.8 ± 1.3 | 38.8 | 45.3 | 21.62 ± 2.78 |
| lanjian | input-lanjian | 44.9 ± 1.2 | 43.1 | 48.4 | 23.81 ± 3.03 |
| lanjian | input-kcen | 48.6 ± 1.8 | 46.3 | 58.5 | 25.79 ± 3.34 |
| lanjian | input-mikofo | 67.9 ± 1.3 | 65.8 | 71.8 | 36.03 ± 4.53 |
| mattcl-py | input-mattcl | 93.8 ± 1.0 | 92.2 | 96.5 | 49.77 ± 6.20 |
| mattcl-py | input-lanjian | 101.0 ± 1.7 | 98.5 | 105.0 | 53.59 ± 6.72 |
| mattcl-py | input-kcen | 107.4 ± 1.4 | 104.6 | 111.2 | 56.97 ± 7.11 |
| mattcl-py | input-mikofo | 142.7 ± 2.2 | 138.6 | 146.6 | 75.67 ± 9.47 |
| kcen | input-mattcl | 199.4 ± 3.9 | 193.5 | 205.6 | 105.77 ± 13.30 |
| kcen | input-lanjian | 208.3 ± 2.9 | 204.4 | 214.1 | 110.46 ± 13.81 |
| kcen | input-kcen | 242.7 ± 5.1 | 232.4 | 251.1 | 128.73 ± 16.22 |
| kcen | input-mikofo | 296.2 ± 7.5 | 282.6 | 309.7 | 157.08 ± 19.92 |
| mikofo | input-mattcl | 1382.4 ± 26.4 | 1362.0 | 1412.3 | 733.20 ± 92.16 |
| mikofo | input-lanjian | 1472.4 ± 47.7 | 1428.4 | 1523.1 | 780.95 ± 100.26 |
| mikofo | input-kcen | 1681.5 ± 52.7 | 1625.9 | 1730.8 | 891.85 ± 114.27 |
| mikofo | input-mikofo | 2034.7 ± 30.2 | 2000.0 | 2054.2 | 1079.18 ± 135.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|