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
| mattcl | input-lanjian | 922.2 ± 216.8 | 187.1 | 1252.2 | 1.00 |
| mattcl | input-pting | 936.9 ± 183.7 | 265.4 | 1253.9 | 1.02 ± 0.31 |
| lanjian | input-pting | 956.4 ± 151.3 | 344.3 | 1335.4 | 1.04 ± 0.29 |
| lanjian | input-lanjian | 958.7 ± 182.1 | 279.5 | 1700.1 | 1.04 ± 0.31 |
| lanjian | input-kcen | 959.6 ± 174.6 | 203.8 | 1390.3 | 1.04 ± 0.31 |
| lanjian | input-mattcl | 969.3 ± 166.1 | 235.7 | 1169.6 | 1.05 ± 0.31 |
| mattcl | input-mattcl | 982.4 ± 144.8 | 277.0 | 1587.0 | 1.07 ± 0.30 |
| mattcl | input-kcen | 994.9 ± 143.5 | 422.7 | 1678.2 | 1.08 ± 0.30 |
| mattcl-py | input-lanjian | 14468.5 ± 614.0 | 13336.8 | 17203.6 | 15.69 ± 3.75 |
| pting | input-lanjian | 14661.4 ± 599.5 | 13597.6 | 17545.1 | 15.90 ± 3.79 |
| mattcl-py | input-kcen | 14800.9 ± 630.0 | 13603.4 | 17758.6 | 16.05 ± 3.84 |
| mattcl-py | input-mattcl | 14877.9 ± 735.6 | 13892.6 | 17807.7 | 16.13 ± 3.88 |
| mattcl-py | input-pting | 14879.5 ± 4829.6 | 13450.4 | 67885.8 | 16.14 ± 6.47 |
| pting | input-pting | 14899.2 ± 3330.5 | 13526.9 | 60643.0 | 16.16 ± 5.24 |
| pting | input-kcen | 15092.1 ± 570.8 | 14106.4 | 17687.9 | 16.37 ± 3.90 |
| pting | input-mattcl | 15103.5 ± 611.3 | 13901.7 | 17690.4 | 16.38 ± 3.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|