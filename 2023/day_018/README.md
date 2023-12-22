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
| lanjian | input-pting | 815.7 ± 182.3 | 97.7 | 1031.0 | 1.00 |
| lanjian | input-mattcl | 846.8 ± 177.6 | 107.7 | 1266.1 | 1.04 ± 0.32 |
| mattcl | input-pting | 870.9 ± 158.4 | 162.1 | 1085.6 | 1.07 ± 0.31 |
| mattcl | input-mattcl | 909.6 ± 133.3 | 473.5 | 1554.8 | 1.12 ± 0.30 |
| mattcl-py | input-pting | 14485.2 ± 521.2 | 13263.8 | 16913.2 | 17.76 ± 4.02 |
| mattcl-py | input-mattcl | 14995.9 ± 633.1 | 13868.7 | 18265.0 | 18.38 ± 4.18 |
| pting | input-pting | 15104.5 ± 4986.7 | 13256.5 | 84031.1 | 18.52 ± 7.38 |
| pting | input-mattcl | 15132.3 ± 630.4 | 13816.1 | 17926.5 | 18.55 ± 4.22 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|