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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 ± 0.23 |
| mattcl | input-chancalan | 1.1 ± 0.1 | 0.6 | 1.8 | 1.02 ± 0.21 |
| lanjian | input-lanjian | 1.8 ± 0.2 | 1.3 | 3.2 | 1.65 ± 0.35 |
| lanjian | input-chancalan | 1.9 ± 0.3 | 1.2 | 2.9 | 1.71 ± 0.37 |
| lanjian | input-mattcl | 1.9 ± 0.3 | 1.6 | 3.3 | 1.73 ± 0.39 |
| chancalan | input-lanjian | 19.6 ± 0.7 | 18.7 | 22.5 | 17.57 ± 3.03 |
| chancalan | input-chancalan | 19.7 ± 0.6 | 18.6 | 22.4 | 17.68 ± 3.04 |
| chancalan | input-mattcl | 19.8 ± 0.7 | 18.5 | 22.3 | 17.72 ± 3.06 |
| mattcl-py | input-mattcl | 33.9 ± 0.8 | 33.1 | 37.4 | 30.43 ± 5.19 |
| mattcl-py | input-chancalan | 34.0 ± 0.9 | 32.9 | 36.7 | 30.48 ± 5.21 |
| mattcl-py | input-lanjian | 34.2 ± 1.0 | 33.0 | 37.4 | 30.66 ± 5.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|