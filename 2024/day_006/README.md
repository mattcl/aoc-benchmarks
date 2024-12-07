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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.5 | 2.5 | 1.00 |
| mattcl | input-lanjian | 2.1 ± 0.2 | 1.6 | 2.9 | 1.02 ± 0.14 |
| mattcl | input-kcen | 2.2 ± 0.3 | 1.8 | 4.8 | 1.08 ± 0.16 |
| mattcl | input-mikofo | 2.4 ± 0.2 | 2.0 | 4.4 | 1.20 ± 0.17 |
| lanjian | input-mattcl | 40.4 ± 0.9 | 39.1 | 43.1 | 20.03 ± 1.99 |
| lanjian | input-lanjian | 44.7 ± 1.2 | 43.0 | 47.8 | 22.19 ± 2.22 |
| lanjian | input-kcen | 48.0 ± 0.8 | 46.7 | 50.1 | 23.85 ± 2.34 |
| lanjian | input-mikofo | 67.9 ± 1.1 | 65.9 | 70.9 | 33.72 ± 3.30 |
| mattcl-py | input-mattcl | 93.5 ± 1.1 | 91.7 | 96.2 | 46.42 ± 4.51 |
| mattcl-py | input-lanjian | 101.0 ± 1.1 | 98.6 | 103.4 | 50.11 ± 4.86 |
| mattcl-py | input-kcen | 108.3 ± 1.5 | 105.3 | 111.1 | 53.76 ± 5.23 |
| mattcl-py | input-mikofo | 144.3 ± 3.3 | 139.8 | 151.4 | 71.64 ± 7.09 |
| kcen | input-mattcl | 345.5 ± 7.1 | 336.5 | 354.2 | 171.49 ± 16.90 |
| kcen | input-lanjian | 354.0 ± 3.0 | 350.1 | 358.0 | 175.69 ± 17.00 |
| kcen | input-kcen | 408.6 ± 5.9 | 399.5 | 417.8 | 202.83 ± 19.77 |
| kcen | input-mikofo | 522.0 ± 4.1 | 517.1 | 527.5 | 259.11 ± 25.06 |
| mikofo | input-mattcl | 1390.6 ± 51.0 | 1344.3 | 1445.3 | 690.29 ± 71.20 |
| mikofo | input-lanjian | 1476.5 ± 28.7 | 1446.4 | 1503.5 | 732.90 ± 72.07 |
| mikofo | input-kcen | 1700.0 ± 66.9 | 1631.6 | 1765.2 | 843.86 ± 87.87 |
| mikofo | input-mikofo | 2075.2 ± 22.6 | 2052.2 | 2097.4 | 1030.10 ± 99.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|