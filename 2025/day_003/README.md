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
| whyando | input-lanjian | 248.9 ± 273.1 | 0.0 | 985.8 | 1.00 |
| whyando | input-whyando | 521.0 ± 211.0 | 0.0 | 798.3 | 2.09 ± 2.45 |
| whyando | input-mattcl | 544.2 ± 200.6 | 0.0 | 825.7 | 2.19 ± 2.53 |
| mattcl | input-whyando | 552.3 ± 221.3 | 0.0 | 872.1 | 2.22 ± 2.59 |
| mattcl | input-mattcl | 564.3 ± 195.0 | 0.0 | 832.4 | 2.27 ± 2.61 |
| mattcl | input-lanjian | 569.6 ± 175.5 | 0.0 | 1159.4 | 2.29 ± 2.61 |
| kcen | input-mattcl | 720.7 ± 307.8 | 0.0 | 1224.2 | 2.90 ± 3.41 |
| kcen | input-lanjian | 954.8 ± 158.0 | 407.2 | 1473.4 | 3.84 ± 4.26 |
| kcen | input-whyando | 978.1 ± 152.2 | 417.7 | 1175.9 | 3.93 ± 4.36 |
| lanjian | input-lanjian | 4074.8 ± 271.6 | 3408.4 | 4861.3 | 16.37 ± 18.00 |
| lanjian | input-mattcl | 4235.7 ± 311.3 | 3450.1 | 5069.5 | 17.02 ± 18.72 |
| lanjian | input-whyando | 4289.4 ± 304.6 | 3566.1 | 5053.6 | 17.24 ± 18.95 |
| mattcl-py | input-lanjian | 21571.5 ± 727.2 | 20298.3 | 24132.4 | 86.68 ± 95.16 |
| mattcl-py | input-mattcl | 22189.6 ± 437.0 | 21117.7 | 24399.3 | 89.16 ± 97.85 |
| mattcl-py | input-whyando | 22390.1 ± 487.1 | 21217.6 | 24731.5 | 89.97 ± 98.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|