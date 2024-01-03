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
| lanjian | input-kcen | 849.5 ± 199.3 | 173.9 | 1586.4 | 1.00 |
| lanjian | input-lanjian | 866.5 ± 176.5 | 144.9 | 1117.1 | 1.02 ± 0.32 |
| lanjian | input-pting | 887.1 ± 175.0 | 138.9 | 1320.6 | 1.04 ± 0.32 |
| mattcl | input-pting | 889.9 ± 185.0 | 171.9 | 1452.2 | 1.05 ± 0.33 |
| lanjian | input-mattcl | 904.1 ± 154.4 | 223.4 | 1520.9 | 1.06 ± 0.31 |
| mattcl | input-lanjian | 915.7 ± 174.3 | 245.4 | 1450.9 | 1.08 ± 0.33 |
| mattcl | input-kcen | 932.1 ± 182.9 | 197.7 | 1674.9 | 1.10 ± 0.34 |
| mattcl | input-mattcl | 969.2 ± 139.2 | 459.6 | 1599.0 | 1.14 ± 0.31 |
| mattcl-py | input-pting | 14503.0 ± 651.0 | 13331.8 | 17737.3 | 17.07 ± 4.08 |
| mattcl-py | input-lanjian | 14594.9 ± 557.6 | 13559.6 | 17099.3 | 17.18 ± 4.08 |
| pting | input-pting | 14797.6 ± 641.5 | 13552.4 | 17594.5 | 17.42 ± 4.16 |
| mattcl-py | input-kcen | 14870.9 ± 536.0 | 13700.4 | 17287.8 | 17.51 ± 4.16 |
| pting | input-lanjian | 14945.7 ± 749.1 | 13510.2 | 18442.7 | 17.59 ± 4.22 |
| mattcl-py | input-mattcl | 15003.6 ± 573.1 | 14138.2 | 18128.3 | 17.66 ± 4.20 |
| pting | input-mattcl | 15198.0 ± 718.9 | 14060.4 | 18372.4 | 17.89 ± 4.28 |
| pting | input-kcen | 15205.3 ± 636.4 | 14202.4 | 18422.8 | 17.90 ± 4.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|