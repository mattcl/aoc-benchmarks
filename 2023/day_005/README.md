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
| mattcl | input-mattcl | 799.0 ± 157.4 | 93.6 | 1213.3 | 1.00 |
| mattcl | input-lanjian | 810.9 ± 181.0 | 87.2 | 1018.1 | 1.01 ± 0.30 |
| lanjian | input-mattcl | 838.8 ± 172.7 | 94.9 | 1357.2 | 1.05 ± 0.30 |
| lanjian | input-lanjian | 884.4 ± 181.2 | 129.4 | 1506.7 | 1.11 ± 0.31 |
| pting | input-mattcl | 17909.3 ± 1359.4 | 16904.1 | 32544.7 | 22.42 ± 4.73 |
| mattcl-py | input-mattcl | 18040.8 ± 814.3 | 16956.9 | 21446.2 | 22.58 ± 4.56 |
| pting | input-lanjian | 21071.5 ± 608.0 | 20195.2 | 23772.1 | 26.37 ± 5.25 |
| mattcl-py | input-lanjian | 21392.4 ± 719.9 | 20302.8 | 24436.9 | 26.78 ± 5.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|