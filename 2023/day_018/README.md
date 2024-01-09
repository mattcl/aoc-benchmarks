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
| lanjian | input-mattcl | 898.2 ± 219.3 | 167.9 | 1598.3 | 1.00 |
| mattcl | input-lanjian | 929.3 ± 201.2 | 214.1 | 1173.3 | 1.03 ± 0.34 |
| lanjian | input-pting | 947.5 ± 162.3 | 229.7 | 1188.2 | 1.05 ± 0.31 |
| mattcl | input-pting | 956.1 ± 174.7 | 245.9 | 1361.3 | 1.06 ± 0.32 |
| lanjian | input-lanjian | 963.1 ± 152.4 | 299.0 | 1624.1 | 1.07 ± 0.31 |
| lanjian | input-kcen | 963.3 ± 159.1 | 257.0 | 1451.0 | 1.07 ± 0.32 |
| mattcl | input-mattcl | 991.1 ± 159.3 | 237.2 | 1358.0 | 1.10 ± 0.32 |
| mattcl | input-kcen | 1013.2 ± 141.9 | 253.6 | 1187.7 | 1.13 ± 0.32 |
| mattcl-py | input-lanjian | 14735.5 ± 612.3 | 13545.4 | 17990.7 | 16.41 ± 4.06 |
| mattcl-py | input-pting | 14758.5 ± 660.2 | 13625.4 | 17769.5 | 16.43 ± 4.08 |
| pting | input-pting | 14966.2 ± 535.3 | 13862.7 | 18152.7 | 16.66 ± 4.11 |
| pting | input-lanjian | 15033.2 ± 699.0 | 13854.4 | 18069.1 | 16.74 ± 4.16 |
| mattcl-py | input-mattcl | 15074.7 ± 484.0 | 13995.0 | 17352.6 | 16.78 ± 4.13 |
| mattcl-py | input-kcen | 15092.1 ± 612.7 | 13950.3 | 18174.3 | 16.80 ± 4.16 |
| pting | input-kcen | 15361.3 ± 692.8 | 14267.2 | 19154.2 | 17.10 ± 4.25 |
| pting | input-mattcl | 15382.1 ± 701.3 | 14306.6 | 18243.9 | 17.13 ± 4.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|