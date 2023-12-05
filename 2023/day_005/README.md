# Day 5 benchmarks

[link to problem](https://adventofcode.com/2023/day/5)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 5)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 675.9 ± 211.4 | 57.0 | 926.7 | 1.00 |
| lanjian | input-pting | 738.0 ± 188.1 | 120.1 | 1195.0 | 1.09 ± 0.44 |
| mattcl | input-lanjian | 749.0 ± 180.9 | 72.3 | 924.8 | 1.11 ± 0.44 |
| mattcl | input-mattcl | 775.1 ± 114.7 | 114.6 | 1187.9 | 1.15 ± 0.40 |
| lanjian | input-mattcl | 782.9 ± 141.8 | 99.0 | 1364.2 | 1.16 ± 0.42 |
| lanjian | input-lanjian | 788.9 ± 183.0 | 131.0 | 1520.3 | 1.17 ± 0.45 |
| mattcl-py | input-mattcl | 15042.3 ± 464.2 | 13990.5 | 18040.9 | 22.25 ± 6.99 |
| pting | input-mattcl | 15104.8 ± 633.5 | 13951.5 | 18271.2 | 22.35 ± 7.05 |
| mattcl-py | input-pting | 15450.1 ± 601.2 | 14766.0 | 18271.5 | 22.86 ± 7.20 |
| pting | input-pting | 15739.2 ± 867.9 | 14609.0 | 19225.1 | 23.28 ± 7.39 |
| mattcl-py | input-lanjian | 16852.9 ± 561.4 | 15864.8 | 20208.2 | 24.93 ± 7.84 |
| pting | input-lanjian | 16993.7 ± 595.0 | 16084.6 | 19862.0 | 25.14 ± 7.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|