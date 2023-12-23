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
| lanjian | input-pting | 856.6 ± 196.4 | 143.5 | 1170.6 | 1.00 |
| lanjian | input-lanjian | 901.0 ± 159.9 | 198.1 | 1130.6 | 1.05 ± 0.30 |
| mattcl | input-pting | 919.8 ± 179.2 | 293.8 | 1423.8 | 1.07 ± 0.32 |
| lanjian | input-mattcl | 923.6 ± 150.1 | 198.6 | 1434.7 | 1.08 ± 0.30 |
| mattcl | input-lanjian | 934.2 ± 180.2 | 178.2 | 1356.0 | 1.09 ± 0.33 |
| mattcl | input-mattcl | 958.4 ± 154.4 | 443.8 | 1327.8 | 1.12 ± 0.31 |
| mattcl-py | input-lanjian | 14548.5 ± 615.7 | 13274.0 | 17817.6 | 16.98 ± 3.96 |
| pting | input-lanjian | 14906.3 ± 685.9 | 13845.6 | 18153.3 | 17.40 ± 4.07 |
| mattcl-py | input-mattcl | 14950.3 ± 572.0 | 13803.6 | 18684.0 | 17.45 ± 4.06 |
| mattcl-py | input-pting | 15089.8 ± 5039.7 | 13354.7 | 75103.2 | 17.62 ± 7.14 |
| pting | input-mattcl | 15141.7 ± 583.0 | 13844.5 | 18327.5 | 17.68 ± 4.11 |
| pting | input-pting | 15708.3 ± 6985.8 | 13678.2 | 70838.3 | 18.34 ± 9.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|