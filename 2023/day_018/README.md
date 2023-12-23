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
| mattcl | input-lanjian | 734.7 ± 280.1 | 86.7 | 1450.1 | 1.00 |
| lanjian | input-lanjian | 797.9 ± 196.2 | 78.4 | 1108.1 | 1.09 ± 0.49 |
| lanjian | input-mattcl | 833.5 ± 181.3 | 79.6 | 1428.9 | 1.13 ± 0.50 |
| lanjian | input-pting | 835.9 ± 172.8 | 96.8 | 1270.4 | 1.14 ± 0.49 |
| mattcl | input-pting | 884.5 ± 157.0 | 391.5 | 1146.9 | 1.20 ± 0.51 |
| mattcl | input-mattcl | 910.4 ± 182.1 | 163.9 | 1577.8 | 1.24 ± 0.53 |
| mattcl-py | input-pting | 14456.6 ± 618.1 | 13305.6 | 17554.4 | 19.68 ± 7.55 |
| mattcl-py | input-lanjian | 14457.4 ± 542.4 | 13618.5 | 17814.6 | 19.68 ± 7.54 |
| pting | input-pting | 14686.2 ± 579.9 | 13687.6 | 17640.3 | 19.99 ± 7.66 |
| pting | input-lanjian | 14738.9 ± 498.5 | 13447.9 | 17309.5 | 20.06 ± 7.68 |
| mattcl-py | input-mattcl | 14892.2 ± 553.5 | 14056.9 | 17536.0 | 20.27 ± 7.77 |
| pting | input-mattcl | 15077.6 ± 558.3 | 13861.7 | 17710.4 | 20.52 ± 7.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|