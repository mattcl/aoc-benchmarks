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
| lanjian | input-lanjian | 662.8 ± 236.8 | 165.4 | 1146.0 | 1.00 |
| lanjian | input-mattcl | 717.2 ± 254.6 | 204.2 | 1433.8 | 1.08 ± 0.55 |
| mattcl | input-lanjian | 849.8 ± 3305.9 | 173.2 | 47232.2 | 1.28 ± 5.01 |
| lanjian | input-pting | 958.1 ± 140.3 | 216.9 | 1384.4 | 1.45 ± 0.56 |
| mattcl | input-pting | 959.5 ± 164.9 | 245.1 | 1150.9 | 1.45 ± 0.57 |
| lanjian | input-kcen | 961.1 ± 141.2 | 224.7 | 1163.3 | 1.45 ± 0.56 |
| mattcl | input-mattcl | 983.9 ± 162.7 | 259.5 | 1201.1 | 1.48 ± 0.58 |
| mattcl | input-kcen | 990.9 ± 150.8 | 240.6 | 1407.3 | 1.50 ± 0.58 |
| mattcl-py | input-pting | 14596.7 ± 626.0 | 13346.3 | 17716.2 | 22.02 ± 7.93 |
| pting | input-pting | 14833.9 ± 659.0 | 13587.8 | 17833.8 | 22.38 ± 8.06 |
| mattcl-py | input-lanjian | 14933.9 ± 2004.3 | 13917.1 | 42322.3 | 22.53 ± 8.60 |
| mattcl-py | input-mattcl | 15081.5 ± 692.7 | 13910.8 | 18135.5 | 22.75 ± 8.20 |
| mattcl-py | input-kcen | 15122.3 ± 654.1 | 13764.7 | 18365.9 | 22.82 ± 8.21 |
| pting | input-mattcl | 15200.8 ± 475.6 | 14015.7 | 17537.9 | 22.93 ± 8.23 |
| pting | input-kcen | 15253.7 ± 657.2 | 13894.1 | 18405.4 | 23.01 ± 8.28 |
| pting | input-lanjian | 15331.6 ± 3164.5 | 13982.4 | 46046.6 | 23.13 ± 9.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|