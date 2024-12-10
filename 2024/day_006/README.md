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
| mattcl | input-lanjian | 2.1 ± 0.2 | 1.6 | 3.3 | 1.00 |
| mattcl | input-mattcl | 2.1 ± 0.3 | 1.6 | 4.0 | 1.00 ± 0.17 |
| mattcl | input-kcen | 2.2 ± 0.2 | 1.8 | 3.8 | 1.05 ± 0.14 |
| mattcl | input-mikofo | 2.5 ± 0.3 | 2.1 | 5.7 | 1.19 ± 0.18 |
| lanjian | input-mattcl | 38.0 ± 1.2 | 36.3 | 41.8 | 18.43 ± 1.82 |
| lanjian | input-lanjian | 42.2 ± 1.8 | 40.3 | 52.3 | 20.44 ± 2.11 |
| lanjian | input-kcen | 45.1 ± 1.2 | 43.8 | 49.4 | 21.85 ± 2.14 |
| lanjian | input-mikofo | 63.3 ± 1.3 | 61.3 | 66.6 | 30.66 ± 2.95 |
| mattcl-py | input-mattcl | 94.1 ± 1.0 | 91.8 | 95.9 | 45.57 ± 4.32 |
| mattcl-py | input-lanjian | 101.1 ± 1.7 | 96.9 | 104.1 | 48.98 ± 4.69 |
| mattcl-py | input-kcen | 107.8 ± 1.7 | 105.2 | 112.0 | 52.23 ± 4.99 |
| mattcl-py | input-mikofo | 144.0 ± 2.6 | 140.3 | 147.7 | 69.77 ± 6.69 |
| kcen | input-mattcl | 350.2 ± 2.7 | 347.1 | 355.9 | 169.64 ± 16.04 |
| kcen | input-lanjian | 359.0 ± 3.4 | 353.4 | 363.7 | 173.90 ± 16.48 |
| kcen | input-kcen | 413.3 ± 3.4 | 408.7 | 417.3 | 200.24 ± 18.95 |
| kcen | input-mikofo | 536.7 ± 10.2 | 527.7 | 553.7 | 260.03 ± 25.01 |
| mikofo | input-mattcl | 1391.0 ± 37.3 | 1349.0 | 1420.0 | 673.90 ± 66.04 |
| mikofo | input-lanjian | 1481.0 ± 9.1 | 1470.5 | 1487.1 | 717.49 ± 67.78 |
| mikofo | input-kcen | 1675.6 ± 58.4 | 1608.1 | 1709.9 | 811.74 ± 81.59 |
| mikofo | input-mikofo | 2071.3 ± 14.2 | 2055.4 | 2082.7 | 1003.45 ± 94.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|