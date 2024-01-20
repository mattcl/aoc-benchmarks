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
| lanjian | input-kcen | 922.2 ± 201.3 | 267.5 | 1206.3 | 1.00 |
| mattcl | input-pting | 967.6 ± 150.2 | 465.8 | 1385.6 | 1.05 ± 0.28 |
| lanjian | input-mattcl | 984.1 ± 179.3 | 286.4 | 1227.3 | 1.07 ± 0.30 |
| mattcl | input-mattcl | 993.2 ± 159.7 | 292.3 | 1180.6 | 1.08 ± 0.29 |
| lanjian | input-pting | 996.2 ± 175.4 | 217.0 | 1541.1 | 1.08 ± 0.30 |
| lanjian | input-lanjian | 1018.4 ± 130.5 | 423.5 | 1169.5 | 1.10 ± 0.28 |
| mattcl | input-kcen | 1018.5 ± 137.6 | 294.2 | 1487.2 | 1.10 ± 0.28 |
| mattcl | input-lanjian | 1021.3 ± 128.4 | 253.3 | 1165.6 | 1.11 ± 0.28 |
| mattcl-py | input-lanjian | 14408.6 ± 523.2 | 13285.3 | 17511.4 | 15.62 ± 3.46 |
| mattcl-py | input-pting | 14414.9 ± 599.2 | 13442.3 | 17498.8 | 15.63 ± 3.47 |
| pting | input-pting | 14654.1 ± 618.4 | 13698.6 | 18367.5 | 15.89 ± 3.53 |
| pting | input-lanjian | 14701.0 ± 576.7 | 13642.1 | 17523.5 | 15.94 ± 3.54 |
| mattcl-py | input-mattcl | 14774.3 ± 484.2 | 14125.6 | 17811.2 | 16.02 ± 3.54 |
| mattcl-py | input-kcen | 14874.0 ± 611.9 | 13838.5 | 18480.3 | 16.13 ± 3.58 |
| pting | input-kcen | 15126.8 ± 608.3 | 14009.8 | 18317.5 | 16.40 ± 3.64 |
| pting | input-mattcl | 15195.5 ± 721.8 | 14079.7 | 18707.7 | 16.48 ± 3.68 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|