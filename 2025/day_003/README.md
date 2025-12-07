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
| whyando | input-lanjian | 518.8 ± 183.6 | 0.0 | 1101.6 | 1.00 |
| whyando | input-mattcl | 520.0 ± 164.1 | 0.0 | 969.9 | 1.00 ± 0.48 |
| whyando | input-whyando | 548.5 ± 157.1 | 0.0 | 1248.9 | 1.06 ± 0.48 |
| mattcl | input-mattcl | 550.8 ± 188.1 | 0.0 | 1089.8 | 1.06 ± 0.52 |
| mattcl | input-lanjian | 560.8 ± 148.9 | 0.0 | 1021.1 | 1.08 ± 0.48 |
| mattcl | input-whyando | 568.4 ± 152.4 | 0.1 | 1091.7 | 1.10 ± 0.49 |
| kcen | input-lanjian | 928.1 ± 144.8 | 426.3 | 1521.3 | 1.79 ± 0.69 |
| kcen | input-whyando | 938.9 ± 165.2 | 386.1 | 1574.9 | 1.81 ± 0.72 |
| kcen | input-mattcl | 962.2 ± 147.1 | 513.2 | 1525.7 | 1.85 ± 0.71 |
| lanjian | input-lanjian | 8599.2 ± 65.0 | 8429.5 | 8797.5 | 16.57 ± 5.87 |
| lanjian | input-whyando | 8601.2 ± 75.9 | 8397.1 | 8854.0 | 16.58 ± 5.87 |
| lanjian | input-mattcl | 8603.5 ± 82.4 | 8419.0 | 9320.4 | 16.58 ± 5.87 |
| mattcl-py | input-lanjian | 21096.2 ± 599.5 | 19921.2 | 23910.1 | 40.66 ± 14.44 |
| mattcl-py | input-mattcl | 21243.0 ± 664.0 | 20127.4 | 24050.6 | 40.94 ± 14.55 |
| mattcl-py | input-whyando | 21307.2 ± 632.4 | 20274.8 | 24549.5 | 41.07 ± 14.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|