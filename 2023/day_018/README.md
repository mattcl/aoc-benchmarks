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
| lanjian | input-kcen | 826.6 ± 216.5 | 95.3 | 1361.6 | 1.00 |
| mattcl | input-kcen | 842.3 ± 186.7 | 139.5 | 1038.7 | 1.02 ± 0.35 |
| mattcl | input-lanjian | 859.6 ± 179.2 | 181.2 | 1074.6 | 1.04 ± 0.35 |
| mattcl | input-mattcl | 878.1 ± 151.7 | 188.8 | 1082.5 | 1.06 ± 0.33 |
| mattcl | input-pting | 882.2 ± 131.8 | 399.2 | 1118.9 | 1.07 ± 0.32 |
| lanjian | input-pting | 891.2 ± 119.3 | 346.7 | 1107.7 | 1.08 ± 0.32 |
| lanjian | input-lanjian | 900.9 ± 119.3 | 118.2 | 1042.7 | 1.09 ± 0.32 |
| lanjian | input-mattcl | 912.2 ± 154.1 | 177.9 | 1743.6 | 1.10 ± 0.34 |
| mattcl-py | input-pting | 14242.8 ± 609.6 | 13420.1 | 17975.9 | 17.23 ± 4.57 |
| mattcl-py | input-lanjian | 14292.5 ± 571.9 | 13163.4 | 17250.2 | 17.29 ± 4.58 |
| pting | input-pting | 14480.0 ± 455.2 | 13749.6 | 17512.7 | 17.52 ± 4.62 |
| pting | input-lanjian | 14549.9 ± 558.5 | 13611.3 | 18323.3 | 17.60 ± 4.66 |
| mattcl-py | input-kcen | 14687.9 ± 552.8 | 13897.4 | 17986.8 | 17.77 ± 4.70 |
| mattcl-py | input-mattcl | 14715.7 ± 598.0 | 13892.7 | 17632.8 | 17.80 ± 4.72 |
| pting | input-kcen | 14927.8 ± 505.0 | 13892.4 | 17470.9 | 18.06 ± 4.77 |
| pting | input-mattcl | 15009.3 ± 610.3 | 14016.8 | 18050.9 | 18.16 ± 4.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|