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
| whyando | input-lanjian | 507.9 ± 173.0 | 0.0 | 1025.5 | 1.00 |
| whyando | input-mattcl | 528.9 ± 155.0 | 53.6 | 1018.1 | 1.04 ± 0.47 |
| mattcl | input-mattcl | 542.1 ± 179.7 | 0.0 | 1114.0 | 1.07 ± 0.51 |
| whyando | input-whyando | 543.1 ± 145.0 | 22.1 | 984.6 | 1.07 ± 0.46 |
| mattcl | input-lanjian | 555.3 ± 164.3 | 0.0 | 1138.4 | 1.09 ± 0.49 |
| mattcl | input-whyando | 563.6 ± 145.6 | 0.0 | 1017.1 | 1.11 ± 0.47 |
| kcen | input-lanjian | 877.6 ± 208.6 | 0.0 | 1482.8 | 1.73 ± 0.72 |
| kcen | input-whyando | 938.4 ± 154.9 | 527.0 | 1662.3 | 1.85 ± 0.70 |
| kcen | input-mattcl | 942.4 ± 166.1 | 0.0 | 1494.5 | 1.86 ± 0.71 |
| lanjian | input-whyando | 8596.1 ± 72.5 | 8398.8 | 8980.9 | 16.93 ± 5.77 |
| lanjian | input-mattcl | 8598.1 ± 72.3 | 8426.7 | 8813.7 | 16.93 ± 5.77 |
| lanjian | input-lanjian | 8601.3 ± 75.0 | 8438.5 | 8914.8 | 16.94 ± 5.77 |
| mattcl-py | input-lanjian | 21139.5 ± 736.3 | 19872.8 | 24542.4 | 41.62 ± 14.25 |
| mattcl-py | input-mattcl | 21158.8 ± 581.9 | 20085.5 | 23917.8 | 41.66 ± 14.24 |
| mattcl-py | input-whyando | 21323.2 ± 636.2 | 20368.5 | 24559.2 | 41.99 ± 14.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|