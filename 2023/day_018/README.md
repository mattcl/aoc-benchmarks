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
| lanjian | input-pting | 913.3 ± 170.2 | 261.4 | 1268.0 | 1.00 |
| lanjian | input-lanjian | 942.4 ± 172.4 | 207.7 | 1330.5 | 1.03 ± 0.27 |
| mattcl | input-pting | 970.0 ± 164.1 | 292.4 | 1184.7 | 1.06 ± 0.27 |
| lanjian | input-mattcl | 974.8 ± 151.4 | 175.3 | 1164.9 | 1.07 ± 0.26 |
| mattcl | input-mattcl | 1000.0 ± 159.7 | 256.7 | 1188.0 | 1.09 ± 0.27 |
| mattcl | input-lanjian | 1004.3 ± 131.0 | 582.7 | 1600.3 | 1.10 ± 0.25 |
| mattcl-py | input-lanjian | 14625.4 ± 572.6 | 13357.5 | 17921.6 | 16.01 ± 3.05 |
| mattcl-py | input-pting | 14672.4 ± 572.1 | 13615.1 | 18022.3 | 16.07 ± 3.06 |
| pting | input-pting | 14862.7 ± 557.2 | 13591.6 | 17702.7 | 16.27 ± 3.09 |
| pting | input-lanjian | 14944.9 ± 793.2 | 13636.0 | 18423.9 | 16.36 ± 3.17 |
| mattcl-py | input-mattcl | 15094.8 ± 679.1 | 13855.3 | 18422.3 | 16.53 ± 3.17 |
| pting | input-mattcl | 15239.0 ± 617.5 | 14241.0 | 18977.3 | 16.69 ± 3.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|