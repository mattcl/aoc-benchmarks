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
| mattcl | input-mattcl | 2.1 ± 0.3 | 1.6 | 4.9 | 1.00 |
| mattcl | input-lanjian | 2.1 ± 0.3 | 1.6 | 4.2 | 1.01 ± 0.19 |
| mattcl | input-kcen | 2.2 ± 0.2 | 1.8 | 4.3 | 1.05 ± 0.19 |
| mattcl | input-mikofo | 2.4 ± 0.2 | 2.2 | 3.7 | 1.18 ± 0.18 |
| lanjian | input-mattcl | 38.1 ± 1.2 | 36.4 | 42.8 | 18.53 ± 2.64 |
| lanjian | input-lanjian | 41.5 ± 1.0 | 40.2 | 44.3 | 20.22 ± 2.85 |
| lanjian | input-kcen | 44.7 ± 1.1 | 43.0 | 47.5 | 21.75 ± 3.07 |
| lanjian | input-mikofo | 62.7 ± 1.2 | 60.8 | 65.2 | 30.54 ± 4.29 |
| mattcl-py | input-mattcl | 96.6 ± 2.3 | 93.1 | 101.5 | 47.03 ± 6.64 |
| mattcl-py | input-lanjian | 103.2 ± 2.2 | 99.1 | 108.0 | 50.28 ± 7.07 |
| mattcl-py | input-kcen | 108.6 ± 1.7 | 105.6 | 112.2 | 52.92 ± 7.41 |
| mattcl-py | input-mikofo | 145.5 ± 3.6 | 141.0 | 155.1 | 70.86 ± 10.01 |
| kcen | input-mattcl | 342.1 ± 2.5 | 338.6 | 346.2 | 166.64 ± 23.20 |
| kcen | input-lanjian | 355.1 ± 4.8 | 349.7 | 360.9 | 172.98 ± 24.16 |
| kcen | input-kcen | 402.0 ± 2.4 | 398.4 | 405.1 | 195.81 ± 27.25 |
| kcen | input-mikofo | 523.0 ± 4.9 | 517.9 | 530.6 | 254.75 ± 35.50 |
| mikofo | input-mattcl | 1440.9 ± 54.2 | 1378.4 | 1473.5 | 701.83 ± 101.09 |
| mikofo | input-lanjian | 1500.2 ± 20.6 | 1477.1 | 1516.5 | 730.70 ± 102.08 |
| mikofo | input-kcen | 1696.1 ± 29.0 | 1666.1 | 1723.9 | 826.09 ± 115.72 |
| mikofo | input-mikofo | 2103.1 ± 41.4 | 2063.8 | 2146.4 | 1024.33 ± 143.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|