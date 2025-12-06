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
| whyando | input-mattcl | 630.8 ± 173.6 | 0.0 | 1533.5 | 1.00 |
| whyando | input-whyando | 646.3 ± 145.0 | 159.4 | 1260.5 | 1.02 ± 0.36 |
| whyando | input-lanjian | 676.2 ± 137.1 | 215.8 | 1354.6 | 1.07 ± 0.37 |
| kcen | input-lanjian | 882.4 ± 147.3 | 384.9 | 1525.9 | 1.40 ± 0.45 |
| kcen | input-mattcl | 892.9 ± 139.2 | 352.9 | 1397.1 | 1.42 ± 0.45 |
| kcen | input-whyando | 975.2 ± 176.1 | 347.2 | 1516.9 | 1.55 ± 0.51 |
| mattcl | input-mattcl | 1032.6 ± 193.1 | 209.4 | 1791.4 | 1.64 ± 0.54 |
| mattcl | input-lanjian | 1056.8 ± 207.1 | 356.0 | 1783.0 | 1.68 ± 0.57 |
| mattcl | input-whyando | 1066.7 ± 230.8 | 70.7 | 1904.0 | 1.69 ± 0.59 |
| lanjian | input-lanjian | 1331.5 ± 261.8 | 824.8 | 2485.6 | 2.11 ± 0.71 |
| lanjian | input-whyando | 1348.4 ± 230.3 | 799.6 | 2465.4 | 2.14 ± 0.69 |
| lanjian | input-mattcl | 1367.0 ± 307.3 | 835.1 | 2566.7 | 2.17 ± 0.77 |
| mattcl-py | input-lanjian | 20967.0 ± 590.0 | 19715.0 | 23847.7 | 33.24 ± 9.19 |
| mattcl-py | input-mattcl | 21076.9 ± 754.9 | 19820.1 | 24195.9 | 33.41 ± 9.27 |
| mattcl-py | input-whyando | 21168.5 ± 623.6 | 19805.8 | 23936.6 | 33.56 ± 9.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|