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
| lanjian | input-pting | 825.4 ± 199.6 | 112.6 | 1325.2 | 1.00 |
| lanjian | input-mattcl | 850.5 ± 183.9 | 75.1 | 1348.8 | 1.03 ± 0.33 |
| lanjian | input-kcen | 855.9 ± 177.4 | 106.9 | 1075.0 | 1.04 ± 0.33 |
| lanjian | input-lanjian | 856.9 ± 154.6 | 149.4 | 1030.4 | 1.04 ± 0.31 |
| mattcl | input-lanjian | 866.7 ± 173.3 | 187.5 | 1185.0 | 1.05 ± 0.33 |
| mattcl | input-mattcl | 869.8 ± 180.9 | 157.0 | 1184.1 | 1.05 ± 0.34 |
| mattcl | input-pting | 885.4 ± 164.3 | 352.1 | 1381.8 | 1.07 ± 0.33 |
| mattcl | input-kcen | 891.7 ± 169.4 | 163.4 | 1412.4 | 1.08 ± 0.33 |
| mattcl-py | input-pting | 14476.8 ± 544.3 | 13687.4 | 18014.5 | 17.54 ± 4.29 |
| mattcl-py | input-lanjian | 14514.3 ± 495.5 | 13271.7 | 17899.0 | 17.58 ± 4.29 |
| pting | input-pting | 14787.7 ± 705.0 | 13653.1 | 18120.6 | 17.92 ± 4.42 |
| pting | input-lanjian | 14833.0 ± 586.8 | 13607.8 | 17868.3 | 17.97 ± 4.40 |
| mattcl-py | input-kcen | 15054.2 ± 640.5 | 13887.5 | 17959.1 | 18.24 ± 4.48 |
| pting | input-kcen | 15072.6 ± 452.1 | 14134.5 | 17739.6 | 18.26 ± 4.45 |
| mattcl-py | input-mattcl | 15122.8 ± 877.0 | 13805.7 | 18007.7 | 18.32 ± 4.56 |
| pting | input-mattcl | 15137.0 ± 609.9 | 13670.9 | 17787.4 | 18.34 ± 4.50 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|