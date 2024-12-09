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
| mattcl | input-mattcl | 2.1 ± 0.3 | 1.7 | 4.3 | 1.00 |
| mattcl | input-lanjian | 2.2 ± 0.2 | 1.7 | 3.0 | 1.00 ± 0.15 |
| mattcl | input-kcen | 2.3 ± 0.3 | 1.9 | 4.1 | 1.08 ± 0.18 |
| mattcl | input-mikofo | 2.5 ± 0.2 | 2.1 | 3.1 | 1.17 ± 0.16 |
| lanjian | input-mattcl | 38.9 ± 1.5 | 36.8 | 48.2 | 18.13 ± 2.38 |
| lanjian | input-lanjian | 42.6 ± 1.1 | 41.0 | 45.0 | 19.84 ± 2.53 |
| lanjian | input-kcen | 45.8 ± 1.1 | 44.1 | 48.9 | 21.32 ± 2.71 |
| lanjian | input-mikofo | 63.9 ± 0.9 | 62.4 | 65.9 | 29.76 ± 3.74 |
| mattcl-py | input-mattcl | 96.2 ± 1.3 | 93.9 | 99.2 | 44.80 ± 5.63 |
| mattcl-py | input-lanjian | 102.8 ± 1.5 | 100.3 | 105.8 | 47.91 ± 6.02 |
| mattcl-py | input-kcen | 109.4 ± 1.7 | 107.1 | 113.3 | 50.99 ± 6.42 |
| mattcl-py | input-mikofo | 145.0 ± 2.6 | 141.4 | 149.5 | 67.55 ± 8.52 |
| kcen | input-mattcl | 349.7 ± 2.3 | 345.9 | 353.1 | 162.94 ± 20.38 |
| kcen | input-lanjian | 361.0 ± 5.4 | 353.5 | 368.0 | 168.17 ± 21.15 |
| kcen | input-kcen | 409.6 ± 2.9 | 404.8 | 413.9 | 190.82 ± 23.87 |
| kcen | input-mikofo | 531.6 ± 0.9 | 530.1 | 532.6 | 247.67 ± 30.94 |
| mikofo | input-mattcl | 1411.0 ± 54.1 | 1355.1 | 1463.1 | 657.41 ± 85.89 |
| mikofo | input-lanjian | 1522.8 ± 18.4 | 1503.3 | 1539.8 | 709.49 ± 89.02 |
| mikofo | input-kcen | 1727.9 ± 29.7 | 1693.6 | 1745.8 | 805.06 ± 101.49 |
| mikofo | input-mikofo | 2126.1 ± 14.1 | 2112.3 | 2140.5 | 990.58 ± 123.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|