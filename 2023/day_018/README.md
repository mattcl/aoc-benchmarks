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
| lanjian | input-pting | 872.2 ± 187.4 | 207.9 | 1128.8 | 1.00 |
| lanjian | input-lanjian | 915.9 ± 175.6 | 173.9 | 1126.4 | 1.05 ± 0.30 |
| mattcl | input-pting | 938.9 ± 171.7 | 252.1 | 1494.4 | 1.08 ± 0.30 |
| mattcl | input-kcen | 943.0 ± 181.1 | 215.4 | 1181.2 | 1.08 ± 0.31 |
| lanjian | input-mattcl | 944.4 ± 144.4 | 212.0 | 1145.7 | 1.08 ± 0.29 |
| lanjian | input-kcen | 946.1 ± 130.8 | 445.5 | 1672.9 | 1.08 ± 0.28 |
| mattcl | input-lanjian | 959.0 ± 166.4 | 217.8 | 1158.9 | 1.10 ± 0.30 |
| mattcl | input-mattcl | 973.5 ± 150.4 | 250.1 | 1255.2 | 1.12 ± 0.30 |
| mattcl-py | input-pting | 14387.2 ± 631.6 | 13342.1 | 17874.8 | 16.49 ± 3.62 |
| mattcl-py | input-lanjian | 14421.9 ± 480.5 | 13695.5 | 16882.9 | 16.53 ± 3.60 |
| pting | input-pting | 14554.0 ± 534.1 | 13625.1 | 17740.2 | 16.69 ± 3.64 |
| pting | input-lanjian | 14707.1 ± 652.1 | 13820.1 | 17574.9 | 16.86 ± 3.70 |
| mattcl-py | input-kcen | 14847.0 ± 561.3 | 13818.2 | 17502.1 | 17.02 ± 3.71 |
| mattcl-py | input-mattcl | 14852.2 ± 614.5 | 13878.8 | 17754.6 | 17.03 ± 3.73 |
| pting | input-mattcl | 15102.7 ± 567.0 | 13999.5 | 17991.0 | 17.32 ± 3.78 |
| pting | input-kcen | 15136.4 ± 582.9 | 14134.1 | 18294.1 | 17.35 ± 3.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|