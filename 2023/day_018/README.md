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
| lanjian | input-pting | 879.4 ± 152.3 | 186.1 | 1105.7 | 1.00 |
| lanjian | input-mattcl | 883.4 ± 158.5 | 146.5 | 1324.7 | 1.00 ± 0.25 |
| mattcl | input-kcen | 885.9 ± 188.4 | 205.5 | 1146.3 | 1.01 ± 0.28 |
| lanjian | input-kcen | 900.7 ± 148.4 | 215.8 | 1329.5 | 1.02 ± 0.24 |
| lanjian | input-lanjian | 903.0 ± 117.1 | 449.9 | 1088.0 | 1.03 ± 0.22 |
| mattcl | input-pting | 907.2 ± 3541.6 | 113.1 | 50603.6 | 1.03 ± 4.03 |
| mattcl | input-mattcl | 920.3 ± 161.5 | 210.7 | 1638.6 | 1.05 ± 0.26 |
| mattcl | input-lanjian | 938.1 ± 122.1 | 447.9 | 1096.8 | 1.07 ± 0.23 |
| mattcl-py | input-pting | 14347.9 ± 583.9 | 13574.2 | 16675.5 | 16.32 ± 2.90 |
| pting | input-pting | 14583.3 ± 533.0 | 13472.3 | 16984.2 | 16.58 ± 2.93 |
| mattcl-py | input-kcen | 14686.4 ± 530.0 | 13636.7 | 17763.4 | 16.70 ± 2.95 |
| pting | input-lanjian | 14693.6 ± 673.5 | 13912.2 | 18147.0 | 16.71 ± 2.99 |
| mattcl-py | input-lanjian | 14705.3 ± 2362.1 | 13436.9 | 45458.6 | 16.72 ± 3.95 |
| mattcl-py | input-mattcl | 14806.0 ± 686.9 | 13726.0 | 18048.1 | 16.84 ± 3.02 |
| pting | input-kcen | 15093.1 ± 657.6 | 13964.2 | 17704.0 | 17.16 ± 3.06 |
| pting | input-mattcl | 15167.1 ± 2076.3 | 13927.3 | 42948.2 | 17.25 ± 3.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|