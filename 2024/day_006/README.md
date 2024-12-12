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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.5 | 2.5 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.3 | 1.4 | 2.6 | 1.03 ± 0.18 |
| mattcl | input-kcen | 2.0 ± 0.3 | 1.5 | 4.3 | 1.05 ± 0.20 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.6 | 3.2 | 1.14 ± 0.18 |
| lanjian | input-mattcl | 38.5 ± 0.8 | 37.4 | 42.1 | 20.46 ± 2.48 |
| lanjian | input-lanjian | 42.7 ± 1.2 | 40.8 | 45.7 | 22.70 ± 2.77 |
| lanjian | input-kcen | 46.4 ± 1.2 | 44.5 | 50.6 | 24.69 ± 3.01 |
| lanjian | input-mikofo | 64.4 ± 1.3 | 62.5 | 66.7 | 34.26 ± 4.14 |
| mattcl-py | input-mattcl | 95.4 ± 1.2 | 92.8 | 98.0 | 50.76 ± 6.08 |
| mattcl-py | input-lanjian | 103.1 ± 1.9 | 98.6 | 106.8 | 54.85 ± 6.61 |
| mattcl-py | input-kcen | 109.2 ± 1.4 | 106.2 | 112.3 | 58.12 ± 6.97 |
| mattcl-py | input-mikofo | 146.0 ± 3.5 | 141.6 | 154.8 | 77.69 ± 9.44 |
| kcen | input-mattcl | 200.9 ± 3.6 | 196.8 | 208.0 | 106.88 ± 12.88 |
| kcen | input-lanjian | 210.2 ± 4.6 | 199.9 | 217.6 | 111.84 ± 13.55 |
| kcen | input-kcen | 244.8 ± 3.5 | 240.8 | 252.4 | 130.22 ± 15.63 |
| kcen | input-mikofo | 297.7 ± 6.1 | 291.1 | 311.3 | 158.40 ± 19.15 |
| mikofo | input-mattcl | 1425.5 ± 25.6 | 1399.3 | 1450.5 | 758.39 ± 91.39 |
| mikofo | input-lanjian | 1525.0 ± 26.3 | 1496.3 | 1548.0 | 811.35 ± 97.68 |
| mikofo | input-kcen | 1740.1 ± 46.9 | 1687.0 | 1775.9 | 925.76 ± 113.10 |
| mikofo | input-mikofo | 2171.7 ± 23.7 | 2144.4 | 2187.6 | 1155.35 ± 138.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|