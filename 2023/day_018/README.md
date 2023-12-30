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
| lanjian | input-pting | 922.6 ± 183.3 | 206.0 | 1148.3 | 1.00 |
| lanjian | input-lanjian | 925.4 ± 191.8 | 203.0 | 1132.4 | 1.00 ± 0.29 |
| lanjian | input-kcen | 939.4 ± 198.6 | 220.1 | 1591.5 | 1.02 ± 0.30 |
| lanjian | input-mattcl | 976.6 ± 144.1 | 314.3 | 1233.3 | 1.06 ± 0.26 |
| mattcl | input-lanjian | 982.8 ± 166.0 | 272.9 | 1190.8 | 1.07 ± 0.28 |
| mattcl | input-mattcl | 995.1 ± 168.0 | 312.2 | 1690.0 | 1.08 ± 0.28 |
| mattcl | input-pting | 1003.2 ± 147.1 | 462.2 | 1252.6 | 1.09 ± 0.27 |
| mattcl | input-kcen | 1011.4 ± 166.3 | 539.3 | 1577.1 | 1.10 ± 0.28 |
| mattcl-py | input-lanjian | 14703.5 ± 669.9 | 13668.2 | 17678.6 | 15.94 ± 3.25 |
| mattcl-py | input-pting | 14704.1 ± 1874.6 | 13454.2 | 39782.4 | 15.94 ± 3.76 |
| pting | input-pting | 14860.2 ± 570.6 | 13563.9 | 17346.5 | 16.11 ± 3.26 |
| pting | input-lanjian | 14906.2 ± 567.1 | 13559.7 | 18043.9 | 16.16 ± 3.27 |
| mattcl-py | input-mattcl | 15021.0 ± 548.3 | 13747.8 | 18662.9 | 16.28 ± 3.29 |
| mattcl-py | input-kcen | 15046.1 ± 697.9 | 13747.4 | 17820.0 | 16.31 ± 3.33 |
| pting | input-mattcl | 15283.3 ± 786.1 | 14135.4 | 18375.2 | 16.57 ± 3.40 |
| pting | input-kcen | 15299.8 ± 593.7 | 14336.6 | 17628.5 | 16.58 ± 3.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|