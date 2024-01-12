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
| lanjian | input-kcen | 871.7 ± 208.8 | 137.6 | 1639.1 | 1.00 |
| lanjian | input-pting | 884.6 ± 166.8 | 344.9 | 1547.9 | 1.01 ± 0.31 |
| lanjian | input-mattcl | 892.4 ± 171.9 | 209.8 | 1122.5 | 1.02 ± 0.31 |
| lanjian | input-lanjian | 894.7 ± 155.0 | 197.6 | 1111.4 | 1.03 ± 0.30 |
| mattcl | input-lanjian | 917.2 ± 155.1 | 215.9 | 1106.4 | 1.05 ± 0.31 |
| mattcl | input-mattcl | 924.8 ± 178.7 | 272.3 | 1476.1 | 1.06 ± 0.33 |
| mattcl | input-kcen | 925.6 ± 162.9 | 240.3 | 1130.8 | 1.06 ± 0.32 |
| mattcl | input-pting | 925.9 ± 159.3 | 204.5 | 1100.4 | 1.06 ± 0.31 |
| mattcl-py | input-pting | 14210.5 ± 540.0 | 13333.2 | 17716.1 | 16.30 ± 3.95 |
| mattcl-py | input-lanjian | 14444.4 ± 786.7 | 13402.5 | 17497.3 | 16.57 ± 4.07 |
| pting | input-lanjian | 14505.1 ± 506.3 | 13618.8 | 17393.3 | 16.64 ± 4.03 |
| pting | input-pting | 14522.7 ± 669.6 | 13579.6 | 17551.5 | 16.66 ± 4.06 |
| mattcl-py | input-mattcl | 14732.3 ± 477.2 | 13766.4 | 17552.9 | 16.90 ± 4.09 |
| mattcl-py | input-kcen | 14788.3 ± 550.8 | 13823.7 | 17599.1 | 16.96 ± 4.11 |
| pting | input-kcen | 15018.8 ± 586.4 | 13997.4 | 17958.9 | 17.23 ± 4.18 |
| pting | input-mattcl | 15126.2 ± 726.0 | 13833.5 | 18287.2 | 17.35 ± 4.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|