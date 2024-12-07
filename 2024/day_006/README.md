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
| mattcl | input-mattcl | 2.1 ± 0.3 | 1.6 | 4.3 | 1.00 |
| mattcl | input-lanjian | 2.1 ± 0.4 | 1.6 | 4.8 | 1.04 ± 0.24 |
| mattcl | input-kcen | 2.2 ± 0.2 | 1.8 | 3.1 | 1.06 ± 0.17 |
| mattcl | input-mikofo | 2.5 ± 0.3 | 2.1 | 5.1 | 1.22 ± 0.23 |
| lanjian | input-mattcl | 40.9 ± 0.7 | 39.3 | 43.0 | 19.84 ± 2.73 |
| lanjian | input-lanjian | 45.3 ± 1.2 | 43.7 | 48.1 | 21.96 ± 3.05 |
| lanjian | input-kcen | 48.8 ± 1.1 | 46.9 | 51.9 | 23.65 ± 3.27 |
| lanjian | input-mikofo | 68.8 ± 0.9 | 67.0 | 71.2 | 33.36 ± 4.57 |
| mattcl-py | input-mattcl | 95.7 ± 1.3 | 93.6 | 98.3 | 46.44 ± 6.36 |
| mattcl-py | input-lanjian | 103.1 ± 1.3 | 100.3 | 105.8 | 49.98 ± 6.84 |
| mattcl-py | input-kcen | 109.3 ± 1.3 | 107.2 | 111.5 | 53.00 ± 7.25 |
| mattcl-py | input-mikofo | 145.9 ± 3.1 | 142.0 | 151.1 | 70.75 ± 9.76 |
| kcen | input-mattcl | 346.5 ± 1.5 | 343.9 | 348.3 | 168.07 ± 22.93 |
| kcen | input-lanjian | 356.3 ± 1.4 | 354.1 | 358.7 | 172.80 ± 23.57 |
| kcen | input-kcen | 408.2 ± 2.3 | 405.1 | 410.5 | 197.97 ± 27.01 |
| kcen | input-mikofo | 529.9 ± 1.6 | 527.6 | 531.4 | 257.02 ± 35.05 |
| mikofo | input-mattcl | 1433.8 ± 33.6 | 1395.1 | 1456.2 | 695.41 ± 96.20 |
| mikofo | input-lanjian | 1515.3 ± 61.9 | 1444.6 | 1559.9 | 734.96 ± 104.61 |
| mikofo | input-kcen | 1715.5 ± 10.9 | 1707.9 | 1728.0 | 832.04 ± 113.56 |
| mikofo | input-mikofo | 2151.7 ± 24.7 | 2125.0 | 2173.5 | 1043.64 ± 142.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|