# Day 1 benchmarks

[link to problem](https://adventofcode.com/2025/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 517.0 ± 151.1 | 0.0 | 720.5 | 1.00 |
| whyando | input-mattcl | 527.7 ± 150.3 | 0.0 | 1033.9 | 1.02 ± 0.42 |
| mattcl | input-lanjian | 528.6 ± 169.7 | 0.0 | 993.0 | 1.02 ± 0.44 |
| whyando | input-lanjian | 529.6 ± 151.8 | 0.0 | 1046.3 | 1.02 ± 0.42 |
| mattcl | input-whyando | 537.4 ± 152.2 | 0.0 | 967.3 | 1.04 ± 0.42 |
| whyando | input-whyando | 538.1 ± 152.2 | 0.0 | 1007.0 | 1.04 ± 0.42 |
| kcen | input-whyando | 830.6 ± 145.3 | 281.9 | 1337.7 | 1.61 ± 0.55 |
| kcen | input-mattcl | 851.8 ± 145.1 | 289.8 | 1402.3 | 1.65 ± 0.56 |
| lanjian | input-lanjian | 863.4 ± 155.6 | 275.3 | 1343.6 | 1.67 ± 0.57 |
| lanjian | input-mattcl | 872.5 ± 136.2 | 325.1 | 1359.1 | 1.69 ± 0.56 |
| lanjian | input-whyando | 882.9 ± 153.1 | 338.2 | 1504.4 | 1.71 ± 0.58 |
| kcen | input-lanjian | 889.8 ± 163.7 | 316.9 | 1438.2 | 1.72 ± 0.59 |
| mattcl-py | input-mattcl | 18355.0 ± 713.0 | 17335.1 | 21333.2 | 35.50 ± 10.47 |
| mattcl-py | input-lanjian | 18411.9 ± 668.2 | 16947.6 | 21490.8 | 35.61 ± 10.49 |
| mattcl-py | input-whyando | 18441.1 ± 666.5 | 16976.2 | 21756.5 | 35.67 ± 10.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|