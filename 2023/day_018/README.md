# Day 18 benchmarks

[link to problem](https://adventofcode.com/2023/day/18)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 18)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-lanjian | 944.7 ± 235.7 | 186.3 | 1719.9 | 1.00 |
| lanjian | input-pting | 966.0 ± 192.3 | 226.1 | 1168.1 | 1.02 ± 0.33 |
| mattcl | input-lanjian | 979.8 ± 229.7 | 216.0 | 1597.8 | 1.04 ± 0.36 |
| lanjian | input-kcen | 980.6 ± 183.2 | 263.4 | 1694.3 | 1.04 ± 0.32 |
| mattcl | input-kcen | 1006.6 ± 169.0 | 249.7 | 1209.0 | 1.07 ± 0.32 |
| mattcl | input-mattcl | 1007.9 ± 205.5 | 232.1 | 1536.8 | 1.07 ± 0.34 |
| lanjian | input-mattcl | 1018.6 ± 155.4 | 282.0 | 1322.2 | 1.08 ± 0.32 |
| mattcl | input-pting | 1019.4 ± 174.1 | 208.8 | 1706.8 | 1.08 ± 0.33 |
| mattcl-py | input-pting | 14749.2 ± 676.9 | 13601.7 | 17664.4 | 15.61 ± 3.96 |
| mattcl-py | input-lanjian | 14830.6 ± 748.1 | 13725.5 | 18655.6 | 15.70 ± 4.00 |
| pting | input-pting | 14938.0 ± 646.6 | 13909.2 | 17607.6 | 15.81 ± 4.00 |
| mattcl-py | input-mattcl | 15011.4 ± 579.1 | 13882.8 | 18571.0 | 15.89 ± 4.01 |
| pting | input-lanjian | 15069.3 ± 664.2 | 14014.7 | 18308.3 | 15.95 ± 4.04 |
| mattcl-py | input-kcen | 15155.2 ± 593.2 | 14088.6 | 18373.9 | 16.04 ± 4.05 |
| pting | input-mattcl | 15210.4 ± 624.2 | 14021.0 | 18729.9 | 16.10 ± 4.07 |
| pting | input-kcen | 15408.6 ± 679.1 | 14433.9 | 18372.1 | 16.31 ± 4.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|