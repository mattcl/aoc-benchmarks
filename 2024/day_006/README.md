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
| mattcl | input-mattcl | 1.9 ± 0.3 | 1.3 | 4.0 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 2.6 | 1.00 ± 0.20 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.7 | 1.02 ± 0.21 |
| mattcl | input-mikofo | 2.1 ± 0.3 | 1.7 | 4.0 | 1.12 ± 0.25 |
| lanjian | input-mattcl | 38.9 ± 1.0 | 37.4 | 42.8 | 20.26 ± 3.33 |
| lanjian | input-lanjian | 42.8 ± 1.1 | 41.0 | 46.1 | 22.29 ± 3.67 |
| lanjian | input-kcen | 46.6 ± 1.3 | 44.7 | 52.1 | 24.27 ± 4.00 |
| lanjian | input-mikofo | 64.3 ± 1.2 | 62.4 | 67.2 | 33.52 ± 5.48 |
| mattcl-py | input-mattcl | 95.9 ± 1.0 | 94.1 | 98.1 | 50.01 ± 8.14 |
| mattcl-py | input-lanjian | 103.1 ± 1.5 | 100.7 | 106.7 | 53.73 ± 8.76 |
| mattcl-py | input-kcen | 109.9 ± 1.4 | 107.8 | 115.1 | 57.31 ± 9.34 |
| mattcl-py | input-mikofo | 146.4 ± 3.8 | 142.1 | 154.2 | 76.31 ± 12.55 |
| kcen | input-mattcl | 204.7 ± 7.9 | 196.7 | 227.1 | 106.71 ± 17.82 |
| kcen | input-lanjian | 212.9 ± 4.1 | 205.4 | 219.5 | 110.99 ± 18.16 |
| kcen | input-kcen | 245.3 ± 3.7 | 236.8 | 251.0 | 127.85 ± 20.86 |
| kcen | input-mikofo | 294.6 ± 4.4 | 288.6 | 303.0 | 153.59 ± 25.06 |
| mikofo | input-mattcl | 1420.3 ± 43.0 | 1375.0 | 1460.4 | 740.40 ± 122.35 |
| mikofo | input-lanjian | 1524.6 ± 38.7 | 1483.3 | 1560.1 | 794.79 ± 130.69 |
| mikofo | input-kcen | 1728.7 ± 31.6 | 1692.4 | 1749.6 | 901.16 ± 147.32 |
| mikofo | input-mikofo | 2149.1 ± 19.8 | 2136.0 | 2171.9 | 1120.30 ± 182.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|