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
| whyando | input-mattcl | 525.8 ± 273.5 | 0.0 | 1017.6 | 1.00 |
| whyando | input-whyando | 604.0 ± 197.6 | 0.0 | 860.6 | 1.15 ± 0.71 |
| whyando | input-lanjian | 666.1 ± 166.7 | 0.0 | 868.6 | 1.27 ± 0.73 |
| kcen | input-whyando | 911.5 ± 149.3 | 474.1 | 1451.5 | 1.73 ± 0.95 |
| mattcl | input-whyando | 928.6 ± 327.1 | 0.0 | 1774.3 | 1.77 ± 1.11 |
| kcen | input-mattcl | 941.7 ± 169.1 | 0.0 | 1186.8 | 1.79 ± 0.99 |
| kcen | input-lanjian | 945.7 ± 181.6 | 62.4 | 1193.4 | 1.80 ± 1.00 |
| mattcl | input-mattcl | 1005.8 ± 193.9 | 26.4 | 1686.9 | 1.91 ± 1.06 |
| mattcl | input-lanjian | 1088.7 ± 147.4 | 462.7 | 1312.7 | 2.07 ± 1.11 |
| lanjian | input-whyando | 1333.4 ± 220.7 | 834.4 | 2499.5 | 2.54 ± 1.38 |
| lanjian | input-mattcl | 1369.2 ± 234.3 | 820.2 | 2446.1 | 2.60 ± 1.43 |
| lanjian | input-lanjian | 1389.6 ± 165.0 | 901.9 | 2570.3 | 2.64 ± 1.41 |
| mattcl-py | input-mattcl | 21113.2 ± 625.2 | 20188.0 | 23944.3 | 40.15 ± 20.92 |
| mattcl-py | input-whyando | 21305.6 ± 640.0 | 20198.8 | 23901.5 | 40.52 ± 21.11 |
| mattcl-py | input-lanjian | 21720.8 ± 654.6 | 20541.5 | 23677.7 | 41.31 ± 21.52 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|