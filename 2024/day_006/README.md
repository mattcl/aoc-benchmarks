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
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.5 | 2.6 | 1.00 |
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.5 | 2.5 | 1.00 ± 0.15 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.6 | 2.8 | 1.04 ± 0.15 |
| mattcl | input-mikofo | 2.2 ± 0.2 | 1.8 | 2.8 | 1.11 ± 0.14 |
| lanjian | input-mattcl | 37.2 ± 1.2 | 35.9 | 44.1 | 18.66 ± 2.08 |
| lanjian | input-lanjian | 40.9 ± 1.0 | 39.4 | 43.5 | 20.49 ± 2.24 |
| lanjian | input-kcen | 44.2 ± 1.2 | 42.1 | 47.1 | 22.15 ± 2.44 |
| mattcl-py | input-mattcl | 57.6 ± 0.8 | 56.3 | 59.9 | 28.84 ± 3.11 |
| mattcl-py | input-lanjian | 58.6 ± 0.8 | 57.1 | 60.5 | 29.36 ± 3.16 |
| mattcl-py | input-kcen | 60.4 ± 0.7 | 58.7 | 62.6 | 30.24 ± 3.25 |
| lanjian | input-mikofo | 61.5 ± 1.5 | 59.5 | 65.7 | 30.81 ± 3.38 |
| mattcl-py | input-mikofo | 65.0 ± 1.0 | 62.4 | 67.3 | 32.58 ± 3.52 |
| kcen | input-mattcl | 195.7 ± 3.6 | 190.6 | 201.8 | 98.07 ± 10.64 |
| kcen | input-lanjian | 206.1 ± 2.5 | 200.2 | 209.6 | 103.25 ± 11.11 |
| kcen | input-kcen | 240.9 ± 4.7 | 234.7 | 252.7 | 120.73 ± 13.12 |
| kcen | input-mikofo | 288.5 ± 5.5 | 276.5 | 294.9 | 144.54 ± 15.69 |
| mikofo | input-mattcl | 1391.0 ± 35.6 | 1362.6 | 1430.9 | 696.98 ± 76.61 |
| mikofo | input-lanjian | 1479.3 ± 46.7 | 1437.5 | 1529.6 | 741.23 ± 82.61 |
| mikofo | input-kcen | 1681.8 ± 35.2 | 1643.6 | 1712.8 | 842.66 ± 91.79 |
| mikofo | input-mikofo | 2058.0 ± 35.5 | 2019.3 | 2089.2 | 1031.17 ± 111.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|