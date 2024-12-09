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
| mattcl | input-mattcl | 2.1 ± 0.2 | 1.6 | 3.6 | 1.00 |
| mattcl | input-lanjian | 2.1 ± 0.2 | 1.6 | 2.5 | 1.01 ± 0.14 |
| mattcl | input-kcen | 2.2 ± 0.2 | 1.9 | 3.3 | 1.07 ± 0.16 |
| mattcl | input-mikofo | 2.5 ± 0.2 | 2.1 | 3.5 | 1.19 ± 0.16 |
| lanjian | input-mattcl | 38.2 ± 1.2 | 36.3 | 43.0 | 18.56 ± 2.14 |
| lanjian | input-lanjian | 41.9 ± 1.2 | 40.2 | 44.9 | 20.40 ± 2.33 |
| lanjian | input-kcen | 45.2 ± 1.0 | 43.6 | 47.7 | 21.96 ± 2.47 |
| lanjian | input-mikofo | 63.7 ± 1.0 | 61.5 | 66.4 | 30.97 ± 3.45 |
| mattcl-py | input-mattcl | 94.7 ± 1.2 | 92.6 | 96.8 | 46.05 ± 5.12 |
| mattcl-py | input-lanjian | 101.4 ± 1.9 | 97.9 | 105.6 | 49.30 ± 5.53 |
| mattcl-py | input-kcen | 108.5 ± 1.7 | 105.9 | 115.0 | 52.76 ± 5.89 |
| mattcl-py | input-mikofo | 144.4 ± 3.2 | 139.0 | 149.4 | 70.21 ± 7.91 |
| kcen | input-mattcl | 348.7 ± 6.0 | 339.1 | 355.1 | 169.56 ± 18.96 |
| kcen | input-lanjian | 359.8 ± 7.7 | 352.5 | 375.8 | 174.96 ± 19.69 |
| kcen | input-kcen | 414.8 ± 6.0 | 406.5 | 421.2 | 201.72 ± 22.48 |
| kcen | input-mikofo | 534.0 ± 4.3 | 529.0 | 539.9 | 259.66 ± 28.76 |
| mikofo | input-mattcl | 1412.2 ± 31.6 | 1377.1 | 1438.5 | 686.70 ± 77.41 |
| mikofo | input-lanjian | 1470.4 ± 51.5 | 1418.6 | 1521.5 | 714.99 ± 82.86 |
| mikofo | input-kcen | 1685.1 ± 32.8 | 1648.6 | 1712.1 | 819.42 ± 91.92 |
| mikofo | input-mikofo | 2047.4 ± 14.4 | 2030.8 | 2056.0 | 995.58 ± 110.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|