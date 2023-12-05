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


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-mattcl | 812.3 ± 154.2 | 102.6 | 1006.8 | 1.00 |
| mattcl | input-mattcl | 842.8 ± 145.8 | 202.6 | 1272.0 | 1.04 ± 0.27 |
| lanjian | input-lanjian | 890.7 ± 128.4 | 241.3 | 1306.1 | 1.10 ± 0.26 |
| mattcl | input-lanjian | 942.3 ± 3567.3 | 30.8 | 50993.2 | 1.16 ± 4.40 |
| mattcl-py | input-mattcl | 17828.5 ± 577.1 | 16839.5 | 20916.7 | 21.95 ± 4.23 |
| mattcl-py | input-lanjian | 21410.4 ± 673.3 | 20609.6 | 24275.6 | 26.36 ± 5.07 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|