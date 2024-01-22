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
| mattcl | input-kcen | 886.2 ± 215.5 | 148.0 | 1418.7 | 1.00 |
| mattcl | input-pting | 894.8 ± 208.5 | 163.3 | 1507.4 | 1.01 ± 0.34 |
| lanjian | input-mattcl | 922.1 ± 189.5 | 310.6 | 1488.6 | 1.04 ± 0.33 |
| lanjian | input-pting | 925.8 ± 169.3 | 195.5 | 1269.0 | 1.04 ± 0.32 |
| lanjian | input-kcen | 943.9 ± 169.3 | 220.1 | 1169.6 | 1.07 ± 0.32 |
| mattcl | input-mattcl | 949.7 ± 163.4 | 220.2 | 1355.9 | 1.07 ± 0.32 |
| mattcl | input-lanjian | 974.2 ± 147.6 | 205.8 | 1624.2 | 1.10 ± 0.31 |
| lanjian | input-lanjian | 986.9 ± 108.1 | 538.7 | 1138.1 | 1.11 ± 0.30 |
| mattcl-py | input-pting | 14635.7 ± 573.4 | 13376.7 | 17369.3 | 16.51 ± 4.07 |
| mattcl-py | input-lanjian | 14657.6 ± 676.9 | 13745.7 | 18205.6 | 16.54 ± 4.09 |
| pting | input-lanjian | 14764.8 ± 560.9 | 13745.8 | 17671.8 | 16.66 ± 4.10 |
| pting | input-pting | 14776.9 ± 509.2 | 13823.4 | 17915.8 | 16.67 ± 4.09 |
| mattcl-py | input-kcen | 15031.2 ± 606.4 | 14043.7 | 17756.7 | 16.96 ± 4.18 |
| mattcl-py | input-mattcl | 15044.8 ± 638.7 | 14001.7 | 18213.0 | 16.98 ± 4.19 |
| pting | input-mattcl | 15159.9 ± 517.9 | 14095.5 | 18272.8 | 17.11 ± 4.20 |
| pting | input-kcen | 15215.2 ± 646.3 | 13985.3 | 18290.5 | 17.17 ± 4.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|