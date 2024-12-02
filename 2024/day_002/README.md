# Day 2 benchmarks

[link to problem](https://adventofcode.com/2024/day/2)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 2)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.5 | 2.2 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.2 | 1.03 ± 0.23 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.3 | 2.2 | 1.03 ± 0.24 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.7 | 2.3 | 1.04 ± 0.24 |
| lanjian | input-mattcl | 1.5 ± 0.1 | 0.6 | 1.8 | 1.06 ± 0.20 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.8 | 2.3 | 1.06 ± 0.21 |
| kcen | input-kcen | 1.7 ± 0.3 | 1.0 | 2.8 | 1.23 ± 0.31 |
| kcen | input-lanjian | 1.9 ± 0.4 | 1.0 | 2.7 | 1.33 ± 0.34 |
| kcen | input-mattcl | 2.1 ± 0.4 | 1.4 | 3.4 | 1.48 ± 0.36 |
| mattcl-py | input-mattcl | 18.5 ± 0.7 | 17.3 | 21.5 | 13.23 ± 2.25 |
| mattcl-py | input-lanjian | 18.8 ± 0.7 | 17.7 | 22.5 | 13.44 ± 2.29 |
| mattcl-py | input-kcen | 18.9 ± 0.6 | 18.0 | 21.9 | 13.50 ± 2.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>680</pre>|<pre>710</pre>|
|input-lanjian|<pre>564</pre>|<pre>604</pre>|
|input-mattcl|<pre>332</pre>|<pre>398</pre>|