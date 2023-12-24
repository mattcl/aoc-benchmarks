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
| lanjian | input-pting | 891.9 ± 191.8 | 145.3 | 1432.0 | 1.00 |
| lanjian | input-lanjian | 893.2 ± 178.7 | 214.6 | 1116.1 | 1.00 ± 0.29 |
| lanjian | input-mattcl | 911.7 ± 193.4 | 204.1 | 1426.2 | 1.02 ± 0.31 |
| mattcl | input-pting | 937.9 ± 157.9 | 259.4 | 1136.4 | 1.05 ± 0.29 |
| mattcl | input-mattcl | 978.0 ± 147.4 | 404.3 | 1594.3 | 1.10 ± 0.29 |
| mattcl | input-lanjian | 991.5 ± 113.4 | 412.4 | 1140.1 | 1.11 ± 0.27 |
| mattcl-py | input-pting | 14495.9 ± 558.2 | 13678.0 | 17076.4 | 16.25 ± 3.55 |
| mattcl-py | input-lanjian | 14619.5 ± 594.3 | 13696.6 | 18222.8 | 16.39 ± 3.59 |
| pting | input-pting | 14764.3 ± 435.6 | 13720.2 | 16942.9 | 16.55 ± 3.59 |
| pting | input-lanjian | 14815.4 ± 519.1 | 13832.0 | 17630.9 | 16.61 ± 3.62 |
| mattcl-py | input-mattcl | 15037.2 ± 695.0 | 13658.5 | 18292.4 | 16.86 ± 3.71 |
| pting | input-mattcl | 15234.1 ± 706.5 | 13985.6 | 18600.6 | 17.08 ± 3.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|