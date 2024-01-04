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
| lanjian | input-kcen | 877.6 ± 209.6 | 138.8 | 1121.8 | 1.00 |
| lanjian | input-lanjian | 905.3 ± 191.7 | 153.1 | 1673.9 | 1.03 ± 0.33 |
| lanjian | input-mattcl | 922.0 ± 161.3 | 172.7 | 1509.9 | 1.05 ± 0.31 |
| lanjian | input-pting | 943.4 ± 102.4 | 556.0 | 1075.6 | 1.07 ± 0.28 |
| mattcl | input-kcen | 954.1 ± 177.4 | 223.1 | 1505.4 | 1.09 ± 0.33 |
| mattcl | input-lanjian | 955.7 ± 156.8 | 395.4 | 1387.1 | 1.09 ± 0.32 |
| mattcl | input-mattcl | 957.4 ± 171.2 | 230.0 | 1453.4 | 1.09 ± 0.33 |
| mattcl | input-pting | 976.3 ± 153.5 | 225.2 | 1380.4 | 1.11 ± 0.32 |
| mattcl-py | input-lanjian | 14652.6 ± 612.7 | 13467.9 | 18266.1 | 16.70 ± 4.05 |
| mattcl-py | input-pting | 14720.9 ± 2268.7 | 13346.7 | 45741.2 | 16.77 ± 4.77 |
| pting | input-lanjian | 14827.0 ± 479.4 | 13752.7 | 16986.0 | 16.89 ± 4.07 |
| mattcl-py | input-mattcl | 14829.3 ± 424.4 | 13826.2 | 17035.2 | 16.90 ± 4.06 |
| pting | input-pting | 14914.8 ± 740.8 | 13487.1 | 18185.6 | 16.99 ± 4.15 |
| mattcl-py | input-kcen | 14954.1 ± 605.5 | 13880.3 | 18100.3 | 17.04 ± 4.13 |
| pting | input-kcen | 15105.8 ± 539.9 | 14004.6 | 18301.3 | 17.21 ± 4.16 |
| pting | input-mattcl | 15368.4 ± 2615.7 | 13993.0 | 50475.9 | 17.51 ± 5.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|