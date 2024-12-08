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
| mattcl | input-mattcl | 2.0 ± 0.2 | 1.6 | 2.9 | 1.00 |
| mattcl | input-lanjian | 2.1 ± 0.2 | 1.7 | 3.4 | 1.02 ± 0.14 |
| mattcl | input-kcen | 2.2 ± 0.2 | 1.7 | 3.3 | 1.06 ± 0.14 |
| mattcl | input-mikofo | 2.4 ± 0.2 | 2.1 | 3.5 | 1.20 ± 0.16 |
| lanjian | input-mattcl | 40.8 ± 1.1 | 39.1 | 44.0 | 20.11 ± 2.02 |
| lanjian | input-lanjian | 44.8 ± 0.9 | 43.3 | 47.6 | 22.08 ± 2.19 |
| lanjian | input-kcen | 48.0 ± 1.1 | 46.6 | 53.3 | 23.65 ± 2.36 |
| lanjian | input-mikofo | 68.2 ± 1.0 | 66.6 | 70.6 | 33.63 ± 3.30 |
| mattcl-py | input-mattcl | 93.9 ± 1.1 | 91.3 | 96.0 | 46.28 ± 4.53 |
| mattcl-py | input-lanjian | 101.0 ± 1.1 | 99.0 | 102.6 | 49.79 ± 4.86 |
| mattcl-py | input-kcen | 108.1 ± 1.5 | 105.6 | 111.8 | 53.29 ± 5.23 |
| mattcl-py | input-mikofo | 145.1 ± 4.6 | 140.5 | 156.6 | 71.52 ± 7.31 |
| kcen | input-mattcl | 348.0 ± 6.4 | 340.3 | 359.3 | 171.54 ± 16.95 |
| kcen | input-lanjian | 355.4 ± 2.8 | 349.8 | 359.0 | 175.14 ± 17.06 |
| kcen | input-kcen | 407.0 ± 6.6 | 399.4 | 419.5 | 200.60 ± 19.75 |
| kcen | input-mikofo | 525.2 ± 6.2 | 518.3 | 534.5 | 258.86 ± 25.31 |
| mikofo | input-mattcl | 1403.6 ± 54.8 | 1353.3 | 1461.9 | 691.76 ± 72.38 |
| mikofo | input-lanjian | 1476.5 ± 41.3 | 1451.6 | 1524.3 | 727.73 ± 73.53 |
| mikofo | input-kcen | 1678.1 ± 57.0 | 1614.2 | 1723.9 | 827.09 ± 85.08 |
| mikofo | input-mikofo | 2090.3 ± 32.0 | 2054.1 | 2114.7 | 1030.21 ± 101.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|