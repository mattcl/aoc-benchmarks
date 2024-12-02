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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 2.1 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.1 | 1.00 ± 0.21 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.4 | 2.5 | 1.01 ± 0.21 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.5 | 1.7 | 1.02 ± 0.20 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.20 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.7 | 2.0 | 1.03 ± 0.20 |
| kcen | input-kcen | 1.6 ± 0.3 | 0.9 | 2.6 | 1.18 ± 0.27 |
| kcen | input-lanjian | 1.8 ± 0.4 | 1.2 | 2.9 | 1.32 ± 0.33 |
| kcen | input-mattcl | 2.0 ± 0.4 | 0.9 | 2.7 | 1.47 ± 0.35 |
| mattcl-py | input-mattcl | 18.4 ± 0.6 | 17.5 | 21.4 | 13.67 ± 2.13 |
| mattcl-py | input-lanjian | 18.7 ± 0.6 | 17.9 | 22.5 | 13.91 ± 2.16 |
| mattcl-py | input-kcen | 18.8 ± 0.6 | 17.7 | 21.7 | 13.92 ± 2.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>680</pre>|<pre>710</pre>|
|input-lanjian|<pre>564</pre>|<pre>604</pre>|
|input-mattcl|<pre>332</pre>|<pre>398</pre>|