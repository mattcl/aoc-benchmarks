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
| mattcl | input-mattcl | 1.9 ± 0.3 | 1.3 | 2.8 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 2.6 | 1.03 ± 0.19 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.8 | 1.04 ± 0.20 |
| mattcl | input-mikofo | 2.1 ± 0.3 | 1.6 | 5.2 | 1.12 ± 0.22 |
| lanjian | input-mattcl | 38.4 ± 2.2 | 36.8 | 51.4 | 20.43 ± 3.06 |
| lanjian | input-lanjian | 42.1 ± 1.6 | 40.1 | 50.6 | 22.43 ± 3.22 |
| lanjian | input-kcen | 45.2 ± 1.1 | 43.9 | 49.0 | 24.07 ± 3.39 |
| lanjian | input-mikofo | 63.2 ± 2.4 | 61.6 | 77.3 | 33.65 ± 4.84 |
| mattcl-py | input-mattcl | 94.4 ± 1.2 | 92.6 | 96.8 | 50.22 ± 6.99 |
| mattcl-py | input-lanjian | 101.2 ± 1.3 | 98.2 | 103.9 | 53.86 ± 7.50 |
| mattcl-py | input-kcen | 108.3 ± 1.7 | 105.0 | 111.9 | 57.64 ± 8.04 |
| mattcl-py | input-mikofo | 145.5 ± 3.6 | 138.6 | 153.0 | 77.44 ± 10.90 |
| kcen | input-mattcl | 345.2 ± 1.2 | 343.4 | 347.0 | 183.69 ± 25.47 |
| kcen | input-lanjian | 360.9 ± 8.1 | 351.8 | 377.1 | 192.04 ± 26.97 |
| kcen | input-kcen | 411.3 ± 5.4 | 407.0 | 422.7 | 218.86 ± 30.47 |
| kcen | input-mikofo | 525.0 ± 4.1 | 520.2 | 531.4 | 279.34 ± 38.78 |
| mikofo | input-mattcl | 1400.2 ± 35.8 | 1369.5 | 1439.5 | 745.09 ± 105.01 |
| mikofo | input-lanjian | 1480.4 ± 9.1 | 1472.3 | 1490.2 | 787.74 ± 109.29 |
| mikofo | input-kcen | 1690.4 ± 51.0 | 1631.6 | 1721.9 | 899.49 ± 127.59 |
| mikofo | input-mikofo | 2096.5 ± 56.2 | 2049.4 | 2158.6 | 1115.57 ± 157.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|