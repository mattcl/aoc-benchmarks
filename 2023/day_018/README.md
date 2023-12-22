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
| lanjian | input-mattcl | 835.4 ± 176.5 | 157.1 | 1031.4 | 1.00 |
| mattcl | input-lanjian | 840.0 ± 196.0 | 214.3 | 1219.3 | 1.01 ± 0.32 |
| mattcl | input-mattcl | 854.3 ± 184.3 | 297.8 | 1406.2 | 1.02 ± 0.31 |
| lanjian | input-pting | 858.3 ± 139.2 | 252.4 | 1073.5 | 1.03 ± 0.27 |
| mattcl | input-pting | 873.8 ± 141.0 | 329.9 | 1274.5 | 1.05 ± 0.28 |
| lanjian | input-lanjian | 881.3 ± 110.8 | 241.2 | 1029.5 | 1.05 ± 0.26 |
| mattcl-py | input-lanjian | 14476.2 ± 509.9 | 13645.0 | 17457.8 | 17.33 ± 3.71 |
| mattcl-py | input-pting | 14644.4 ± 741.8 | 13564.9 | 17593.4 | 17.53 ± 3.81 |
| pting | input-pting | 14751.9 ± 656.7 | 13600.1 | 18227.2 | 17.66 ± 3.81 |
| pting | input-lanjian | 14799.3 ± 507.4 | 13624.8 | 17027.4 | 17.72 ± 3.79 |
| mattcl-py | input-mattcl | 14940.5 ± 637.8 | 13898.9 | 18401.5 | 17.88 ± 3.85 |
| pting | input-mattcl | 15190.6 ± 600.3 | 14226.4 | 17655.7 | 18.18 ± 3.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|