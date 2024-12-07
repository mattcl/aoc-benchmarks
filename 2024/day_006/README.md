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
| mattcl | input-lanjian | 2.0 ± 0.2 | 1.6 | 2.9 | 1.00 |
| mattcl | input-mattcl | 2.0 ± 0.3 | 1.6 | 4.1 | 1.00 ± 0.16 |
| mattcl | input-kcen | 2.1 ± 0.2 | 1.7 | 4.0 | 1.05 ± 0.15 |
| mattcl | input-mikofo | 2.4 ± 0.2 | 2.0 | 3.2 | 1.18 ± 0.14 |
| lanjian | input-mattcl | 40.6 ± 1.2 | 38.7 | 45.4 | 20.02 ± 1.91 |
| lanjian | input-lanjian | 44.6 ± 1.0 | 42.9 | 47.8 | 21.97 ± 2.06 |
| lanjian | input-kcen | 48.0 ± 1.3 | 46.4 | 52.2 | 23.68 ± 2.25 |
| lanjian | input-mikofo | 67.7 ± 1.2 | 65.6 | 72.0 | 33.35 ± 3.10 |
| mattcl-py | input-mattcl | 93.8 ± 1.1 | 91.6 | 95.7 | 46.26 ± 4.25 |
| mattcl-py | input-lanjian | 101.4 ± 1.3 | 98.9 | 103.8 | 49.98 ± 4.60 |
| mattcl-py | input-kcen | 107.3 ± 1.3 | 104.9 | 110.1 | 52.87 ± 4.86 |
| mattcl-py | input-mikofo | 143.5 ± 3.1 | 138.9 | 149.7 | 70.74 ± 6.62 |
| kcen | input-mattcl | 348.7 ± 6.1 | 340.8 | 359.7 | 171.88 ± 15.94 |
| kcen | input-lanjian | 352.4 ± 4.5 | 348.4 | 360.9 | 173.71 ± 15.98 |
| kcen | input-kcen | 407.1 ± 4.7 | 400.2 | 412.5 | 200.66 ± 18.43 |
| kcen | input-mikofo | 522.4 ± 3.5 | 519.6 | 528.5 | 257.48 ± 23.52 |
| mikofo | input-mattcl | 1392.1 ± 25.6 | 1371.6 | 1420.8 | 686.19 ± 63.78 |
| mikofo | input-lanjian | 1495.2 ± 28.3 | 1463.1 | 1516.6 | 736.99 ± 68.58 |
| mikofo | input-kcen | 1676.8 ± 46.0 | 1629.3 | 1721.1 | 826.54 ± 78.65 |
| mikofo | input-mikofo | 2078.9 ± 6.5 | 2072.7 | 2085.6 | 1024.71 ± 93.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|