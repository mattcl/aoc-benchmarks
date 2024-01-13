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
| lanjian | input-pting | 882.6 ± 169.2 | 168.9 | 1087.9 | 1.00 |
| mattcl | input-lanjian | 885.3 ± 182.5 | 169.5 | 1070.6 | 1.00 ± 0.28 |
| lanjian | input-lanjian | 889.4 ± 188.3 | 169.5 | 1068.7 | 1.01 ± 0.29 |
| mattcl | input-pting | 901.6 ± 157.6 | 182.9 | 1100.6 | 1.02 ± 0.27 |
| lanjian | input-kcen | 903.9 ± 158.4 | 176.2 | 1096.3 | 1.02 ± 0.27 |
| lanjian | input-mattcl | 912.1 ± 162.1 | 191.4 | 1472.2 | 1.03 ± 0.27 |
| mattcl | input-kcen | 938.3 ± 152.2 | 210.6 | 1452.3 | 1.06 ± 0.27 |
| mattcl | input-mattcl | 940.7 ± 120.5 | 441.7 | 1133.0 | 1.07 ± 0.25 |
| mattcl-py | input-pting | 14321.7 ± 586.6 | 13425.5 | 17632.4 | 16.23 ± 3.18 |
| mattcl-py | input-lanjian | 14386.0 ± 582.7 | 13483.0 | 17638.9 | 16.30 ± 3.19 |
| pting | input-pting | 14537.9 ± 504.5 | 13598.6 | 17428.0 | 16.47 ± 3.21 |
| pting | input-lanjian | 14663.5 ± 632.3 | 13589.7 | 17526.3 | 16.61 ± 3.27 |
| mattcl-py | input-mattcl | 14768.7 ± 545.0 | 13761.6 | 17515.7 | 16.73 ± 3.27 |
| mattcl-py | input-kcen | 14796.2 ± 674.2 | 13911.4 | 18378.0 | 16.76 ± 3.30 |
| pting | input-kcen | 15024.2 ± 580.5 | 13843.0 | 18169.2 | 17.02 ± 3.33 |
| pting | input-mattcl | 15026.0 ± 379.1 | 14401.2 | 16797.6 | 17.02 ± 3.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|