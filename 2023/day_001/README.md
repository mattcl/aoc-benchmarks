# Day 1 benchmarks

[link to problem](https://adventofcode.com/2023/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.1 | 1.9 | 1.00 |
| mattcl | input-chancalan | 1.1 ± 0.1 | 0.6 | 1.5 | 1.02 ± 0.21 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.6 | 1.9 | 1.06 ± 0.25 |
| lanjian | input-chancalan | 1.8 ± 0.2 | 1.3 | 3.3 | 1.71 ± 0.39 |
| lanjian | input-mattcl | 1.8 ± 0.2 | 1.3 | 2.7 | 1.72 ± 0.39 |
| lanjian | input-lanjian | 1.9 ± 0.3 | 1.2 | 3.2 | 1.79 ± 0.42 |
| chancalan | input-mattcl | 19.5 ± 0.6 | 18.4 | 22.5 | 18.22 ± 3.39 |
| chancalan | input-lanjian | 19.5 ± 0.8 | 18.5 | 22.8 | 18.25 ± 3.42 |
| chancalan | input-chancalan | 19.6 ± 0.8 | 18.5 | 22.4 | 18.35 ± 3.45 |
| mattcl-py | input-chancalan | 25.6 ± 0.8 | 24.5 | 28.7 | 23.92 ± 4.45 |
| mattcl-py | input-lanjian | 25.7 ± 0.9 | 24.8 | 29.4 | 24.03 ± 4.49 |
| mattcl-py | input-mattcl | 25.8 ± 1.0 | 24.7 | 29.1 | 24.08 ± 4.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|