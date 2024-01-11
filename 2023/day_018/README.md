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
| lanjian | input-lanjian | 941.2 ± 179.5 | 256.1 | 1378.5 | 1.00 |
| lanjian | input-pting | 947.8 ± 128.5 | 584.9 | 1145.1 | 1.01 ± 0.24 |
| lanjian | input-mattcl | 972.3 ± 191.2 | 242.4 | 1709.5 | 1.03 ± 0.28 |
| mattcl | input-pting | 984.9 ± 166.4 | 254.6 | 1642.0 | 1.05 ± 0.27 |
| lanjian | input-kcen | 988.2 ± 118.1 | 508.1 | 1133.5 | 1.05 ± 0.24 |
| mattcl | input-mattcl | 994.9 ± 171.5 | 255.0 | 1415.0 | 1.06 ± 0.27 |
| mattcl | input-lanjian | 1011.0 ± 157.1 | 271.8 | 1556.6 | 1.07 ± 0.26 |
| mattcl | input-kcen | 1021.6 ± 127.5 | 573.4 | 1530.6 | 1.09 ± 0.25 |
| mattcl-py | input-pting | 14568.7 ± 606.5 | 13265.4 | 17735.5 | 15.48 ± 3.02 |
| mattcl-py | input-lanjian | 14837.8 ± 2960.0 | 13641.9 | 55933.1 | 15.76 ± 4.35 |
| pting | input-pting | 14889.3 ± 695.7 | 13766.8 | 18020.2 | 15.82 ± 3.11 |
| mattcl-py | input-mattcl | 14960.8 ± 466.7 | 14023.8 | 18227.5 | 15.90 ± 3.07 |
| mattcl-py | input-kcen | 15014.4 ± 699.1 | 13699.6 | 18442.8 | 15.95 ± 3.13 |
| pting | input-lanjian | 15077.2 ± 2657.9 | 13577.8 | 50999.4 | 16.02 ± 4.16 |
| pting | input-kcen | 15158.1 ± 478.7 | 14173.4 | 17538.1 | 16.10 ± 3.11 |
| pting | input-mattcl | 15203.4 ± 486.5 | 14133.6 | 17839.2 | 16.15 ± 3.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|