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
| mattcl | input-lanjian | 856.1 ± 225.1 | 125.3 | 1226.7 | 1.00 |
| lanjian | input-pting | 866.2 ± 202.8 | 98.9 | 1322.6 | 1.01 ± 0.36 |
| lanjian | input-lanjian | 873.0 ± 167.7 | 176.7 | 1115.7 | 1.02 ± 0.33 |
| lanjian | input-mattcl | 885.6 ± 168.7 | 297.9 | 1378.8 | 1.03 ± 0.34 |
| lanjian | input-kcen | 907.5 ± 141.6 | 154.6 | 1070.3 | 1.06 ± 0.32 |
| mattcl | input-pting | 924.1 ± 131.6 | 513.5 | 1118.5 | 1.08 ± 0.32 |
| mattcl | input-kcen | 937.4 ± 149.3 | 381.0 | 1438.0 | 1.09 ± 0.34 |
| mattcl | input-mattcl | 997.8 ± 142.8 | 432.9 | 1499.6 | 1.17 ± 0.35 |
| mattcl-py | input-lanjian | 14651.2 ± 653.7 | 13377.3 | 18020.9 | 17.11 ± 4.56 |
| pting | input-lanjian | 14838.3 ± 645.8 | 13783.2 | 17851.8 | 17.33 ± 4.62 |
| mattcl-py | input-kcen | 14880.5 ± 492.2 | 13703.1 | 17679.5 | 17.38 ± 4.61 |
| pting | input-pting | 14963.1 ± 1631.9 | 13823.6 | 36548.0 | 17.48 ± 4.97 |
| mattcl-py | input-pting | 14963.6 ± 3988.6 | 13146.0 | 59036.0 | 17.48 ± 6.54 |
| mattcl-py | input-mattcl | 14975.3 ± 556.1 | 13940.1 | 17739.4 | 17.49 ± 4.64 |
| pting | input-kcen | 15264.7 ± 697.7 | 13883.6 | 18425.4 | 17.83 ± 4.76 |
| pting | input-mattcl | 15824.9 ± 3581.7 | 14107.0 | 53824.8 | 18.48 ± 6.41 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|