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
| lanjian | input-lanjian | 879.3 ± 198.2 | 134.5 | 1482.3 | 1.00 |
| mattcl | input-lanjian | 892.0 ± 195.9 | 187.7 | 1083.0 | 1.01 ± 0.32 |
| lanjian | input-pting | 892.1 ± 165.9 | 156.9 | 1635.2 | 1.01 ± 0.30 |
| lanjian | input-mattcl | 893.6 ± 179.2 | 179.4 | 1243.7 | 1.02 ± 0.31 |
| lanjian | input-kcen | 903.4 ± 159.4 | 164.9 | 1387.1 | 1.03 ± 0.29 |
| mattcl | input-mattcl | 913.8 ± 174.4 | 251.9 | 1442.4 | 1.04 ± 0.31 |
| mattcl | input-pting | 930.6 ± 155.4 | 158.3 | 1369.3 | 1.06 ± 0.30 |
| mattcl | input-kcen | 956.1 ± 141.9 | 236.4 | 1398.7 | 1.09 ± 0.29 |
| mattcl-py | input-pting | 14500.8 ± 539.6 | 13547.2 | 18531.6 | 16.49 ± 3.77 |
| mattcl-py | input-lanjian | 14510.8 ± 530.5 | 13307.5 | 17551.9 | 16.50 ± 3.77 |
| pting | input-lanjian | 14812.4 ± 591.2 | 13871.4 | 17471.1 | 16.85 ± 3.86 |
| pting | input-pting | 14910.3 ± 3089.6 | 13435.0 | 57351.4 | 16.96 ± 5.19 |
| mattcl-py | input-mattcl | 14955.9 ± 710.9 | 13654.1 | 18086.7 | 17.01 ± 3.92 |
| mattcl-py | input-kcen | 14987.5 ± 583.9 | 13716.6 | 18146.1 | 17.04 ± 3.90 |
| pting | input-kcen | 15066.7 ± 537.3 | 13856.1 | 18369.5 | 17.13 ± 3.91 |
| pting | input-mattcl | 15195.9 ± 637.1 | 13919.2 | 18365.8 | 17.28 ± 3.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|