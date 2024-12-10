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
| mattcl | input-lanjian | 1.9 ± 0.3 | 1.3 | 3.5 | 1.02 ± 0.21 |
| mattcl | input-kcen | 1.9 ± 0.2 | 1.5 | 2.5 | 1.05 ± 0.20 |
| mattcl | input-mikofo | 2.0 ± 0.2 | 1.6 | 2.9 | 1.11 ± 0.20 |
| lanjian | input-mattcl | 38.2 ± 1.1 | 36.5 | 41.4 | 20.84 ± 3.04 |
| lanjian | input-lanjian | 42.2 ± 1.7 | 40.2 | 52.3 | 23.03 ± 3.41 |
| lanjian | input-kcen | 45.6 ± 2.0 | 43.5 | 58.0 | 24.92 ± 3.72 |
| lanjian | input-mikofo | 63.3 ± 1.1 | 61.3 | 66.1 | 34.54 ± 4.97 |
| mattcl-py | input-mattcl | 93.9 ± 1.1 | 91.6 | 95.9 | 51.27 ± 7.35 |
| mattcl-py | input-lanjian | 101.1 ± 1.2 | 99.0 | 105.2 | 55.18 ± 7.91 |
| mattcl-py | input-kcen | 108.2 ± 2.6 | 105.4 | 116.5 | 59.05 ± 8.55 |
| mattcl-py | input-mikofo | 144.1 ± 4.1 | 140.0 | 153.2 | 78.68 ± 11.46 |
| kcen | input-mattcl | 347.7 ± 6.0 | 339.8 | 355.3 | 189.82 ± 27.32 |
| kcen | input-lanjian | 361.7 ± 2.0 | 358.7 | 364.8 | 197.48 ± 28.24 |
| kcen | input-kcen | 415.1 ± 7.7 | 404.9 | 425.1 | 226.61 ± 32.65 |
| kcen | input-mikofo | 527.4 ± 7.3 | 520.6 | 535.7 | 287.92 ± 41.33 |
| mikofo | input-mattcl | 1369.8 ± 40.8 | 1322.8 | 1397.1 | 747.78 ± 109.15 |
| mikofo | input-lanjian | 1468.5 ± 70.3 | 1411.5 | 1547.1 | 801.71 ± 120.82 |
| mikofo | input-kcen | 1704.1 ± 19.5 | 1681.7 | 1716.4 | 930.30 ± 133.36 |
| mikofo | input-mikofo | 2080.2 ± 40.6 | 2050.3 | 2126.4 | 1135.64 ± 163.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|