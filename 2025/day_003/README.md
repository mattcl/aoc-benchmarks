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
| mattcl | input-lanjian | 574.1 ± 159.7 | 0.0 | 1066.8 | 1.00 |
| whyando | input-lanjian | 580.7 ± 142.7 | 93.9 | 1007.6 | 1.01 ± 0.38 |
| whyando | input-whyando | 584.1 ± 162.0 | 0.0 | 1042.3 | 1.02 ± 0.40 |
| whyando | input-mattcl | 605.1 ± 141.0 | 114.2 | 1200.8 | 1.05 ± 0.38 |
| mattcl | input-whyando | 616.9 ± 147.4 | 45.4 | 985.6 | 1.07 ± 0.39 |
| mattcl | input-mattcl | 620.4 ± 175.5 | 95.3 | 1327.4 | 1.08 ± 0.43 |
| kcen | input-whyando | 938.3 ± 122.2 | 431.2 | 1385.2 | 1.63 ± 0.50 |
| kcen | input-mattcl | 957.1 ± 163.9 | 224.8 | 1642.2 | 1.67 ± 0.54 |
| kcen | input-lanjian | 961.4 ± 114.4 | 533.2 | 1488.5 | 1.67 ± 0.51 |
| lanjian | input-mattcl | 4049.1 ± 315.7 | 3397.9 | 4961.9 | 7.05 ± 2.04 |
| lanjian | input-lanjian | 4076.3 ± 311.3 | 3361.2 | 5159.5 | 7.10 ± 2.05 |
| lanjian | input-whyando | 4092.9 ± 287.6 | 3441.8 | 4893.5 | 7.13 ± 2.04 |
| mattcl-py | input-lanjian | 21099.0 ± 799.1 | 20113.0 | 24473.0 | 36.75 ± 10.31 |
| mattcl-py | input-mattcl | 21151.4 ± 816.6 | 20006.8 | 24635.9 | 36.84 ± 10.34 |
| mattcl-py | input-whyando | 21345.8 ± 641.3 | 20385.5 | 24560.6 | 37.18 ± 10.40 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|