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
| mattcl | input-mattcl | 2.0 ± 0.3 | 1.4 | 3.5 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.6 | 1.00 ± 0.17 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.6 | 2.6 | 1.01 ± 0.16 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.7 | 2.9 | 1.09 ± 0.17 |
| lanjian | input-mattcl | 39.8 ± 1.3 | 38.2 | 46.1 | 20.05 ± 2.68 |
| lanjian | input-lanjian | 43.9 ± 1.1 | 42.1 | 47.1 | 22.14 ± 2.92 |
| lanjian | input-kcen | 47.3 ± 0.9 | 46.1 | 52.3 | 23.83 ± 3.12 |
| lanjian | input-mikofo | 66.9 ± 1.1 | 64.7 | 69.5 | 33.70 ± 4.40 |
| mattcl-py | input-mattcl | 95.9 ± 1.1 | 93.9 | 98.9 | 48.32 ± 6.29 |
| mattcl-py | input-lanjian | 102.6 ± 1.2 | 100.4 | 105.2 | 51.72 ± 6.73 |
| mattcl-py | input-kcen | 109.9 ± 1.7 | 107.1 | 114.1 | 55.37 ± 7.22 |
| mattcl-py | input-mikofo | 145.0 ± 2.8 | 141.4 | 151.4 | 73.08 ± 9.57 |
| kcen | input-mattcl | 200.3 ± 2.8 | 194.5 | 206.5 | 100.93 ± 13.16 |
| kcen | input-lanjian | 209.3 ± 2.8 | 204.8 | 214.7 | 105.49 ± 13.74 |
| kcen | input-kcen | 241.4 ± 1.9 | 239.2 | 245.2 | 121.66 ± 15.79 |
| kcen | input-mikofo | 296.1 ± 4.4 | 289.8 | 303.0 | 149.24 ± 19.47 |
| mikofo | input-mattcl | 1434.7 ± 40.0 | 1389.1 | 1463.5 | 723.07 ± 95.83 |
| mikofo | input-lanjian | 1533.1 ± 68.9 | 1454.2 | 1581.0 | 772.64 ± 105.96 |
| mikofo | input-kcen | 1748.3 ± 56.4 | 1697.6 | 1809.0 | 881.13 ± 117.65 |
| mikofo | input-mikofo | 2149.3 ± 2.6 | 2146.5 | 2151.6 | 1083.21 ± 140.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|