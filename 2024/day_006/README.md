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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.6 | 3.1 | 1.00 |
| mattcl | input-lanjian | 2.1 ± 0.2 | 1.7 | 2.8 | 1.01 ± 0.14 |
| mattcl | input-kcen | 2.2 ± 0.2 | 1.8 | 3.9 | 1.09 ± 0.17 |
| mattcl | input-mikofo | 2.5 ± 0.2 | 2.2 | 3.5 | 1.21 ± 0.15 |
| lanjian | input-mattcl | 37.8 ± 0.9 | 36.4 | 40.5 | 18.50 ± 1.98 |
| lanjian | input-lanjian | 42.0 ± 1.9 | 39.9 | 54.6 | 20.55 ± 2.33 |
| lanjian | input-kcen | 45.4 ± 1.2 | 44.0 | 49.2 | 22.25 ± 2.39 |
| lanjian | input-mikofo | 63.0 ± 1.1 | 61.7 | 67.7 | 30.86 ± 3.26 |
| mattcl-py | input-mattcl | 94.7 ± 1.1 | 92.7 | 96.8 | 46.37 ± 4.86 |
| mattcl-py | input-lanjian | 101.6 ± 1.8 | 98.0 | 105.5 | 49.74 ± 5.26 |
| mattcl-py | input-kcen | 108.3 ± 1.7 | 105.9 | 112.5 | 53.04 ± 5.59 |
| mattcl-py | input-mikofo | 145.6 ± 3.3 | 140.1 | 152.2 | 71.30 ± 7.61 |
| kcen | input-mattcl | 348.7 ± 4.7 | 342.1 | 355.1 | 170.74 ± 17.94 |
| kcen | input-lanjian | 362.2 ± 3.4 | 358.5 | 368.4 | 177.35 ± 18.55 |
| kcen | input-kcen | 416.3 ± 3.6 | 411.1 | 421.7 | 203.83 ± 21.31 |
| kcen | input-mikofo | 529.7 ± 5.9 | 523.2 | 538.5 | 259.36 ± 27.18 |
| mikofo | input-mattcl | 1397.6 ± 37.8 | 1366.1 | 1439.6 | 684.35 ± 73.68 |
| mikofo | input-lanjian | 1483.2 ± 30.9 | 1451.7 | 1513.4 | 726.26 ± 77.17 |
| mikofo | input-kcen | 1680.6 ± 40.6 | 1634.1 | 1709.1 | 822.90 ± 88.03 |
| mikofo | input-mikofo | 2069.3 ± 30.3 | 2034.5 | 2090.1 | 1013.21 ± 106.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|