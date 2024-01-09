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
| lanjian | input-mattcl | 923.3 ± 198.9 | 174.0 | 1245.0 | 1.00 |
| mattcl | input-mattcl | 939.0 ± 202.9 | 248.0 | 1210.4 | 1.02 ± 0.31 |
| lanjian | input-lanjian | 946.8 ± 180.4 | 234.0 | 1302.5 | 1.03 ± 0.29 |
| lanjian | input-kcen | 950.3 ± 156.3 | 240.5 | 1113.9 | 1.03 ± 0.28 |
| lanjian | input-pting | 954.9 ± 163.3 | 225.5 | 1258.3 | 1.03 ± 0.28 |
| mattcl | input-lanjian | 975.0 ± 145.0 | 542.4 | 1176.9 | 1.06 ± 0.28 |
| mattcl | input-pting | 987.5 ± 153.3 | 289.5 | 1480.1 | 1.07 ± 0.28 |
| mattcl | input-kcen | 989.2 ± 171.7 | 292.7 | 1413.5 | 1.07 ± 0.30 |
| mattcl-py | input-pting | 14375.6 ± 576.2 | 13292.6 | 17416.1 | 15.57 ± 3.41 |
| mattcl-py | input-lanjian | 14418.7 ± 646.2 | 13588.2 | 18200.4 | 15.62 ± 3.44 |
| pting | input-pting | 14596.8 ± 600.7 | 13609.5 | 18393.3 | 15.81 ± 3.47 |
| pting | input-lanjian | 14604.4 ± 468.1 | 13639.4 | 17069.2 | 15.82 ± 3.44 |
| mattcl-py | input-mattcl | 14804.4 ± 614.9 | 13765.0 | 17898.5 | 16.03 ± 3.52 |
| mattcl-py | input-kcen | 14990.0 ± 2517.8 | 13776.2 | 49133.9 | 16.23 ± 4.43 |
| pting | input-mattcl | 15096.2 ± 565.9 | 14084.1 | 17922.1 | 16.35 ± 3.57 |
| pting | input-kcen | 15536.2 ± 4603.9 | 13885.1 | 61309.8 | 16.83 ± 6.16 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|