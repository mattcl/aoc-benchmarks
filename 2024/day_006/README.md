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
| mattcl | input-mattcl | 2.0 ± 0.3 | 1.6 | 4.2 | 1.00 |
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.6 | 3.0 | 1.00 ± 0.16 |
| mattcl | input-kcen | 2.2 ± 0.3 | 1.6 | 4.0 | 1.06 ± 0.19 |
| mattcl | input-mikofo | 2.4 ± 0.4 | 2.1 | 5.7 | 1.20 ± 0.23 |
| lanjian | input-mattcl | 40.5 ± 1.1 | 39.2 | 44.8 | 19.93 ± 2.61 |
| lanjian | input-lanjian | 44.5 ± 0.9 | 43.0 | 47.4 | 21.87 ± 2.83 |
| lanjian | input-kcen | 48.3 ± 1.2 | 46.7 | 53.5 | 23.75 ± 3.09 |
| lanjian | input-mikofo | 67.6 ± 0.7 | 66.3 | 69.3 | 33.23 ± 4.26 |
| mattcl-py | input-mattcl | 93.8 ± 1.3 | 91.8 | 97.1 | 46.13 ± 5.93 |
| mattcl-py | input-lanjian | 100.6 ± 1.1 | 98.5 | 103.0 | 49.47 ± 6.35 |
| mattcl-py | input-kcen | 107.3 ± 1.4 | 104.5 | 109.9 | 52.76 ± 6.78 |
| mattcl-py | input-mikofo | 142.9 ± 4.1 | 139.3 | 153.9 | 70.27 ± 9.20 |
| kcen | input-mattcl | 349.0 ± 4.6 | 341.2 | 353.9 | 171.61 ± 22.06 |
| kcen | input-lanjian | 360.0 ± 1.7 | 357.3 | 362.2 | 177.05 ± 22.65 |
| kcen | input-kcen | 412.8 ± 8.9 | 406.1 | 431.3 | 203.00 ± 26.32 |
| kcen | input-mikofo | 529.1 ± 4.6 | 525.5 | 536.3 | 260.21 ± 33.35 |
| mikofo | input-mattcl | 1400.9 ± 21.1 | 1376.8 | 1415.7 | 688.92 ± 88.69 |
| mikofo | input-lanjian | 1494.8 ± 32.2 | 1459.3 | 1522.2 | 735.12 ± 95.32 |
| mikofo | input-kcen | 1692.7 ± 43.8 | 1642.5 | 1723.5 | 832.42 ± 108.59 |
| mikofo | input-mikofo | 2052.1 ± 15.7 | 2035.1 | 2065.9 | 1009.20 ± 129.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|