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
| lanjian | input-pting | 892.4 ± 153.5 | 322.4 | 1106.8 | 1.00 |
| lanjian | input-lanjian | 902.7 ± 131.8 | 450.3 | 1217.2 | 1.01 ± 0.23 |
| mattcl | input-lanjian | 905.2 ± 192.7 | 232.1 | 1545.3 | 1.01 ± 0.28 |
| mattcl | input-kcen | 917.5 ± 177.7 | 195.1 | 1162.9 | 1.03 ± 0.27 |
| lanjian | input-mattcl | 926.9 ± 122.3 | 417.6 | 1083.6 | 1.04 ± 0.23 |
| lanjian | input-kcen | 933.1 ± 108.4 | 446.2 | 1087.7 | 1.05 ± 0.22 |
| mattcl | input-pting | 943.9 ± 130.2 | 369.9 | 1123.8 | 1.06 ± 0.23 |
| mattcl | input-mattcl | 948.0 ± 157.1 | 278.4 | 1223.9 | 1.06 ± 0.25 |
| mattcl-py | input-pting | 14348.4 ± 662.1 | 13357.2 | 17496.9 | 16.08 ± 2.86 |
| mattcl-py | input-lanjian | 14392.8 ± 766.1 | 13461.0 | 18485.4 | 16.13 ± 2.90 |
| pting | input-pting | 14582.0 ± 712.6 | 13529.1 | 18339.0 | 16.34 ± 2.92 |
| pting | input-lanjian | 14603.0 ± 594.1 | 13754.5 | 17690.8 | 16.36 ± 2.89 |
| mattcl-py | input-kcen | 14827.1 ± 672.8 | 13930.9 | 18000.1 | 16.62 ± 2.96 |
| mattcl-py | input-mattcl | 14946.6 ± 1783.9 | 13759.4 | 38337.7 | 16.75 ± 3.51 |
| pting | input-kcen | 14990.6 ± 444.4 | 13990.7 | 17721.4 | 16.80 ± 2.93 |
| pting | input-mattcl | 15043.9 ± 630.5 | 13958.4 | 18341.4 | 16.86 ± 2.98 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|