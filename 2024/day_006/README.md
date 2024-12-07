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
| mattcl | input-lanjian | 2.1 ± 0.3 | 1.7 | 4.2 | 1.00 |
| mattcl | input-mattcl | 2.1 ± 0.3 | 1.6 | 4.7 | 1.00 ± 0.20 |
| mattcl | input-kcen | 2.2 ± 0.2 | 1.8 | 2.8 | 1.03 ± 0.16 |
| mattcl | input-mikofo | 2.4 ± 0.2 | 2.1 | 3.4 | 1.17 ± 0.17 |
| lanjian | input-mattcl | 41.3 ± 1.3 | 39.3 | 44.1 | 19.78 ± 2.71 |
| lanjian | input-lanjian | 45.1 ± 1.2 | 43.2 | 48.2 | 21.62 ± 2.93 |
| lanjian | input-kcen | 48.5 ± 1.1 | 46.5 | 52.2 | 23.22 ± 3.14 |
| lanjian | input-mikofo | 68.9 ± 0.9 | 67.1 | 70.6 | 33.01 ± 4.41 |
| mattcl-py | input-mattcl | 95.6 ± 1.3 | 93.6 | 99.2 | 45.79 ± 6.12 |
| mattcl-py | input-lanjian | 102.5 ± 1.5 | 100.1 | 105.1 | 49.14 ± 6.58 |
| mattcl-py | input-kcen | 108.9 ± 1.7 | 106.1 | 111.9 | 52.17 ± 6.99 |
| mattcl-py | input-mikofo | 146.0 ± 3.0 | 142.4 | 152.8 | 69.96 ± 9.41 |
| kcen | input-mattcl | 343.1 ± 2.7 | 339.4 | 347.8 | 164.41 ± 21.91 |
| kcen | input-lanjian | 353.3 ± 7.1 | 344.8 | 363.8 | 169.30 ± 22.77 |
| kcen | input-kcen | 401.9 ± 5.4 | 394.7 | 408.2 | 192.57 ± 25.74 |
| kcen | input-mikofo | 527.4 ± 3.7 | 521.3 | 530.2 | 252.71 ± 33.66 |
| mikofo | input-mattcl | 1423.0 ± 48.0 | 1367.9 | 1455.8 | 681.84 ± 93.55 |
| mikofo | input-lanjian | 1513.4 ± 42.0 | 1465.3 | 1542.8 | 725.18 ± 98.52 |
| mikofo | input-kcen | 1723.8 ± 34.4 | 1684.2 | 1746.8 | 825.99 ± 111.08 |
| mikofo | input-mikofo | 2112.3 ± 17.9 | 2091.9 | 2125.5 | 1012.15 ± 134.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|