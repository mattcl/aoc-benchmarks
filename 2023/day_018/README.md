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
| lanjian | input-kcen | 862.4 ± 207.4 | 113.9 | 1697.4 | 1.00 |
| lanjian | input-pting | 871.5 ± 170.3 | 167.5 | 1086.5 | 1.01 ± 0.31 |
| lanjian | input-lanjian | 875.5 ± 167.3 | 193.2 | 1607.8 | 1.02 ± 0.31 |
| lanjian | input-mattcl | 891.2 ± 153.5 | 157.5 | 1390.5 | 1.03 ± 0.31 |
| mattcl | input-lanjian | 899.5 ± 185.1 | 195.4 | 1124.0 | 1.04 ± 0.33 |
| mattcl | input-mattcl | 920.9 ± 177.7 | 227.7 | 1158.2 | 1.07 ± 0.33 |
| mattcl | input-pting | 926.3 ± 167.8 | 172.9 | 1313.3 | 1.07 ± 0.32 |
| mattcl | input-kcen | 964.8 ± 154.8 | 477.6 | 1592.6 | 1.12 ± 0.32 |
| mattcl-py | input-pting | 14552.4 ± 603.2 | 13542.0 | 17231.6 | 16.87 ± 4.12 |
| mattcl-py | input-lanjian | 14554.5 ± 423.1 | 13633.1 | 16665.5 | 16.88 ± 4.09 |
| pting | input-pting | 14764.3 ± 554.7 | 13637.2 | 17243.6 | 17.12 ± 4.17 |
| pting | input-lanjian | 14822.7 ± 593.2 | 13525.3 | 17600.0 | 17.19 ± 4.19 |
| mattcl-py | input-mattcl | 14991.6 ± 676.8 | 13722.4 | 18410.3 | 17.38 ± 4.25 |
| mattcl-py | input-kcen | 14993.9 ± 561.7 | 13637.1 | 18021.4 | 17.39 ± 4.23 |
| pting | input-kcen | 15171.6 ± 534.9 | 14051.9 | 17819.7 | 17.59 ± 4.28 |
| pting | input-mattcl | 15185.3 ± 633.5 | 14265.7 | 18376.2 | 17.61 ± 4.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|