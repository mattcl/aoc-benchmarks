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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.4 | 2.4 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.4 | 2.5 | 1.00 ± 0.16 |
| mattcl | input-kcen | 2.0 ± 0.3 | 1.5 | 3.2 | 1.05 ± 0.18 |
| mattcl | input-mikofo | 2.2 ± 0.3 | 1.7 | 4.5 | 1.13 ± 0.19 |
| lanjian | input-mattcl | 39.6 ± 1.1 | 38.0 | 42.7 | 20.74 ± 2.39 |
| lanjian | input-lanjian | 43.5 ± 0.8 | 42.1 | 46.9 | 22.79 ± 2.60 |
| lanjian | input-kcen | 47.2 ± 0.9 | 45.5 | 50.1 | 24.72 ± 2.82 |
| lanjian | input-mikofo | 66.4 ± 1.4 | 63.9 | 69.4 | 34.81 ± 3.98 |
| mattcl-py | input-mattcl | 93.9 ± 0.9 | 92.2 | 96.2 | 49.24 ± 5.55 |
| mattcl-py | input-lanjian | 101.3 ± 1.4 | 98.7 | 104.4 | 53.10 ± 6.01 |
| mattcl-py | input-kcen | 108.5 ± 1.7 | 105.4 | 112.7 | 56.91 ± 6.46 |
| mattcl-py | input-mikofo | 143.4 ± 3.2 | 139.0 | 149.9 | 75.22 ± 8.61 |
| kcen | input-mattcl | 198.1 ± 3.8 | 192.1 | 204.3 | 103.86 ± 11.83 |
| kcen | input-lanjian | 208.7 ± 4.7 | 199.4 | 218.6 | 109.41 ± 12.53 |
| kcen | input-kcen | 243.0 ± 5.4 | 237.6 | 255.8 | 127.44 ± 14.59 |
| kcen | input-mikofo | 292.5 ± 6.0 | 283.0 | 303.6 | 153.38 ± 17.51 |
| mikofo | input-mattcl | 1396.1 ± 22.5 | 1380.6 | 1421.9 | 732.05 ± 83.07 |
| mikofo | input-lanjian | 1475.2 ± 7.2 | 1467.2 | 1481.0 | 773.55 ± 86.97 |
| mikofo | input-kcen | 1688.5 ± 51.5 | 1629.2 | 1721.2 | 885.39 ± 103.05 |
| mikofo | input-mikofo | 2066.3 ± 31.5 | 2037.7 | 2100.0 | 1083.49 ± 122.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|