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
| lanjian | input-mattcl | 955.0 ± 175.2 | 272.5 | 1193.6 | 1.00 |
| lanjian | input-pting | 964.3 ± 183.8 | 222.8 | 1360.1 | 1.01 ± 0.27 |
| lanjian | input-lanjian | 965.6 ± 148.3 | 369.8 | 1184.6 | 1.01 ± 0.24 |
| lanjian | input-kcen | 973.4 ± 164.0 | 228.4 | 1218.3 | 1.02 ± 0.25 |
| mattcl | input-mattcl | 977.0 ± 209.4 | 260.4 | 1695.4 | 1.02 ± 0.29 |
| mattcl | input-pting | 978.8 ± 173.6 | 409.1 | 1699.8 | 1.02 ± 0.26 |
| mattcl | input-lanjian | 986.9 ± 154.5 | 330.1 | 1192.3 | 1.03 ± 0.25 |
| mattcl | input-kcen | 1009.3 ± 167.8 | 349.2 | 1688.4 | 1.06 ± 0.26 |
| mattcl-py | input-lanjian | 14735.9 ± 642.8 | 13453.0 | 18441.4 | 15.43 ± 2.91 |
| pting | input-lanjian | 14901.9 ± 555.7 | 13986.3 | 17858.9 | 15.60 ± 2.92 |
| pting | input-pting | 14904.9 ± 582.9 | 14028.2 | 17985.6 | 15.61 ± 2.93 |
| mattcl-py | input-mattcl | 15077.9 ± 574.7 | 13961.8 | 17753.0 | 15.79 ± 2.96 |
| mattcl-py | input-kcen | 15128.9 ± 596.7 | 14033.9 | 18544.3 | 15.84 ± 2.97 |
| pting | input-mattcl | 15241.5 ± 567.0 | 14130.5 | 17785.1 | 15.96 ± 2.99 |
| pting | input-kcen | 15244.3 ± 552.6 | 14265.7 | 18208.2 | 15.96 ± 2.98 |
| mattcl-py | input-pting | 15278.6 ± 4037.2 | 13669.2 | 49927.0 | 16.00 ± 5.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|