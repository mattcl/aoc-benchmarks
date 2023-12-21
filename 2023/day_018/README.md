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

- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 719.9 ± 311.6 | 123.1 | 1554.1 | 1.00 |
| mattcl | input-pting | 907.4 ± 200.8 | 166.1 | 1136.9 | 1.26 ± 0.61 |
| mattcl-py | input-pting | 14531.6 ± 570.0 | 13545.2 | 17713.1 | 20.19 ± 8.77 |
| pting | input-pting | 15023.9 ± 1999.5 | 13826.4 | 41480.3 | 20.87 ± 9.45 |
| pting | input-mattcl | 15176.2 ± 565.3 | 13902.5 | 18386.2 | 21.08 ± 9.16 |
| mattcl-py | input-mattcl | 15621.2 ± 4471.1 | 13954.2 | 55494.5 | 21.70 ± 11.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|