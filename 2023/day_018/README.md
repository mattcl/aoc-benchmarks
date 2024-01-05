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
| lanjian | input-pting | 925.5 ± 199.9 | 208.4 | 1653.0 | 1.00 |
| lanjian | input-kcen | 953.1 ± 196.1 | 249.8 | 1545.3 | 1.03 ± 0.31 |
| lanjian | input-mattcl | 959.9 ± 150.6 | 476.0 | 1246.0 | 1.04 ± 0.28 |
| lanjian | input-lanjian | 980.0 ± 139.4 | 528.0 | 1284.5 | 1.06 ± 0.27 |
| mattcl | input-lanjian | 999.7 ± 181.0 | 306.7 | 1616.3 | 1.08 ± 0.30 |
| mattcl | input-kcen | 1011.3 ± 140.8 | 538.3 | 1182.1 | 1.09 ± 0.28 |
| mattcl | input-pting | 1019.6 ± 132.8 | 367.9 | 1573.7 | 1.10 ± 0.28 |
| mattcl | input-mattcl | 1020.3 ± 167.3 | 299.7 | 1550.1 | 1.10 ± 0.30 |
| mattcl-py | input-pting | 14463.1 ± 737.2 | 13515.0 | 17920.4 | 15.63 ± 3.47 |
| pting | input-pting | 14600.5 ± 595.7 | 13612.5 | 17564.0 | 15.78 ± 3.47 |
| mattcl-py | input-lanjian | 14605.8 ± 1874.0 | 13533.4 | 39185.9 | 15.78 ± 3.97 |
| mattcl-py | input-kcen | 14762.1 ± 548.7 | 13678.6 | 17418.7 | 15.95 ± 3.50 |
| mattcl-py | input-mattcl | 14883.8 ± 755.6 | 13802.0 | 17809.6 | 16.08 ± 3.57 |
| pting | input-lanjian | 15091.6 ± 3882.4 | 13520.6 | 59155.0 | 16.31 ± 5.48 |
| pting | input-mattcl | 15104.4 ± 543.8 | 14243.3 | 17630.7 | 16.32 ± 3.57 |
| pting | input-kcen | 15107.3 ± 624.7 | 13897.5 | 18152.7 | 16.32 ± 3.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|