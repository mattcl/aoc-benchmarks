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
| mattcl | input-pting | 644.1 ± 279.2 | 110.7 | 1140.2 | 1.00 |
| lanjian | input-pting | 890.9 ± 212.0 | 160.9 | 1695.0 | 1.38 ± 0.68 |
| lanjian | input-lanjian | 922.2 ± 160.1 | 246.2 | 1643.0 | 1.43 ± 0.67 |
| lanjian | input-kcen | 927.5 ± 151.5 | 166.8 | 1131.1 | 1.44 ± 0.67 |
| lanjian | input-mattcl | 928.1 ± 159.7 | 485.6 | 1588.3 | 1.44 ± 0.67 |
| mattcl | input-mattcl | 930.0 ± 176.2 | 204.6 | 1407.9 | 1.44 ± 0.68 |
| mattcl | input-kcen | 938.1 ± 178.6 | 164.3 | 1486.8 | 1.46 ± 0.69 |
| mattcl | input-lanjian | 939.7 ± 150.4 | 433.5 | 1335.0 | 1.46 ± 0.67 |
| mattcl-py | input-lanjian | 14712.8 ± 656.9 | 13755.6 | 17985.7 | 22.84 ± 9.95 |
| pting | input-pting | 14814.7 ± 686.0 | 14014.7 | 18366.7 | 23.00 ± 10.03 |
| mattcl-py | input-pting | 14930.5 ± 830.7 | 13794.6 | 18229.0 | 23.18 ± 10.13 |
| pting | input-lanjian | 14934.8 ± 680.6 | 13648.6 | 18091.0 | 23.19 ± 10.10 |
| mattcl-py | input-mattcl | 14959.3 ± 524.7 | 13855.0 | 17758.8 | 23.22 ± 10.10 |
| mattcl-py | input-kcen | 14959.9 ± 540.1 | 14156.2 | 17622.1 | 23.23 ± 10.10 |
| pting | input-mattcl | 15249.2 ± 696.8 | 14208.3 | 18669.2 | 23.67 ± 10.32 |
| pting | input-kcen | 15263.3 ± 632.7 | 14199.1 | 18390.0 | 23.70 ± 10.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|