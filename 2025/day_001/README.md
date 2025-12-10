# Day 1 benchmarks

[link to problem](https://adventofcode.com/2025/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-whyando | 159.0 ± 223.7 | 0.0 | 729.6 | 1.00 |
| lanjian | input-whyando | 391.3 ± 265.4 | 0.0 | 983.3 | 2.46 ± 3.84 |
| kcen | input-whyando | 484.4 ± 272.7 | 0.0 | 1030.0 | 3.05 ± 4.62 |
| mattcl | input-mattcl | 518.3 ± 187.3 | 0.0 | 1033.9 | 3.26 ± 4.74 |
| whyando | input-lanjian | 550.3 ± 133.6 | 61.5 | 869.9 | 3.46 ± 4.94 |
| whyando | input-mattcl | 551.2 ± 166.2 | 0.0 | 983.9 | 3.47 ± 4.99 |
| mattcl | input-lanjian | 560.9 ± 176.9 | 0.0 | 1048.8 | 3.53 ± 5.09 |
| whyando | input-whyando | 582.5 ± 163.9 | 0.0 | 1050.9 | 3.66 ± 5.26 |
| kcen | input-mattcl | 851.0 ± 167.4 | 0.0 | 1306.6 | 5.35 ± 7.61 |
| lanjian | input-mattcl | 871.5 ± 166.3 | 0.0 | 1404.8 | 5.48 ± 7.78 |
| lanjian | input-lanjian | 874.5 ± 134.4 | 304.7 | 1337.4 | 5.50 ± 7.79 |
| kcen | input-lanjian | 892.3 ± 174.5 | 229.7 | 1503.8 | 5.61 ± 7.98 |
| mattcl-py | input-whyando | 18344.3 ± 654.0 | 17056.6 | 21193.0 | 115.38 ± 162.44 |
| mattcl-py | input-lanjian | 18365.6 ± 620.1 | 17411.7 | 21351.5 | 115.52 ± 162.62 |
| mattcl-py | input-mattcl | 18389.7 ± 765.5 | 17155.2 | 22470.4 | 115.67 ± 162.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|