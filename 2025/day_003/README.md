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
| whyando | input-lanjian | 559.8 ± 185.2 | 0.0 | 1074.5 | 1.00 |
| whyando | input-whyando | 575.7 ± 144.9 | 0.0 | 1041.0 | 1.03 ± 0.43 |
| mattcl | input-lanjian | 590.7 ± 163.8 | 0.0 | 1044.0 | 1.06 ± 0.46 |
| whyando | input-mattcl | 601.7 ± 159.4 | 9.6 | 1566.4 | 1.07 ± 0.46 |
| mattcl | input-mattcl | 603.8 ± 209.2 | 0.0 | 1180.9 | 1.08 ± 0.52 |
| mattcl | input-whyando | 604.3 ± 152.9 | 0.0 | 1023.9 | 1.08 ± 0.45 |
| kcen | input-lanjian | 937.8 ± 149.5 | 384.1 | 1488.5 | 1.68 ± 0.62 |
| kcen | input-mattcl | 947.0 ± 135.1 | 436.9 | 1391.7 | 1.69 ± 0.61 |
| kcen | input-whyando | 952.9 ± 159.5 | 212.3 | 1482.4 | 1.70 ± 0.63 |
| lanjian | input-mattcl | 8628.1 ± 77.3 | 8420.5 | 8851.4 | 15.41 ± 5.10 |
| lanjian | input-whyando | 8635.1 ± 74.3 | 8454.0 | 8916.1 | 15.43 ± 5.10 |
| lanjian | input-lanjian | 8676.9 ± 340.7 | 8422.8 | 12001.8 | 15.50 ± 5.16 |
| mattcl-py | input-lanjian | 21148.1 ± 571.2 | 20221.6 | 23917.4 | 37.78 ± 12.54 |
| mattcl-py | input-mattcl | 21234.7 ± 657.3 | 20313.4 | 24298.5 | 37.93 ± 12.60 |
| mattcl-py | input-whyando | 21342.9 ± 610.5 | 20034.2 | 24439.2 | 38.13 ± 12.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|