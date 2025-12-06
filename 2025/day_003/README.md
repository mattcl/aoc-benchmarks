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
| whyando | input-mattcl | 518.3 ± 172.7 | 0.0 | 1056.2 | 1.00 |
| whyando | input-lanjian | 532.4 ± 130.7 | 0.0 | 919.5 | 1.03 ± 0.43 |
| whyando | input-whyando | 537.7 ± 177.5 | 0.0 | 1205.5 | 1.04 ± 0.49 |
| mattcl | input-whyando | 548.5 ± 168.1 | 0.0 | 1079.6 | 1.06 ± 0.48 |
| mattcl | input-lanjian | 551.8 ± 150.2 | 0.0 | 949.0 | 1.06 ± 0.46 |
| mattcl | input-mattcl | 563.2 ± 178.3 | 0.0 | 1231.9 | 1.09 ± 0.50 |
| kcen | input-mattcl | 945.2 ± 160.1 | 203.8 | 1503.4 | 1.82 ± 0.68 |
| kcen | input-whyando | 950.9 ± 160.7 | 280.6 | 1527.2 | 1.83 ± 0.69 |
| kcen | input-lanjian | 951.7 ± 172.0 | 347.9 | 1499.3 | 1.84 ± 0.70 |
| lanjian | input-mattcl | 8578.6 ± 71.6 | 8360.9 | 8878.9 | 16.55 ± 5.52 |
| lanjian | input-lanjian | 8608.5 ± 187.9 | 8400.8 | 10506.3 | 16.61 ± 5.55 |
| lanjian | input-whyando | 8611.8 ± 226.8 | 8311.9 | 11461.3 | 16.62 ± 5.55 |
| mattcl-py | input-lanjian | 21141.8 ± 623.2 | 20037.8 | 23748.8 | 40.79 ± 13.65 |
| mattcl-py | input-mattcl | 21271.1 ± 798.1 | 19722.9 | 24667.2 | 41.04 ± 13.76 |
| mattcl-py | input-whyando | 21365.2 ± 806.3 | 19963.3 | 24562.9 | 41.22 ± 13.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|