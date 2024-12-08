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
| mattcl | input-mattcl | 2.1 ± 0.2 | 1.6 | 3.1 | 1.00 |
| mattcl | input-lanjian | 2.1 ± 0.2 | 1.6 | 3.0 | 1.00 ± 0.14 |
| mattcl | input-kcen | 2.2 ± 0.2 | 1.7 | 3.4 | 1.07 ± 0.15 |
| mattcl | input-mikofo | 2.5 ± 0.3 | 2.1 | 4.8 | 1.20 ± 0.19 |
| lanjian | input-mattcl | 40.8 ± 1.2 | 39.3 | 43.8 | 19.77 ± 2.15 |
| lanjian | input-lanjian | 45.0 ± 1.1 | 43.4 | 48.4 | 21.79 ± 2.35 |
| lanjian | input-kcen | 48.6 ± 1.0 | 46.7 | 51.2 | 23.56 ± 2.52 |
| lanjian | input-mikofo | 69.0 ± 1.0 | 66.7 | 71.0 | 33.45 ± 3.55 |
| mattcl-py | input-mattcl | 95.8 ± 1.2 | 93.1 | 98.0 | 46.41 ± 4.91 |
| mattcl-py | input-lanjian | 102.3 ± 1.5 | 100.4 | 106.2 | 49.58 ± 5.26 |
| mattcl-py | input-kcen | 108.9 ± 1.3 | 106.7 | 111.7 | 52.76 ± 5.58 |
| mattcl-py | input-mikofo | 146.1 ± 3.6 | 141.8 | 154.5 | 70.77 ± 7.63 |
| kcen | input-mattcl | 343.8 ± 2.2 | 341.2 | 347.1 | 166.59 ± 17.53 |
| kcen | input-lanjian | 355.7 ± 4.0 | 350.8 | 361.8 | 172.37 ± 18.20 |
| kcen | input-kcen | 403.6 ± 4.9 | 395.0 | 411.1 | 195.56 ± 20.67 |
| kcen | input-mikofo | 530.3 ± 7.6 | 522.1 | 542.2 | 256.96 ± 27.23 |
| mikofo | input-mattcl | 1442.0 ± 17.9 | 1422.0 | 1456.4 | 698.72 ± 73.88 |
| mikofo | input-lanjian | 1502.3 ± 34.3 | 1466.7 | 1535.1 | 727.94 ± 78.23 |
| mikofo | input-kcen | 1719.4 ± 31.8 | 1684.0 | 1745.5 | 833.15 ± 88.84 |
| mikofo | input-mikofo | 2117.6 ± 11.8 | 2106.7 | 2130.2 | 1026.11 ± 107.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|