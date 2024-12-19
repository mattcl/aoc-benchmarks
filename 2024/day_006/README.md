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
| mattcl | input-mattcl | 1.9 ± 0.3 | 1.4 | 3.5 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.4 | 2.8 | 1.02 ± 0.19 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.8 | 1.05 ± 0.19 |
| mattcl | input-mikofo | 2.2 ± 0.3 | 1.8 | 4.7 | 1.14 ± 0.23 |
| lanjian | input-mattcl | 40.4 ± 1.1 | 38.8 | 43.9 | 21.12 ± 3.11 |
| lanjian | input-lanjian | 44.4 ± 1.1 | 42.4 | 48.0 | 23.26 ± 3.42 |
| lanjian | input-kcen | 48.4 ± 1.1 | 47.0 | 52.3 | 25.35 ± 3.71 |
| lanjian | input-mikofo | 67.7 ± 1.3 | 65.5 | 71.2 | 35.43 ± 5.18 |
| mattcl-py | input-mattcl | 94.0 ± 1.1 | 91.7 | 96.0 | 49.21 ± 7.15 |
| mattcl-py | input-lanjian | 101.1 ± 1.3 | 98.5 | 103.6 | 52.91 ± 7.69 |
| mattcl-py | input-kcen | 108.4 ± 1.6 | 105.3 | 111.4 | 56.75 ± 8.26 |
| mattcl-py | input-mikofo | 142.5 ± 2.1 | 139.0 | 147.9 | 74.57 ± 10.85 |
| kcen | input-mattcl | 197.0 ± 4.0 | 189.4 | 203.3 | 103.10 ± 15.07 |
| kcen | input-lanjian | 206.9 ± 4.7 | 200.0 | 214.4 | 108.30 ± 15.87 |
| kcen | input-kcen | 241.7 ± 5.1 | 228.6 | 246.6 | 126.50 ± 18.51 |
| kcen | input-mikofo | 293.0 ± 6.4 | 280.3 | 302.5 | 153.39 ± 22.46 |
| mikofo | input-mattcl | 1386.5 ± 44.1 | 1349.4 | 1435.3 | 725.76 ± 107.60 |
| mikofo | input-lanjian | 1476.8 ± 17.1 | 1463.1 | 1496.0 | 773.00 ± 112.29 |
| mikofo | input-kcen | 1684.5 ± 22.3 | 1660.4 | 1704.3 | 881.75 ± 128.21 |
| mikofo | input-mikofo | 2077.1 ± 42.5 | 2045.7 | 2125.4 | 1087.23 ± 159.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|