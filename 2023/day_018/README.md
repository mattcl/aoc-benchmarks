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
| lanjian | input-mattcl | 927.1 ± 211.1 | 232.8 | 1748.6 | 1.00 |
| lanjian | input-lanjian | 927.7 ± 185.2 | 224.9 | 1634.8 | 1.00 ± 0.30 |
| lanjian | input-pting | 948.2 ± 153.5 | 528.7 | 1538.3 | 1.02 ± 0.29 |
| mattcl | input-lanjian | 968.9 ± 172.9 | 236.4 | 1349.5 | 1.05 ± 0.30 |
| mattcl | input-pting | 974.9 ± 161.4 | 289.0 | 1268.8 | 1.05 ± 0.30 |
| mattcl | input-mattcl | 1015.3 ± 150.7 | 279.7 | 1730.0 | 1.10 ± 0.30 |
| mattcl-py | input-lanjian | 14743.0 ± 603.3 | 13828.8 | 17751.4 | 15.90 ± 3.68 |
| pting | input-pting | 14852.7 ± 617.8 | 13806.1 | 18031.6 | 16.02 ± 3.71 |
| pting | input-lanjian | 14954.9 ± 470.7 | 14004.7 | 17486.0 | 16.13 ± 3.71 |
| mattcl-py | input-pting | 15011.1 ± 3926.6 | 13511.7 | 52733.9 | 16.19 ± 5.62 |
| mattcl-py | input-mattcl | 15115.2 ± 648.6 | 13922.3 | 18670.1 | 16.30 ± 3.78 |
| pting | input-mattcl | 15341.5 ± 715.9 | 14506.5 | 18354.4 | 16.55 ± 3.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|