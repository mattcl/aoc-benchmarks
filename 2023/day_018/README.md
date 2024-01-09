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
| lanjian | input-pting | 895.5 ± 180.7 | 129.8 | 1536.3 | 1.00 |
| lanjian | input-lanjian | 899.2 ± 151.1 | 175.2 | 1101.1 | 1.00 ± 0.26 |
| lanjian | input-kcen | 901.5 ± 162.5 | 152.8 | 1110.2 | 1.01 ± 0.27 |
| mattcl | input-pting | 901.5 ± 177.6 | 199.7 | 1502.3 | 1.01 ± 0.28 |
| lanjian | input-mattcl | 905.8 ± 169.5 | 104.9 | 1086.4 | 1.01 ± 0.28 |
| mattcl | input-kcen | 908.1 ± 168.6 | 214.0 | 1117.2 | 1.01 ± 0.28 |
| mattcl | input-lanjian | 939.7 ± 155.3 | 362.4 | 1429.4 | 1.05 ± 0.27 |
| mattcl | input-mattcl | 953.5 ± 177.9 | 121.8 | 1691.9 | 1.06 ± 0.29 |
| mattcl-py | input-pting | 14669.5 ± 696.0 | 13524.7 | 17932.8 | 16.38 ± 3.40 |
| pting | input-pting | 14797.4 ± 532.1 | 13763.6 | 17699.8 | 16.52 ± 3.39 |
| pting | input-lanjian | 14959.0 ± 637.6 | 13942.1 | 17821.0 | 16.70 ± 3.44 |
| mattcl-py | input-mattcl | 15018.5 ± 544.1 | 13707.1 | 17792.9 | 16.77 ± 3.44 |
| mattcl-py | input-kcen | 15154.6 ± 685.5 | 14184.6 | 18625.0 | 16.92 ± 3.50 |
| pting | input-mattcl | 15247.4 ± 652.7 | 14215.2 | 18290.3 | 17.03 ± 3.51 |
| pting | input-kcen | 15291.6 ± 713.7 | 14435.9 | 18392.9 | 17.08 ± 3.54 |
| mattcl-py | input-lanjian | 15308.0 ± 5304.1 | 13448.8 | 69458.3 | 17.09 ± 6.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|