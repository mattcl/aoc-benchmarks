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
| whyando | input-whyando | 524.1 ± 202.0 | 0.0 | 1072.4 | 1.00 |
| whyando | input-lanjian | 551.5 ± 165.5 | 0.0 | 1069.6 | 1.05 ± 0.51 |
| mattcl | input-whyando | 553.9 ± 172.1 | 0.0 | 1054.8 | 1.06 ± 0.52 |
| whyando | input-mattcl | 559.8 ± 147.5 | 0.0 | 995.2 | 1.07 ± 0.50 |
| mattcl | input-lanjian | 572.3 ± 127.7 | 0.0 | 791.9 | 1.09 ± 0.49 |
| mattcl | input-mattcl | 581.6 ± 171.8 | 0.0 | 1336.2 | 1.11 ± 0.54 |
| kcen | input-lanjian | 942.4 ± 130.2 | 0.0 | 1360.5 | 1.80 ± 0.74 |
| kcen | input-whyando | 946.9 ± 156.3 | 369.3 | 1850.7 | 1.81 ± 0.76 |
| kcen | input-mattcl | 971.3 ± 175.4 | 318.0 | 1576.1 | 1.85 ± 0.79 |
| lanjian | input-mattcl | 8608.6 ± 65.1 | 8455.6 | 8833.2 | 16.42 ± 6.33 |
| lanjian | input-lanjian | 8616.3 ± 82.6 | 8478.7 | 9299.7 | 16.44 ± 6.34 |
| lanjian | input-whyando | 8622.4 ± 85.8 | 8465.5 | 8944.0 | 16.45 ± 6.34 |
| mattcl-py | input-mattcl | 21115.3 ± 488.4 | 20096.5 | 23365.0 | 40.28 ± 15.55 |
| mattcl-py | input-lanjian | 21142.4 ± 684.8 | 19950.1 | 24009.4 | 40.34 ± 15.60 |
| mattcl-py | input-whyando | 21378.3 ± 748.9 | 20147.5 | 24697.7 | 40.79 ± 15.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|