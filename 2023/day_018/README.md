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
| lanjian | input-pting | 799.4 ± 169.0 | 142.4 | 1138.9 | 1.00 |
| lanjian | input-lanjian | 821.9 ± 168.8 | 113.1 | 1139.2 | 1.03 ± 0.30 |
| lanjian | input-mattcl | 827.5 ± 164.1 | 130.0 | 1367.7 | 1.04 ± 0.30 |
| mattcl | input-lanjian | 838.3 ± 156.4 | 151.4 | 1015.5 | 1.05 ± 0.30 |
| mattcl | input-mattcl | 854.6 ± 168.7 | 159.6 | 1599.7 | 1.07 ± 0.31 |
| mattcl | input-pting | 864.1 ± 126.4 | 388.6 | 1068.1 | 1.08 ± 0.28 |
| mattcl-py | input-lanjian | 14187.2 ± 529.7 | 13338.5 | 17544.8 | 17.75 ± 3.81 |
| pting | input-pting | 14407.0 ± 593.0 | 13459.2 | 17554.8 | 18.02 ± 3.88 |
| pting | input-lanjian | 14491.7 ± 605.5 | 13526.9 | 18101.3 | 18.13 ± 3.91 |
| mattcl-py | input-pting | 14523.9 ± 2906.4 | 13084.5 | 45626.6 | 18.17 ± 5.29 |
| mattcl-py | input-mattcl | 14586.5 ± 536.3 | 13768.9 | 17555.4 | 18.25 ± 3.92 |
| pting | input-mattcl | 14868.6 ± 503.7 | 13729.7 | 17758.3 | 18.60 ± 3.98 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|