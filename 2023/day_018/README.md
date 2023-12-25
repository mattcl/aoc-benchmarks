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
| lanjian | input-pting | 836.7 ± 162.8 | 119.3 | 1071.3 | 1.00 |
| lanjian | input-mattcl | 858.0 ± 158.6 | 138.2 | 1204.0 | 1.03 ± 0.28 |
| lanjian | input-lanjian | 863.3 ± 139.3 | 124.6 | 1054.1 | 1.03 ± 0.26 |
| mattcl | input-pting | 877.8 ± 142.4 | 305.8 | 1063.9 | 1.05 ± 0.27 |
| mattcl | input-mattcl | 893.6 ± 170.1 | 167.3 | 1564.0 | 1.07 ± 0.29 |
| mattcl | input-lanjian | 907.7 ± 146.8 | 109.0 | 1060.5 | 1.08 ± 0.27 |
| mattcl-py | input-pting | 14338.0 ± 603.5 | 13299.8 | 18552.9 | 17.14 ± 3.41 |
| mattcl-py | input-lanjian | 14518.3 ± 612.2 | 13331.5 | 17980.2 | 17.35 ± 3.45 |
| pting | input-pting | 14727.7 ± 608.5 | 13654.1 | 17888.5 | 17.60 ± 3.50 |
| pting | input-lanjian | 14800.7 ± 782.1 | 13571.5 | 18045.8 | 17.69 ± 3.57 |
| mattcl-py | input-mattcl | 14818.9 ± 529.9 | 13656.8 | 18311.1 | 17.71 ± 3.50 |
| pting | input-mattcl | 15101.0 ± 603.6 | 14286.2 | 17691.4 | 18.05 ± 3.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|