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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.3 | 2.5 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 2.6 | 1.02 ± 0.19 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.6 | 1.05 ± 0.19 |
| mattcl | input-mikofo | 2.1 ± 0.3 | 1.6 | 4.5 | 1.13 ± 0.21 |
| lanjian | input-mattcl | 37.8 ± 1.0 | 36.4 | 41.0 | 20.29 ± 2.74 |
| lanjian | input-lanjian | 41.8 ± 1.0 | 40.4 | 44.6 | 22.41 ± 3.02 |
| lanjian | input-kcen | 45.3 ± 1.2 | 43.7 | 50.0 | 24.27 ± 3.27 |
| lanjian | input-mikofo | 63.0 ± 1.2 | 60.8 | 66.1 | 33.81 ± 4.52 |
| mattcl-py | input-mattcl | 93.9 ± 1.0 | 91.7 | 96.0 | 50.38 ± 6.69 |
| mattcl-py | input-lanjian | 101.2 ± 1.6 | 98.6 | 103.7 | 54.26 ± 7.23 |
| mattcl-py | input-kcen | 108.0 ± 1.5 | 105.7 | 111.8 | 57.92 ± 7.71 |
| mattcl-py | input-mikofo | 142.8 ± 3.1 | 138.3 | 150.1 | 76.56 ± 10.27 |
| kcen | input-mattcl | 197.4 ± 4.7 | 189.5 | 207.2 | 105.88 ± 14.25 |
| kcen | input-lanjian | 205.1 ± 3.1 | 199.9 | 210.7 | 109.98 ± 14.65 |
| kcen | input-kcen | 240.3 ± 4.2 | 232.5 | 245.6 | 128.85 ± 17.21 |
| kcen | input-mikofo | 290.0 ± 7.8 | 277.8 | 302.5 | 155.55 ± 21.02 |
| mikofo | input-mattcl | 1397.3 ± 36.9 | 1355.2 | 1423.7 | 749.36 ± 101.17 |
| mikofo | input-lanjian | 1453.9 ± 43.8 | 1410.0 | 1497.6 | 779.71 ± 105.88 |
| mikofo | input-kcen | 1682.1 ± 37.9 | 1639.6 | 1712.2 | 902.13 ± 121.17 |
| mikofo | input-mikofo | 2047.1 ± 21.2 | 2027.9 | 2069.9 | 1097.89 ± 145.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|