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
| mattcl | input-mattcl | 1.9 ± 0.2 | 1.3 | 2.6 | 1.00 |
| mattcl | input-lanjian | 1.9 ± 0.3 | 1.4 | 3.0 | 1.02 ± 0.19 |
| mattcl | input-kcen | 2.0 ± 0.2 | 1.5 | 2.6 | 1.04 ± 0.18 |
| mattcl | input-mikofo | 2.1 ± 0.2 | 1.7 | 3.5 | 1.12 ± 0.19 |
| lanjian | input-mattcl | 38.7 ± 1.1 | 37.2 | 41.5 | 20.39 ± 2.66 |
| lanjian | input-lanjian | 42.5 ± 1.8 | 40.5 | 54.2 | 22.36 ± 3.01 |
| lanjian | input-kcen | 45.6 ± 1.1 | 43.7 | 48.1 | 24.01 ± 3.11 |
| lanjian | input-mikofo | 64.0 ± 1.0 | 62.2 | 65.9 | 33.71 ± 4.33 |
| mattcl-py | input-mattcl | 95.7 ± 1.2 | 92.6 | 98.3 | 50.40 ± 6.45 |
| mattcl-py | input-lanjian | 102.4 ± 1.3 | 100.2 | 106.0 | 53.97 ± 6.91 |
| mattcl-py | input-kcen | 109.4 ± 1.6 | 106.6 | 112.9 | 57.65 ± 7.39 |
| mattcl-py | input-mikofo | 146.0 ± 3.3 | 141.0 | 154.5 | 76.91 ± 9.95 |
| kcen | input-mattcl | 349.6 ± 1.9 | 348.0 | 354.0 | 184.15 ± 23.48 |
| kcen | input-lanjian | 358.1 ± 2.6 | 355.3 | 361.8 | 188.66 ± 24.07 |
| kcen | input-kcen | 406.9 ± 2.1 | 404.3 | 410.5 | 214.36 ± 27.33 |
| kcen | input-mikofo | 531.7 ± 3.0 | 527.0 | 534.3 | 280.09 ± 35.71 |
| mikofo | input-mattcl | 1423.9 ± 42.8 | 1376.1 | 1458.5 | 750.04 ± 98.16 |
| mikofo | input-lanjian | 1526.2 ± 56.5 | 1466.6 | 1579.0 | 803.97 ± 106.65 |
| mikofo | input-kcen | 1742.3 ± 29.2 | 1708.6 | 1760.9 | 917.80 ± 117.92 |
| mikofo | input-mikofo | 2117.6 ± 30.8 | 2090.5 | 2151.0 | 1115.46 ± 143.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5145</pre>|<pre>1523</pre>|
|input-lanjian|<pre>4752</pre>|<pre>1719</pre>|
|input-mattcl|<pre>4663</pre>|<pre>1530</pre>|
|input-mikofo|<pre>5453</pre>|<pre>2188</pre>|