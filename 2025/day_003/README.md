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
| whyando | input-mattcl | 652.6 ± 138.0 | 34.4 | 1102.7 | 1.00 |
| whyando | input-whyando | 658.6 ± 166.3 | 0.0 | 1315.5 | 1.01 ± 0.33 |
| whyando | input-lanjian | 677.6 ± 182.0 | 0.0 | 1195.2 | 1.04 ± 0.35 |
| kcen | input-mattcl | 886.1 ± 187.6 | 0.0 | 1507.4 | 1.36 ± 0.41 |
| kcen | input-whyando | 930.0 ± 143.0 | 497.7 | 1462.5 | 1.43 ± 0.37 |
| kcen | input-lanjian | 938.9 ± 187.3 | 0.0 | 1574.1 | 1.44 ± 0.42 |
| mattcl | input-mattcl | 1017.7 ± 195.9 | 424.0 | 1788.0 | 1.56 ± 0.45 |
| mattcl | input-whyando | 1033.5 ± 170.2 | 485.9 | 1697.4 | 1.58 ± 0.42 |
| mattcl | input-lanjian | 1072.6 ± 231.0 | 132.0 | 1970.8 | 1.64 ± 0.50 |
| lanjian | input-mattcl | 1311.9 ± 280.2 | 780.1 | 2424.3 | 2.01 ± 0.60 |
| lanjian | input-lanjian | 1326.5 ± 257.8 | 874.8 | 2398.4 | 2.03 ± 0.58 |
| lanjian | input-whyando | 1337.9 ± 306.1 | 784.1 | 2442.7 | 2.05 ± 0.64 |
| mattcl-py | input-lanjian | 21019.5 ± 668.1 | 19793.5 | 24523.2 | 32.21 ± 6.89 |
| mattcl-py | input-mattcl | 21052.9 ± 739.0 | 19771.7 | 23994.8 | 32.26 ± 6.91 |
| mattcl-py | input-whyando | 21128.9 ± 740.0 | 19984.7 | 24028.5 | 32.38 ± 6.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|