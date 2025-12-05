# Day 3 benchmarks

[link to problem](https://adventofcode.com/2025/day/3)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 3)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-mattcl | 607.9 ± 177.5 | 0.0 | 1063.2 | 1.00 |
| whyando | input-whyando | 618.6 ± 171.1 | 32.8 | 1084.1 | 1.02 ± 0.41 |
| whyando | input-lanjian | 668.6 ± 130.2 | 274.8 | 1297.7 | 1.10 ± 0.39 |
| kcen | input-mattcl | 854.4 ± 184.3 | 0.0 | 1468.8 | 1.41 ± 0.51 |
| kcen | input-whyando | 895.4 ± 122.8 | 471.8 | 1465.2 | 1.47 ± 0.47 |
| kcen | input-lanjian | 907.3 ± 130.1 | 314.4 | 1414.7 | 1.49 ± 0.49 |
| mattcl | input-lanjian | 998.3 ± 213.0 | 338.5 | 1837.4 | 1.64 ± 0.59 |
| mattcl | input-whyando | 1000.0 ± 176.7 | 35.2 | 1681.9 | 1.64 ± 0.56 |
| mattcl | input-mattcl | 1012.4 ± 232.4 | 46.3 | 1799.3 | 1.67 ± 0.62 |
| lanjian | input-lanjian | 1306.9 ± 289.5 | 804.3 | 2408.5 | 2.15 ± 0.79 |
| lanjian | input-mattcl | 1307.8 ± 269.5 | 790.3 | 2484.9 | 2.15 ± 0.77 |
| lanjian | input-whyando | 1327.2 ± 279.0 | 769.3 | 2453.0 | 2.18 ± 0.79 |
| mattcl-py | input-mattcl | 20922.2 ± 650.1 | 19833.9 | 24455.7 | 34.41 ± 10.10 |
| mattcl-py | input-lanjian | 21066.8 ± 861.4 | 19691.0 | 24604.2 | 34.65 ± 10.21 |
| mattcl-py | input-whyando | 21125.5 ± 607.5 | 20087.1 | 24115.9 | 34.75 ± 10.19 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|