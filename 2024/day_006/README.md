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
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.6 | 3.6 | 1.00 |
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.5 | 2.7 | 1.01 ± 0.16 |
| mattcl | input-kcen | 2.1 ± 0.3 | 1.6 | 4.4 | 1.05 ± 0.18 |
| mattcl | input-mikofo | 2.3 ± 0.2 | 1.8 | 3.0 | 1.12 ± 0.17 |
| lanjian | input-mattcl | 40.1 ± 1.0 | 38.5 | 42.6 | 19.78 ± 2.49 |
| lanjian | input-lanjian | 44.2 ± 1.4 | 42.4 | 50.5 | 21.80 ± 2.77 |
| lanjian | input-kcen | 47.5 ± 1.2 | 45.9 | 50.5 | 23.42 ± 2.94 |
| mattcl-py | input-mattcl | 58.3 ± 0.7 | 57.1 | 60.4 | 28.76 ± 3.56 |
| mattcl-py | input-lanjian | 58.9 ± 0.7 | 56.9 | 60.2 | 29.05 ± 3.60 |
| mattcl-py | input-kcen | 61.2 ± 0.8 | 59.3 | 62.8 | 30.18 ± 3.74 |
| mattcl-py | input-mikofo | 65.8 ± 0.9 | 63.6 | 68.0 | 32.43 ± 4.02 |
| lanjian | input-mikofo | 67.1 ± 1.4 | 64.3 | 70.5 | 33.09 ± 4.13 |
| kcen | input-mattcl | 196.9 ± 2.6 | 192.6 | 202.7 | 97.08 ± 12.03 |
| kcen | input-lanjian | 204.7 ± 3.8 | 199.1 | 210.8 | 100.95 ± 12.57 |
| kcen | input-kcen | 240.4 ± 5.6 | 230.7 | 250.8 | 118.54 ± 14.86 |
| kcen | input-mikofo | 291.9 ± 5.5 | 285.8 | 305.2 | 143.97 ± 17.94 |
| mikofo | input-mattcl | 1412.5 ± 42.6 | 1382.2 | 1461.1 | 696.56 ± 88.32 |
| mikofo | input-lanjian | 1488.9 ± 34.5 | 1455.1 | 1524.1 | 734.23 ± 92.02 |
| mikofo | input-kcen | 1709.9 ± 42.6 | 1661.0 | 1739.1 | 843.22 ± 105.96 |
| mikofo | input-mikofo | 2117.6 ± 17.3 | 2099.1 | 2133.4 | 1044.27 ± 128.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|